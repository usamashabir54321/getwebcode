<template>
    <div class="no-bottom no-top" id="content">
        <div id="top"></div>
        
        <!-- section begin -->
        <section id="subheader" class="text-light" data-bgimage="url(/preview/gigaland/assets/images/background/subheader.jpg) top">
            <div class="center-y relative text-center">
                <div class="container">
                    <div class="row">

                        <div class="col-md-12 text-center">
                            <h1>Pricing</h1>
                            <p>Anim pariatur cliche reprehenderit</p>
                        </div>
                        <div class="clearfix"></div>
                    </div>
                </div>
            </div>
        </section>
        <!-- section close -->
        
        <!-- section begin -->
        <section>
            <div class="container">
                <div class="row">
                    <div class="col text-center"> 

                        <div class="switch-set">
                            <div>Monthly</div>                              
                            <div><input id="sw-1" class="switch" type="checkbox" /></div>                   
                            <div>Yearly</div>
                            <div class="spacer-20"></div>
                        </div>
                        
                    </div>
                </div>

                <div class="row sequence">
                    <div class="col-lg-4 col-md-6 col-sm-12 sq-item wow">
                        <div class="pricing-s1 mb30">
                            <div class="top">
                                <h2>Free</h2>
                                <p class="plan-tagline">Basic</p>            
                            </div>
                            <div class="mid text-light bg-color">
                                <p class="price">
                                    <span class="currency">$</span>
                                    <span class="m opt-1">0</span>
                                    <span class="y opt-2">0</span>
                                    <span class="month">p/mo</span>
                                </p>               
                            </div>

                            <div class="bottom">

                                <ul>
                                    <li><i class="fa fa-check"></i>1 device</li>
                                    <li><i class="fa fa-check"></i>Daily reminder</li>
                                    <li><i class="fa fa-check"></i>Simple reporting</li>
                                    <li><i class="fa fa-check"></i>Standart dashboard</li>
                                    <li><i class="fa fa-check"></i>Email Notification</li>
                                    <li><i class="fa fa-check"></i>Email Support</li>
                                </ul>
                            </div>

                            <div class="action">
                                <nuxt-link to="/template/gigaland/light/register" class="btn-main">Sign Up Now</nuxt-link>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-12 sq-item wow">
                        <div class="pricing-s1 mb30">
                            <div class="top">
                                <h2>Pro</h2>
                                <p class="plan-tagline">For Individuals</p>
                            </div>
                            <div class="mid text-light bg-color">
                                <p class="price">
                                    <span class="currency">$</span>
                                    <span class="m opt-1">9.59</span>
                                    <span class="y opt-2">7.46</span>
                                    <span class="month">p/mo</span>
                                </p>     
                            </div>
                            <div class="bottom">
                                <ul>
                                    <li><i class="fa fa-check"></i>Up to 2 devices</li>
                                    <li><i class="fa fa-check"></i>Daily reminder</li>
                                    <li><i class="fa fa-check"></i>Detailed reporting</li>
                                    <li><i class="fa fa-check"></i>Interactive dashboard</li>
                                    <li><i class="fa fa-check"></i>Email and SMS notification</li>
                                    <li><i class="fa fa-check"></i>24/7 Customer Support</li>
                                </ul>
                            </div>

                            <div class="action">
                                <nuxt-link to="/template/gigaland/light/register" class="btn-main">Sign Up Now</nuxt-link>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-md-6 col-sm-12 sq-item wow">
                        <div class="pricing-s1 mb30">
                            <div class="top">
                                <h2>For Teams</h2>
                                <p class="plan-tagline">Best for organization</p>
                            </div>
                            <div class="mid text-light bg-color">
                                <p class="price">
                                    <span class="currency">$</span>
                                    <span class="m opt-1">24.99</span>
                                    <span class="y opt-2">16.49</span>
                                    <span class="month">p/mo</span>
                                </p>     
                            </div>
                            <div class="bottom">
                                <ul>
                                    <li><i class="fa fa-check"></i>Up to 10 devices</li>
                                    <li><i class="fa fa-check"></i>Daily reminder</li>
                                    <li><i class="fa fa-check"></i>Detailed reporting</li>
                                    <li><i class="fa fa-check"></i>Interactive dashboard</li>
                                    <li><i class="fa fa-check"></i>Email and SMS notification</li>
                                    <li><i class="fa fa-check"></i>24/7 Customer Support</li>
                                </ul>
                            </div>

                            <div class="action">
                                <nuxt-link to="/template/gigaland/light/register" class="btn-main">Sign Up Now</nuxt-link>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-6 offset-lg-3 text-center">
                        <small>Price shown are in USD and VAT inclusive.</small>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
    export default {
        layout:'gigaland/light',
        head: {
            title: 'GIGALAND LIGHT PRICING TABLE',
            script:[
            { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>
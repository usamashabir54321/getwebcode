<template>
    <div class="no-bottom no-top" id="content">
        <div id="top"></div>
        
        <section class="full-height relative no-top no-bottom vertical-center" style="background: url(/preview/gigaland/assets/images/background/6.jpg) center top / cover !important;" data-stellar-background-ratio=".5">
            <div class="overlay-gradient t50">
                <div class="center-y relative">
                    <div class="container">
                        <div class="row align-items-center">

                            <div class="col-lg-4 offset-lg-4 wow fadeIn bg-color" data-wow-delay=".5s">
                                <div class="box-rounded padding40">
                                    <h3 class="mb10">Sign In</h3>
                                    <p>Login using an existing account or create a new account <a href="#">here<span></span></a>.</p>
                                    <form name="contactForm" id='contact_form' class="form-border" method="post" action='https://gigaland.io/blank.php'>

                                        <div class="field-set">
                                            <input type='text' name='email' id='email' class="form-control" placeholder="username">
                                        </div>
                                        
                                        <div class="field-set">
                                            <input type='password' name='password' id='password' class="form-control" placeholder="password">
                                        </div>
                                        
                                        <div class="field-set">
                                            <input type='submit' id='send_message' value='Submit' class="btn btn-main btn-fullwidth color-2">
                                        </div>
                                        
                                        <div class="clearfix"></div>
                                        
                                        <div class="spacer-single"></div>

                                        <!-- social icons -->
                                        <ul class="list s3">
                                            <li>Login with:</li>
                                            <li><a href="#">Facebook</a></li>
                                            <li><a href="#">Google</a></li>
                                        </ul>
                                        <!-- social icons close -->
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>      
        
    </div>
</template>

<script>
    export default {
        layout:'gigaland/grey',
        head: {
            title: 'GIGALAND GRAY LOGIN',
            script:[
                { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>
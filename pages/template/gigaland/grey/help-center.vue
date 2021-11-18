<template>
    <body class="dark-scheme de-grey">
        <div id="wrapper">
            <TmpltGigalandGreyHead />
            <!-- content begin -->
            <div class="no-bottom no-top" id="content">
                <div id="top"></div>
                
                <!-- section begin -->
                <section id="subheader">

                    <div class="center-y relative text-center mt-30">
                        <div class="container">
                            <div class="row">
                                <div class="col-md-8 offset-md-2">
                                <div class="col text-center">
                                    <div class="spacer-single"></div>
                                    <h1>Help Center</h1>
                                    
                                    <form action='https://gigaland.io/blank.php' class="row" id='form_sb' method="post" name="myForm">
                                    <div class="col text-center">
                                        <div class="spacer-10"></div>
                                        <input class="form-control" id='name_1' name='name_1' placeholder="type your question here" type='text'> <a href="#" id="btn-submit"><i class="arrow_right"></i></a>
                                    </div>
                                    </form>
                                    
                                    <div class="spacer-20"></div>
                                    
                                    <p>eg. create item, create wallet.</p>
                                </div>
                                <div class="clearfix"></div>
                            </div>
                            </div>
                        </div>
                    </div>

                </section>
                <!-- section close -->

                <!-- section begin -->
                <section aria-label="section">
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-4 col-md-6 mb25">
                                <div class="feature-box f-boxed style-3 text-center">
                                    <div class="text">
                                        <h4>Getting Started</h4>
                                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam.</p>
                                        <a href="#" class="btn-main">Read more</a>
                                    </div>
                                </div>
                            </div>    

                            <div class="col-lg-4 col-md-6 mb25">
                                <div class="feature-box f-boxed style-3 text-center">
                                    <div class="text">
                                        <h4>Buying</h4>
                                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam.</p>
                                        <a href="#" class="btn-main">Read more</a>
                                    </div>
                                </div>
                            </div>  

                            <div class="col-lg-4 col-md-6 mb25">
                                <div class="feature-box f-boxed style-3 text-center">
                                    <div class="text">
                                        <h4>Selling</h4>
                                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam.</p>
                                        <a href="#" class="btn-main">Read more</a>
                                    </div>
                                </div>
                            </div>  

                            <div class="col-lg-4 col-md-6 mb25">
                                <div class="feature-box f-boxed style-3 text-center">
                                    <div class="text">
                                        <h4>Creating</h4>
                                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam.</p>
                                        <a href="#" class="btn-main">Read more</a>
                                    </div>
                                </div>
                            </div>  

                            <div class="col-lg-4 col-md-6 mb25">
                                <div class="feature-box f-boxed style-3 text-center">
                                    <div class="text">
                                        <h4>Partners</h4>
                                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam.</p>
                                        <a href="#" class="btn-main">Read more</a>
                                    </div>
                                </div>
                            </div>  

                            <div class="col-lg-4 col-md-6 mb25">
                                <div class="feature-box f-boxed style-3 text-center">
                                    <div class="text">
                                        <h4>Developers</h4>
                                        <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam.</p>
                                        <a href="#" class="btn-main">Read more</a>
                                    </div>
                                </div>
                            </div>                      
                        </div>
                    </div>
                </section>

            </div>
            <!-- content close -->
            <a href="#" id="back-to-top"></a>
            <TmpltGigalandGreyFoot />
        </div>
    </body>
</template>

<script>
    export default {
        layout:'templtGigaland',
        head: {
            title: 'GIGALAND GRAY HELP CENTER',
            script:[
                { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>
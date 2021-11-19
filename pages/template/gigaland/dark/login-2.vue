<template>
    <div class="no-bottom no-top" id="content">
        <div id="top"></div>
        
        <!-- section begin -->
        <section id="subheader" class="text-light" data-bgimage="url(/preview/gigaland/assets/images/background/subheader.jpg) top">
                <div class="center-y relative text-center">
                    <div class="container">
                        <div class="row">
                            
                            <div class="col-md-12 text-center">
                                <h1>User Login</h1>
                                <p>Anim pariatur cliche reprehenderit</p>
                            </div>
                            <div class="clearfix"></div>
                        </div>
                    </div>
                </div>
        </section>
        <!-- section close -->
        

        <section aria-label="section">
            <div class="container">
                <div class="row">
                    <div class="col-md-6 offset-md-3">
                        <form name="contactForm" id='contact_form' class="form-border" method="post" action='https://gigaland.io/blank.php'>
                                <h3>Login to your account</h3>

                                        <div class="field-set">
                                            <label>Username</label>
                                            <input type='text' name='name' id='name' class="form-control" placeholder="">
                                        </div>


                                        <div class="field-set">
                                            <label>Password</label>
                                            <input type='text' name='email' id='email' class="form-control" placeholder="">
                                        </div>

                                <div id='submit'>
                                    <input type='submit' id='send_message' value='Login' class="btn btn-main color-2">

                                    <div id='mail_success' class='success'>Your message has been sent successfully.</div>
                                    <div id='mail_fail' class='error'>Sorry, error occured this time sending your message.</div>

                                    <div class="clearfix"></div>

                                    <div class="spacer-single"></div>

                                    <!-- social icons -->
                                    <ul class="list s3">
                                        <li>Or login with:</li>
                                        <li><a href="#">Facebook</a></li>
                                        <li><a href="#">Google</a></li>
                                        <li><a href="#">Instagram</a></li>
                                    </ul>
                                    <!-- social icons close -->

                                </div>
                                
                            </form>
                    </div>
                </div>
            </div>
        </section>
        
        
    </div>
</template>

<script>
    export default {
        layout:'gigaland/dark',
        head: {
            title: 'GIGALAND DARK LOGIN 2',
            script:[
                { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>
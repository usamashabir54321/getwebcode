<template>
    <div class="no-bottom no-top" id="content">
        <div id="top"></div>
        
        <!-- section begin -->
        <section id="subheader" class="text-light" data-bgimage="url(/preview/gigaland/assets/images/background/subheader.jpg) top">
                <div class="center-y relative text-center">
                    <div class="container">
                        <div class="row">
                            
                            <div class="col-md-12 text-center">
                                <h1>Progress Bar</h1>
                            </div>
                            <div class="clearfix"></div>
                        </div>
                    </div>
                </div>
        </section>
        <!-- section close -->
        

        <!-- section begin -->
        <section aria-label="section">
            <div class="container">
                <div class="row">
                    
                    <div class="col-md-4">
                        <div class="skill-bar style-2">
                            <h5>Art</h5>
                            <div class="de-progress">
                                <div class="value"></div>
                                <div class="progress-bar" data-value="80%">
                                </div>
                            </div>
                        </div>

                        <div class="skill-bar style-2">
                            <h5>Music</h5>
                            <div class="de-progress">
                                <div class="value"></div>
                                <div class="progress-bar" data-value="70%">
                                </div>
                            </div>
                        </div>

                    </div>

                    <div class="col-md-4">
                        <div class="skill-bar style-2">
                            <h5>Domain Names</h5>
                            <div class="de-progress">
                                <div class="value"></div>
                                <div class="progress-bar" data-value="70%">
                                </div>
                            </div>
                        </div>

                        <div class="skill-bar style-2">
                            <h5>Virtual Worlds</h5>
                            <div class="de-progress">
                                <div class="value"></div>
                                <div class="progress-bar" data-value="90%">
                                </div>
                            </div>
                        </div>

                    </div>

                    <div class="col-md-4">
                        <div class="skill-bar style-2">
                            <h5>Trading Cards</h5>
                            <div class="de-progress">
                                <div class="value"></div>
                                <div class="progress-bar" data-value="90%">
                                </div>
                            </div>
                        </div>

                        <div class="skill-bar style-2">
                            <h5>Collectibles</h5>
                            <div class="de-progress">
                                <div class="value"></div>
                                <div class="progress-bar" data-value="75%">
                                </div>
                            </div>
                        </div>

                    </div>
                    
                </div>
            </div>
        </section>
        <!-- section close -->

    </div>
</template>

<script>
    export default {
        layout:'gigaland/light',
        head: {
            title: 'GIGALAND LIGHT PROGRESS BAR',
            script:[
                { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>
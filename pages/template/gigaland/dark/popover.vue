<template>
    <div class="no-bottom no-top" id="content">
        <div id="top"></div>
        <!-- section begin -->
        <section id="subheader" class="text-light" data-bgimage="url(/preview/gigaland/assets/images/background/subheader.jpg) top">
                <div class="center-y relative text-center">
                    <div class="container">
                        <div class="row">
                            
                            <div class="col-md-12 text-center">
                                <h1>Popover</h1>
                            </div>
                            <div class="clearfix"></div>
                        </div>
                    </div>
                </div>
        </section>
        <!-- section close -->
        

        <!-- section begin -->
         <section id="section-fun-facts" class="pt60 pb60">
                <div class="container">
                    <div class="row">
                        <div class="col-md-12">
                            <button type="button" class="btn btn-lg btn-danger" data-bs-toggle="popover" title="Popover title" data-bs-content="And here's some amazing content. It's very engaging. Right?">Click to toggle popover</button>

                            <div class="spacer-single"></div>

                            <h3>Four directions</h3>
                            <p>Four options are available: top, right, bottom, and left aligned. Directions are mirrored when using Bootstrap in RTL.</p>
                            <button type="button" class="btn btn-main" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="top" data-bs-content="Top popover">
                              Popover on top
                            </button>
                            <button type="button" class="btn btn-main" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="right" data-bs-content="Right popover">
                              Popover on right
                            </button>
                            <button type="button" class="btn btn-main" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="bottom" data-bs-content="Bottom popover">
                              Popover on bottom
                            </button>
                            <button type="button" class="btn btn-main" data-bs-container="body" data-bs-toggle="popover" data-bs-placement="left" data-bs-content="Left popover">
                              Popover on left
                            </button>

                        </div>
                    </div>
                </div>
            </section>
        
        <!-- section close -->

    </div>
</template>

<script>
    export default {
        layout:'gigaland/dark',
        head: {
            title: 'GIGALAND DARK POPOVERS',
            script:[
                { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>

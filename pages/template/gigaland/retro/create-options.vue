<template>
    <div class="no-bottom no-top" id="content">
        <div id="top"></div>
        
        <!-- section begin -->
        <section id="subheader">
                <div class="center-y relative text-center">
                    <div class="container">
                        <div class="row">
                            
                            <div class="col-md-12 text-center">
                                <h1>Create Collectible</h1>
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
                <div class="row wow fadeIn">
                    <div class="col-md-6 offset-md-3">
                        <p>Choose "Single" if you want your collectible to be one of a kind or "Multiple" if you want to sell one collectible times</p>
                        <a href="/template/gigaland/retro/create-single" class="opt-create">
                            <img src="/preview/gigaland/assets/images/misc/grey-coll-single.png" alt="">
                            <h3>Single</h3>
                        </a>
                        <a href="/template/gigaland/retro/create-multiple" class="opt-create">
                            <img src="/preview/gigaland/assets/images/misc/grey-coll-multiple.png" alt="">
                            <h3>Multiple</h3>
                        </a>
                    </div>                             
                </div>
            </div>
        </section>

    </div>
</template>

<script>
    export default {
        layout:'gigaland/retro',
        head: {
            title: 'GIGALAND RETRO CREATE OPTIONS',
            script:[
                { src:'/preview/gigaland/assets/js/designesia.js' , defer:'defer' },
            ],
        },
    }
</script>
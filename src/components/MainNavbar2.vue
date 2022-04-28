<template>
    <div class="container mt-3 p-3">
        <ul class="nav nav-tabs justify-content-center bg-light ">
            <li class="nav-item" v-for="item in mainNavbarItems" :key="item.id">
                <router-link class="nav-link text-dark "  :to="item.path">{{item.itemName}}</router-link>
            </li>
        </ul>
        <img src="../../src/assets/body-image.webp" alt="image-body" class="mt-3 img-fluid">
        
        <div class="text-start mt-3">
        
        <h2>Future technology: 22 ideas about to change our world</h2>
        <p>The future is coming, and sooner than you think. These emerging technologies will change 
        the way we live, how we look after our bodies and help us avert a climate disaster.</p>
        </div>

            <router-link to="/facebook">
                    <i class="fa fa-facebook mx-2 p-3"></i>
            </router-link>
            <i class="fa fa-instagram mx-2 p-3"></i>
            <i class="fa fa-twitter mx-2 p-3"></i>
            <i class="fa fa-whatsapp mx-2 p-3"></i>
            <a href="https://www.youtube.com/results?search_query=tech"><i class="fa fa-youtube mx-2 p-3"></i></a>
        <div>

        </div>

    </div>
</template>

<script>
    export default {
        name:'MainNavbar2',
        data(){
            return{
                mainNavbarItems:[
                    {id:1,itemName:'New',path:"/"},
                    {id:2,itemName:'Future Tech',path:"/"},
                    {id:3,itemName:'Nature',path:"/nature"},
                    {id:4,itemName:'Human Body',path:"/"},
                    {id:5,itemName:'Everyday Science',path:"/"},
                    {id:6,itemName:'Planet Earth',path:"/"},
                ]
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>
<template>
    <div class="container mt-3">
        <ul class="nav navbar-tabs bg-secondary ">
            <li class="nav-item" v-for="item in navItems" :key="item.id">
                <router-link class="nav-link text-white" :to="item.path" >
                    {{item.name}}
                </router-link>
            </li>
        </ul>  
        <p class="mark text-center p-5">This search feature uses functional cookies to work, but they 
            are being blocked by your browser. 
            Check your ad-blocker settings for blocked scripts to enable this feature.</p>

            <h1>Poeple and Departement</h1>
            <ul class="nav ">
                <li class="nav-item">
                    <router-link class="nav-link" to="/">Find People</router-link>
                </li>

                <li class="nav-item">
                    <router-link class="nav-link" to="/">Academic College</router-link>
                </li>

                <li class="nav-item">
                    <router-link class="nav-link" to="/">All Ohio State</router-link>
                </li>
            </ul>
            <div class="bg-dark text-white">
                <hr>
                <h6>The Ohio state university</h6>

                 <router-link to="/about" @click="showMessage()"> <i class="fa fa-instagram mx-5"></i></router-link>
                 <router-link to="/about"> <i class="fa fa-facebook mx-5"></i></router-link>
                 <router-link to="/about"> <i class="fa fa-twitter mx-5"></i></router-link>
                 <router-link to="/about"> <i class="fa fa-youtube mx-5"></i></router-link>
                 <router-link to="/about"> <i class="fa fa-whatsapp mx-5"></i></router-link>
                
            </div>
    </div>
</template>

<script>
    export default {
        name:'NavbarNature',
        data(){
            return{
                navItems:[
                    {id:1,name:'Futures Student',path:''},
                    {id:2,name:'Current Student',path:''},
                    {id:3,name:'Alumi',path:''},
                    {id:4,name:'Faculty/Staff',path:''},
                    {id:5,name:'Academics',path:''},
                    {id:6,name:'Research',path:''},
                    {id:7,name:'initatives',path:''},
                    {id:8,name:'Athletices',path:''},
                ]
            }
        },
        methods:{
            showMessage(){
                alert('Only for test in the future we try improve the page ')
            }
        }
    }
</script>

<style lang="scss" scoped>

</style>
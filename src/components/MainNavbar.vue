<template>
    <div class="container mt-2">
        <div class="row">
                <div class="col-md-8">
                    <ul class="nav nav-tabs border justify-content-center bg-light">
                        <li class="nav-item">
                            <router-link class="nav-link text-dark border-end" to="/bbc">Subscribe To BBC </router-link>
                        </li>
                        
                        <li class="nav-item">
                            <router-link class="nav-link text-dark border-end" to="/issue">Previous issue </router-link>
                        </li>

                        <li class="nav-item">
                            <router-link class="nav-link text-dark" to="/issue">QA </router-link>
                        </li>
                </ul>
            </div>
            <div class="col-md-4">
                <ul class="nav nav-tabs border justify-content-center bg-light">
                <img src="../../src/assets/user.png" alt="userName-icon" id="img-usericon" class="align-center mt-2">
                    <li class="nav-item">
                        <router-link class="nav-link text-dark" to="/signin">Signin</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link text-dark" to="/register"> | Register</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name:'MainNavbar'
    }
</script>

<style lang="scss" scoped>
#img-usericon{
    max-width:  30px;
    max-height: 30px;
}
</style>
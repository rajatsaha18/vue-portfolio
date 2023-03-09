<template>
    <div class="my-header">
        <nav class="navbar fixed-top navbar-expand-md navbar-dark bg-dark">
            <div class="container">
                <router-link :to="{ name: 'home' }" class="navbar-brand">RAJAT SAHA</router-link>
                <ul class="navbar-nav">
                    <li><router-link :to="{ name: 'about' }" class="nav-link text-white"><i
                                class="fa-solid fa-address-card"></i> About</router-link></li>
                    <li><router-link :to="{ name: 'my-work' }" class="nav-link text-white"><i
                                class="fa-sharp fa-solid fa-house-laptop"></i> My Work</router-link></li>
                    <li><router-link :to="{ name: 'find-developer' }" class="nav-link text-white"><i
                                class="fa-regular fa-user"></i> Find Developer</router-link></li>
                    <li><router-link :to="{ name: 'account' }" class="nav-link text-white"><i class="fa-solid fa-lock"></i>
                            Account</router-link></li>

                </ul>
            </div>
        </nav>
    </div>
</template>
  
<script>
export default {
    name: 'MyHeader',
}
</script>
  
<style scoped></style>
<template>
    <nav class="navbar navbar-expand-md bg-light">
        <div class="container-fluid  d-md-flex flex-column">
            <router-link :to="{name: 'home'}" class="navbar-brand">Boolpress</router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link :to="{name: 'postsIndex'}" class="nav-link voce">Posts</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'about'}" class="nav-link voce">About</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'contactUs'}" class="nav-link voce">Contact</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.voce{
    padding: 1rem!important;
}
.voce:focus-within{
    padding: 1rem;
    background-color:cadetblue;
    color: white !important;;
}
</style>

<template>
  <div>
    <div class="container-fluid bg-light p-3 m-auto">
        <div class="row col-10 m-auto justify-content-center">
            <img src="../components/logo-boolean.png" alt="img" class="img-f w-25 col-3">
            <ul class="col-5 lista list-unstyled list-group list-group-horizontal">
                    <li class="nav-item">
                        <router-link :to="{name: 'home'}" class="nav-link foot p-3">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'postsIndex'}" class="nav-link foot p-3">Posts</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'about'}" class="nav-link foot p-3">About</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link :to="{name: 'contactUs'}" class="nav-link foot p-3">Contact</router-link>
                    </li>
                </ul>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
.img-f{
    object-fit: contain;
}
</style>

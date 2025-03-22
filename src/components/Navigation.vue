<script setup lang="ts">
import { onBeforeUnmount, onMounted, ref } from 'vue';

const showMobileMenu = ()=>{
    let nav= document.getElementById('nav');
    nav?.classList.toggle('mobile_nav')
}


const scrolled = ref(false);

const checkScrolled = ()=>{
    scrolled.value = window.scrollY > 30;
}

onMounted(()=>{
    window.addEventListener('scroll', checkScrolled);
})

onBeforeUnmount(()=>{
    window.addEventListener('scroll', checkScrolled);

})

</script>
<template>
    <!-- Navbar -->
    <nav id="navbar" class="tw-fixed tw-top-0 tw-w-full tw-z-50 tw-transition tw-duration-300 " :class="{'tw-p-0':scrolled, 'md:tw-p-4':!scrolled}">
        <div class="tw-flex tw-justify-between tw-p-3 tw-items-center tw-bg-black
         tw-text-white   tw-top-0 tw-w-full tw-m-0
         " :class="{'tw-fixed tw-top-0 tw-w-full tw-transition tw-duration-300':scrolled, 'md:tw-max-w-5xl md:tw-mx-auto md:tw-rounded tw-transition tw-duration-300':!scrolled}">
            <h1 class="tw-text-white tw-text-xl tw-font-bold tw-font-[Castoro]">Ilem Ilem.</h1>
            <ul class="tw-space-x-6 tw-text-white">
                <div class="tw-hidden md:tw-flex " id="nav">
                    <li class="inline-block tw-ml-4"><a href="#intro" class="hover:tw-text-gray-300 tw-text-xs tw-font-mono">Intro</a></li>
                    <li class="inline-block tw-ml-4"><a href="#about" class="hover:tw-text-gray-300 tw-text-xs tw-font-mono">About</a></li>
                    <li class="inline-block tw-ml-4"><a href="#works" class="hover:tw-text-gray-300 tw-text-xs tw-font-mono">Works</a></li>
                    <li class="inline-block tw-ml-4"><a href="#contact" class="hover:tw-text-gray-300 tw-text-xs tw-font-mono">Contact</a></li>
                </div>
            </ul>

            <button class="md:tw-hidden" @click="showMobileMenu">
                <svg xmlns="http://www.w3.org/2000/svg" height="24px" viewBox="0 -960 960 960" width="24px" fill="#e3e3e3"><path d="M120-240v-80h720v80H120Zm0-200v-80h720v80H120Zm0-200v-80h720v80H120Z"/></svg>
            </button>
        </div>
    </nav>
</template>
<style scoped>
.mobile_nav{
    display:block;
    margin: 0;
    width:100%;
    height: fit-content;
    position: fixed;
    top: 3rem;
    left: 0;
    height: 300px;
    background: rgb(21, 21, 21);
    padding: 0;
    transition: all 700ms linear;
}
#nav{
    transition: all 700ms linear;
}

.mobile_nav li{
    margin:0.5rem;
    display: block;
    padding:5px;
}

.mobile_nav li > a{
    display: block;
}

.mobile_nav li:hover{
    background: rgb(109, 108, 108);
}
</style>
<template>
    <div class="container flex items-center justify-between py-[20px]">
       <HeaderLinks/>
       <HeaderNumber/>
       <HeaderIcons/>
    </div>
</template>
<script>
import HeaderLinks from "./components/HeaderLinks.vue"
import HeaderNumber from "./components/HeaderNumber.vue"
import HeaderIcons from "./components/HeaderIcons.vue"
export default{
components:{
    HeaderLinks,
    HeaderNumber,
    HeaderIcons,
}
}
</script>
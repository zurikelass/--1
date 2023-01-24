<script>
export default{
    props:{
        data:{ type:Array, required:true}
    }
}

</script>
<template>
    <ul>
        <li v-for="item in data" :key="item.id">{{ item.title }}</li>
    </ul>
</template>
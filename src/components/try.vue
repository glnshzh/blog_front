
<template>
<button @click="addCount">123</button>
<P>{{ count }}</P>
</template>

<script>
export default{
    data(){
        return{
            count:0
        }
    },
    methods:{
        addCount(){
            this.count+=1
        }
    }
}

</script>
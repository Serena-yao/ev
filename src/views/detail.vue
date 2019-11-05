<template>
    <div>
        详情页面
        <ul v-for="item in list"></ul>
    </div>
</template>
<script>
export default {
    data() {
        return {
            lsitdata:[]
        }
    },
    created(){
        this.getdetail()
    },
    methods: {
        getdetail(){
            
        }
    },
}
</script>

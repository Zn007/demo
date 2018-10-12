<template>
    <div class="header">
        <div class="header_left">
            左

        </div>
        <div class="header_input">
            welcome 

        </div>
        <div class="header_right">
            右

        </div>
    </div>
    
</template>
<script>
export default {
    name:'HomeHeader'
}
</script>
<style scoped>
.header{
    height: .88rem;
    line-height: .88rem;
    background-color: red;
    display: flex;

}
.header_left{
    float: left;
    width: .60erm;
}
.header_input{
    flex: 1;
    background:white;
    border-radius: 3px;
    height: .64rem;
    margin-top: .12rem;
    line-height: .58rem;


}
.header_right{
    float: right;
}

</style>


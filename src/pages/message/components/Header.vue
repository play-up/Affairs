<template>
    <div class="message-header">
        待办
    </div>
</template>

<script>
export default {
    name: "MessageHeader"
}
</script>

<style scoped>
.message-header{
    position: fixed;
    z-index: 99;
    top: 0;
    left: 0;
    height: 0.67rem;
    width: 100%;
    background: linear-gradient(to right, #040309, #7B7B7B);
    text-align: center;
    color: #FFFBC4;
    font-size: 0.18rem;
    line-height: 0.67rem;
}
</style>
<template>
    <div class="v-btn-inner">
        <button class="v-btn">{{ title_btn }}</button>
        <button class="v-btn-create">{{ title_btn2 }}</button>
    </div>
</template>

<script>

export default {
    props: {
        title_btn: String,
        title_btn2: String
    }
}

</script>

<style scoped>

.v-btn-inner {
    display: flex;
    align-items: center;
}

.v-btn-inner > button {
    margin: 0px 10px;
}

.v-btn {
    border: 3px solid #fff;
    background: #292929;
    color: #fff;
    padding: 10px 30px;
    font-size: 18px;
    border-radius: 12px;
    width: 174px;
}

.v-btn-create {
    background: #FFF965;
    color: #000;
    padding: 10px 30px;
    font-size: 12px;
    border-radius: 12px;
    width: 174px;
}
</style>
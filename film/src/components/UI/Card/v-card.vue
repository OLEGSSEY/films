<template>
    <div class="v-card">
        <img src="../../../assets/card.png" width="260" height="180" alt="">
        <div class="v-data">
            <h3>Название фильма</h3>
            <Nice />
            <p class="v-text">Ghbdiufhsdoifn fjsdiufjsd iufjsd iofunhdsfiupgdfsg<br>
            dfsgidfsogjdsfhgsdfh<br>
            sdhgsfh-fgo0<br>
            hfgdshfsgdh<br>
            fgshsfghjfsg0i79hsjdo8ghjrteo</p>
        </div>
    </div>
</template>

<script>
import Nice from './v-nice.vue'

export default {
    components: {
        Nice
    }
}

</script>

<style>
.v-card {
    background: #232323;
    border-radius: 16px;
    width: 260px;
    color: #fff;
}

.v-data {
    padding: 10px;
}

.v-text {
    font-size: 12px;
    margin: 10px 0px;
}
</style>
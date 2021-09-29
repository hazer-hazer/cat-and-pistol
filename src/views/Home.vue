<template>
    <div class="home">
        <header class="page-header">
            <span class="can-and-pistol">🔫🐈‍⬛</span>
        </header>
    </div>
</template>

<style lang="scss">
.page-header {
    height: 350px;
    width: 100%;
    box-sizing: border-box;
    padding: 50px 100px;

    .can-and-pistol {
        height: 250px;
        margin: 0 auto;
        font-size: 150px;
        line-height: 1;
        vertical-align: middle;
        text-align: center;
    }
}
</style>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
    components: {},
})
export default class Home extends Vue {}
</script>

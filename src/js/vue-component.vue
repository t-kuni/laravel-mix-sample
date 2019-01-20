<template>
    <div class="root">
        {{ body }}
    </div>
</template>

<script>
    export default {
        data() {
            return {
                body: 'I am a Vue Component.'
            }
        }
    }
</script>

<style lang="scss">
    @import '../_variables.scss';

    .root {
        color: $test;
    }
</style>
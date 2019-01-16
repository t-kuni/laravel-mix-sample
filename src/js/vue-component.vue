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

<style type="scss">
    @import '../_variables.scss';

    .root {
        background-color: $test;
    }
</style>
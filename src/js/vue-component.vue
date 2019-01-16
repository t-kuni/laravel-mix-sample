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

<style type="scss" scoped>
    .root {
        background: grey;
    }
</style>
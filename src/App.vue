<template>
    <div>
        <hello-world></hello-world>
    </div>
</template>

<script lang="ts">
import HelloWorld from './components/HelloWorld.vue'
export default {
    components: {
        HelloWorld
    },
    data() {
        return {
            msg: 'hello world'
        }
    },
}
</script>
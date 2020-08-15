<template>
    <div>
        <Switch v-model:value="status"></Switch>
    </div>
</template>

<script lang="ts">
import Switch from "../lib/Switch.vue"
import { ref } from "vue"

export default {
    components: { Switch },
    setup() {
        const status = ref(false)
        return {
            status
        }
    }
}
</script>
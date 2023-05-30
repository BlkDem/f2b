<template>
  <button>{{ text }}</button>
</template>

<script lang="ts">
export default {
    props: {
        text: {
            type: String,
            default: "Some Message"
        }
    }
}
</script>

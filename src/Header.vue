<template>
    <ul>
        <LiElement title="Home" />
        <LiElement title="About" />
        <LiElement title="Contact" />
    </ul>
</template>

<script>
import LiElement from "./LiElement.vue";

export default {
    name: "Header",
    components: {
        LiElement
    }
}
</script>

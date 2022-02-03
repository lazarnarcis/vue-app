<template>
    <li @click="showTitle()">{{title}}</li>
</template>

<script>
    export default {
        name: "LiElement",
        props: {
            title: String
        },
        methods: {
            showTitle() {
                console.log(this.title);
            }
        }
    }
</script>

<template>
    <div id="Content" class="flex w-full h-auto">
        <div id="left" class="w-[70%] bg-orange-200">
            <PostItem></PostItem>
        </div>
        <div id="right" class="w-[30%] bg-green-200">Navigation</div>
    </div>
</template>

<script>
import PostItem from "../bases/PostItem.vue";
export default {
    components: { PostItem },
};
</script>

<style>
</style>
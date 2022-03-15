<template>
    <div id="Post-Item" class="w-full h-[220px] flex">
        <div class="w-[40%] bg-slate-300 p-4 relative" id="img">
            <!-- //? canvas  -->
            <!-- <hr class="w-[80%]" /> -->
            <hr class="w-[60%] rotate absolute text-red-500 bg-red-500" />
        </div>
        <div class="w-[60%] bg-orange-50" id="content">content</div>
    </div>
</template>

<script>
export default {};
</script>

<style scope>
.rotate {
    transform: rotate(90deg);
}
</style>
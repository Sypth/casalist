<template>
    <Link :href="route('listing.index')">Listing</Link>&nbsp;
    <Link :href="route('listing.create')">New Listing</Link>
    <!-- <div>The page with time {{ timer }}</div> -->

    <!-- <div v-if="flashSuccess !== null && typeof flashSuccess !== 'undefined'" class="success">asd</div> -->
    <div v-if="$page.props.flash.success" class="success">
        {{ $page.props.flash.success }}
    </div>

    <slot>Default</slot>
</template>

<script setup>
// import { computed } from "vue";
import { Link } from "@inertiajs/vue3";
// page.props.value.flash.success
// const
// const flashSuccess = $page.props.flash.success;
// import { ref } from "vue";

// const timer = ref(0);
// setInterval(() => timer.value++, 1000);
</script>

<style scoped>
.success {
    background-color: green;
    color: white;
}
</style>

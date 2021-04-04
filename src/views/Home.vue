<template>
    <div class="home">
        <Weather />
    </div>
</template>

<script>
import Weather from "@/components/Weather";

export default {
    name: "Home",
    components: { Weather },
};
</script>

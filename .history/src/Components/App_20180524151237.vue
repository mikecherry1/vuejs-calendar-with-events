<template>
    <div>
        <div v-for="day in days"></div>
    </div>
</template>
<<script>
    export default {
        data() {
            return {
                month: 5,
                year: 2018
            };
        },
        created() {
            console.log(this.$moment);
        }
    }
</script>
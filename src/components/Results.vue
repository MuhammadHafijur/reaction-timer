<template>
    <div>
        <p>Your reaction time {{ score }} ms</p>
    </div>
</template>

<script>
 export default {
    props: ["score"],
    data(){
        return {}

    }
 }
</script>
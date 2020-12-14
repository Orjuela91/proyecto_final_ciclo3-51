<template>
    <div>
        <h2>hola componente</h2>
        {{this.member}}
    </div>
</template>

<script>
    export default {
        name: "TeamCard",
        props: ['member']
    }
</script>


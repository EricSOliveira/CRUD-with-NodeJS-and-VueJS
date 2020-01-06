<template>
    <footer class="footer">
        <span>Desenvolvido por <strong>Eric</strong> em NodeJS e VueJS © 2019-2020</span>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>
    .footer {
        grid-area: footer;
        background-color: #DDD;
        color: #333;

        display: flex;
        align-items: center;
        justify-content: flex-end;
        padding-right: 10px;
    }
</style>
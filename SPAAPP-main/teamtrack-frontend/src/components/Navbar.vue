<template>
    <div>
        <a href="/">Koduleht</a>
        <a href="/coachEvents">Olen Treener</a>
        <a href="/athleteEvents">Olen Sportlane</a>
        <a href="/newevent">Lisa sündmus</a>
        <a href="/eventPeople">Isikute Sündmused</a>
        <a href="/peopleStore">Inimesed</a>




    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
    a {
        list-style-type: none;
        margin: 0 auto; /* Keskendab nav-bari lehe keskele */
        padding: 0;
        width: 319px;
        background-color: black;
        padding: 20px 0; /* Lisa ruumi ülal ja all */
    }

    a {
        float: left;
        display: block;
        color: white;
        text-align: center;
        padding: 14px 16px;
        text-decoration: none;
        border: 2px solid white;
        border-radius: 5px;
        transition: transform 0.3s; /* Üleminekumuudatus, et suurendada nuppu suurust sujuvalt */
    }

        a:hover {
            transform: scale(1.04); /* Suurendab nuppu 5% võrra, kui kasutaja selle peale hiirega liigub */
        }
</style>



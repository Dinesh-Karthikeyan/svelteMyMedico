<script>
    import Name from "./Name.svelte";
</script>

<main>
    <div class="companyName">
        <span class="my">My</span> <span class="medico">Medico</span>
    </div>
    <Name name="Anoop" />
    <Name name="Chetan" />
    <Name name="Dinesh" />
    <Name name="Aryan" />
</main>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400&display=swap");

    main {
        background-color: black;
        font-family: "Montserrat", sans-serif;
        display: flex;
        align-items: center;
        justify-content: space-around;
        height: 400px;
        color: white;
    }
    .my {
        color: rgb(214, 175, 238);
    }
    .medico {
        color:  #858aff;
    }
    .companyName {
        font-size: 2em;
    }
</style>

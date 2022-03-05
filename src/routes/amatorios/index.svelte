<script>
    function straight() {
        window.open("/amatorios/straight", "_self");
    }
    function gay() {
        window.open("/amatorios/gay", "_self");
    }
    function lesbian() {
        window.open("/amatorios/lesbian", "_self");
    }
    function biSexual() {
        window.open("/amatorios/bi-sexual", "_self");
    }
</script>
<h1>Amatorios</h1>
<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Vitae dolore dolor velit rem nostrum distinctio unde laudantium cupiditate tempora repudiandae inventore temporibus ad necessitatibus deserunt iusto magnam a, reiciendis voluptas!</p>
<div class="row">
     <button on:click={straight} class="column">
        <h5>Straight</h5>
        <img src="../../../static/images/straight.png" alt="">
    </button>
     <button on:click={gay} class="column">
        <h5>Gay</h5>
        <img src="../../../static/images/gay.png" alt="">
    </button>
     <button on:click={lesbian} class="column">
        <h5>Lesbian</h5>
        <img src="../../../static/images/lesbian.png" alt="">
    </button>
     <button on:click={biSexual} class="column">
        <h5>Bi-Sexual</h5>
        <img src="../../../static/images/bi-sexual.png" alt="">
    </button>
</div>
<style>
    .row, .column {
        display: flex;
        flex: 1;
        justify-content: center;
        align-items: center;
    }
    .column {
        flex-direction: column;
        row-gap: 20px;
        padding: 10px;
        background-color: hsla(0, 100%, 100%, 1);
        margin: 10px;
        color: hsla(0, 0%, 0%, 1);
        border-radius: 50px;
    }
    .column:hover {
        background-color: hsla(15, 100%, 57%, 1);
    }
    img {
        width: 80%;
    }
</style>
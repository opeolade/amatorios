<script>
    function straight() {
        window.open("https://forms.gle/N1aBdbpniEHU5YDo9", "_self");
    }
</script>
<h1 class="about">What is amatorios all about?</h1>
<p>Amatorios is an exclusive event basically designed for those with wild fantasies, an event rated 21<sup>+</sup>. What to expect:<br>*Mannerless girls *Unclad girls *Girls that matches your fantasy, just give us a preference of what you want *Food * 21<sup>+</sup> rated games *Real life sex games.</p>
<div class="row">
     <button on:click={straight} class="column">
        <h5>Girls</h5>
        <img src="./images/girls.png" alt="">
    </button>
     <button on:click={straight} class="column">
        <h5>Food</h5>
        <img src="./images/food.png" alt="">
    </button>
     <button on:click={straight} class="column">
        <h5>Games</h5>
        <img src="./images/erotic.png" alt="">
    </button>
     <button on:click={straight} class="column">
        <h5>Fantasy Room</h5>
        <img src="./images/fantasy.png" alt="">
    </button>
</div>
<style>
    p {
        text-align: center !important;
    }
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
        filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(360deg) brightness(0%) contrast(100%);
    }
</style>
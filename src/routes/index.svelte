<script>
    function accept() {
        window.open("https://paystack.com/pay/amatorios", "_self");
    }
    
    function reject() {
        window.open("/reject", "_self");
    }
</script>
<div class="row">
    <div class="column">
        <div class="image">
            <img src="/static/images/amatorios.png" alt="">
        </div>
        <div class="card">
            <p>Ever dreamt of attending a crazy house party with no manners, cozy rules in a secured and coded environment? Amatorios is here to make your fantasy come true. On the 25<sup>th</sup> of March from 19:00pm, all sort of manners will be set loose.</p>
            <div class="button-holder">
                <button on:click={accept}>Accept</button>
                <button on:click={reject} class="reject">Reject</button>
            </div>
        </div>
    </div>
</div>

<style>
    .row, .column, .image, .card, .button-holder, button {
        display: flex;
        flex: 1;
        justify-content: center;
        align-items: center;
    }
    
    .card {
        flex-direction: column;
        row-gap: 50px;
    }
    
    .card p {
        text-align: justify;
    }
    
    .button-holder button {
        border-radius: 125px;
        padding: 10px 50px;
        font-size: 3vw;
    }
    
    .button-holder button:hover {
        background-color: hsla(0, 0%, 0%, 1);
        color: hsla(0, 100%, 100%, 1);
        border-style: solid;
        border-width: 2px;
        border-color: hsla(0, 100%, 100%, 1);
    }
    
    .reject {
        background-color: hsla(15, 100%, 57%, 1);
    }
    
    .reject:hover {
        background-color: hsla(0, 0%, 0%, 1) !important;
        color: hsla(15, 100%, 57%, 1) !important;
        border-color: hsla(15, 100%, 57%, 1) !important;
    }
    
    .card .button-holder {
        column-gap: 50px;
    }
    
    img {
        filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(360deg) brightness(100%) contrast(100%);
    }
</style>
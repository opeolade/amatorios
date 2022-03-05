<header>
    <a class="brand" href="/">
        <h1 class="name">
            <img src="./images/favicon.svg" alt="">
            Amatorios
        </h1>
        <h1 class="rated">21+</h1>
    </a>
</header>
<style>
    header, .brand {
        display: flex;
        align-items: center;
    }
    
    header {
        padding: 10px 10vw;
        height: 18vh;
    }
    
    .brand {
        flex: 1;
        column-gap: 10px;
        justify-content: center;
    }
    
    .brand h1 {
        background-color: hsla(15, 100%, 57%, 1);
        padding: 5px 10px;
        color: hsla(0, 0%, 0%, 1);
    }
    
    .brand .rated {
        background-color: hsla(0, 100%, 100%, 1);
        margin-left: -10px;
    }
    
    .rated:hover {
        color: hsla(15, 100%, 57%, 1) !important;
    }
    
    .rated {
        border-top-right-radius: 125px;
        border-bottom-right-radius: 125px;
    }
    
    .name {
        border-top-left-radius: 125px;
        border-bottom-left-radius: 125px;
    }
    
    .brand h1:hover {
        color: hsla(0, 0%, 100%, 1);
    }
    
    .brand img {
        height: 5vw;
    }
    
    .brand img:hover {
        filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(360deg) brightness(100%) contrast(100%);
    }
</style>
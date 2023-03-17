<script>
    // const src = '../assets/logo.jpg'
    // const src = "D:\\coding\\web\\svelte\\two\\src\\assets\\logo.jpg"
    const src = "assets/logo.jpg";
</script>

<main>
    <img {src} alt="Company logo">
    <nav>
        <div>Home</div>
        <div>Blog</div>
        <div>Q/A</div>
        <div>Contact</div>
    </nav>
    <div class="hide">
        <!-- <img src="../assets/logo.jpg" alt="Company logo"> -->
        <div class="log">Sign UP / Sign IN</div>
    </div>
</main>

<style>
    /* @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400&family=Poppins:ital,wght@0,400;0,500;1,400&display=swap'); */
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400&display=swap');

    main {
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-family: 'Montserrat', sans-serif;
    }
    
    div {
        display: inline;
    }
    
    nav div{
        font-size: 1.5em;
        margin:20px;
    }
    .hide {
        border-radius: 50%;
        border-color: rgb(214, 175, 238);
        border-width: 3px;
    }
    img {
        width:15em;
    }
</style>
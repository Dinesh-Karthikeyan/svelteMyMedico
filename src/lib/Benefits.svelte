<script>
    const locate = "/assets/location.png";
    const doctor = "/assets/doctor.png";
    const incognito = "/assets/incognito.png";
</script>

<main>
    <h1>How do patients Benefit?</h1>
    <div class="container">
        <div class="dabba">
            <div><img src={doctor} alt="doctor-icon" /></div>
            <div>
                Fast, accurate and early diognosis guaranteed
                by doctors made from your symptoms 
            </div>
        </div>
        <div class="dabba">
            <div><img src={locate} alt="locate icon" /></div>
            <div>
                Anonymously ask your questions to a communtiy of certified doctors which you may feel
                uncomfortable to share with your friends and family
            </div>
        </div>
        <div class="dabba">
            <div><img src={incognito} alt="incognito icon" /></div>
            <div>Easily locate speacilist clinics near your location</div>
        </div>
    </div>
</main>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400&display=swap");

    main {
        font-family: 'Montserrat', sans-serif;
    }
    .container {
        display: flex;
        justify-content: space-around;
        margin-top: 50px;
        font-size: 1.1em;
    }
    .container div {
        padding: 50px;
    }
    .dabba {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: flex-start;
        text-align: center;
        width: 30%;
    }
    img {
        width: 80px;
    }
</style>

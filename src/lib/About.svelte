<script>
    const src = "/assets/mobilehome.png";
</script>

<main>
    <div>
        <h1><span class="my">My</span> <span class="medico">Medico</span></h1>
        <h2>Because we care</h2>
        <div class="content">
            <div>
                One stop solution to speed up your medical consultancy and
                appointments
            </div>
            <div>
                Questionnaire prepared by doctors to reliably tell what your
                symptoms mean
            </div>
            <div>
                Ask your doubts and queries in the doctor community to get
                reliable suggestions and answers
            </div>
            <div>
                In emergency, ambulance and hospital admission are made easy by
                making your medical history readily available to the doctors
            </div>
            <div>
                Relevant blogs posted by doctors will be recommended to you
                according to your medical history
            </div>
        </div>
    </div>
    <div class="imgContainer">
        <img {src} alt="" />
    </div>
</main>

<style>
    @import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200;400&display=swap");

    main {
        display: flex;
        justify-content: space-around;
        font-family: 'Montserrat', sans-serif;
        padding-left:50px;
    }
    main div {
        width: 50%;
    }
    main div div {
        line-height: 2em;
        width: initial;
    }
    img {
        max-width: 100%;
        height: 500px;
        border-radius: 0.7rem;
        filter: drop-shadow(0.5rem 0.5rem 0.5rem rgba(0, 0, 0, 0.8));
    }
    .imgContainer {
        text-align: center;
    }
    .my {
        color: rgb(214, 175, 238);
    }
    .medico {
        color: #858aff;
    }
    .content {
        margin-top: 50px;
        text-align: justify;
    }
    h1 {
        font-size: 2.5rem;
    }
    h2 {
        font-size: 1.5em;
    }
</style>

<template>
    <div class="main-container">
        <div class="container-one">
            <div class="profile">
                <img src="../assets/profilepic.jpg" alt="">
                <h3>Batuhan Okur</h3>
                <p>Software Developer</p>
            </div>
            <div class="social-links">
                <div class="link">
                    <a href="">
                        <img src="../assets/github.png" alt="">
                        <h2>GitHub</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/linkedin.png" alt="">
                        <h2>LinkedIn</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="">
                        <img src="../assets/hackerrank.png" alt="">
                        <h2>Hackerrank</h2>
                    </a>
                </div>                
            </div>
        </div>
        <div class="container-two">
            <div class="about-me">
                <h1>About Me</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Veniam eaque accusantium rerum deserunt adipisci praesentium sunt fugit dolores molestiae laboriosam. 
                    Veritatis corrupti accusantium assumenda vero, quas sunt commodi porro dolor.</p>
            </div>
            <div class="technology-section">
                <h1>Technologies</h1>
                <p>.NET, Java, Spring Boot, Vue.Js, C#, Python, HTML, CSS, SQL, PHP-Laravel, C </p>
            </div>
            <div class="button-container">
                <div class="projects-button">
                    <a href="">My Projects</a>
                </div>
                <div class="projects-button">
                    <a href="">My Resume</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{

}
</script>

<style scoped>
    img{
        height: 20px;
    }
    
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #cecece;
        border-radius: 25px;
        width: 70%;
        margin-left: 15%;
    }

    .container-one{
        background-color: #ffb0b0;
        padding: 2.5%;
        border-radius: 25px;
        width: 30%;
    }

    .profile img{
        height: 10rem;
        border-radius: 50%;
    }

    .link a{
        text-decoration: none;
        color: #2c3e50;
        font-size: 12px;
    }
    .link img{
        height: 2rem;
    }

    .container-two{
        background-color: #cdc0fc;
        width: 70%;
        margin: 2.5%;
    }

    .about-me{
        text-align: left;
    }

    .technologies-section p{
        text-align: center;
    }

    .button-container{
        margin-top: 5%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .projects-button{
        background-color: #7c58ff;
        margin: 5px;
        padding: 5px;
        border-radius: 15px;
    }

    .projects-button a{
        text-decoration: none;
        color: white;
        margin-bottom: 10px;
    }
</style>
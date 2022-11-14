<template>
<div class="wrapper">
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
                <p >Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                    Veniam eaque accusantium rerum deserunt adipisci praesentium sunt fugit dolores molestiae laboriosam. 
                    Veritatis corrupti accusantium assumenda vero, quas sunt commodi porro dolor.</p>
            </div>
            <div class="technology-section">
                <h1>Technologies</h1>
                <p>.NET, Java, Spring Boot, Vue.Js, C#, Python, HTML, CSS, SQL, PHP-Laravel, C </p>
            </div>
            <div class="button-container">
                <div class="projects-button">
                    <a href="#project-card">My Projects</a>
                </div>
                <div class="projects-button">
                    <a href="">My Resume</a>
                </div>
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

    .wrapper{
        display: flex;
        justify-content: center;
    }
    
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #A0d4ff;
        border-radius: 25px;
        width: 60%;
    }

    .container-one{
        background-color: #1292ee;
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
        width: 70%;
        margin: 2.5%;
    }

    .about-me{
        text-align: left;
        margin-top: 10%;
        color: aliceblue;
    }

    .technology-section{
        margin-top: 10%;
        text-align: left;
    }

    .button-container{
        margin-top: 50%;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .projects-button{
        background-color: #005ca4;
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
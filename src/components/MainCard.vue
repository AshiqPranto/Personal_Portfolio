<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/PrantoProfilePicturePunjabi.JPG" alt="Profile Picture">
                    <h3>Ashiq Uddin Pranto</h3>
                    <p>Full stack Developer with Asp.net and Vue | Cloud Computing | Agile Practitionar | Former Competitive Programmer <br><br> Bangladesh <br> Gmail: ashiqpranto@gmail.com</p>
                </div>
                <div class="social-links">
                    <div class="link">
                        <a href="https://github.com/AshiqPranto" target="_blank">
                            <img src="../assets/github-logo.png" alt="Github logo">
                            <h2>Github</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.linkedin.com/in/ashiqpranto/" target="_blank">
                            <img src="../assets/linkedin.png" alt="Linkedin logo">
                            <h2>Linkedin</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/ashiquddin.pranto.3" target="_blank">
                            <img src="../assets/facebook.png" alt="Facebook logo">
                            <h2>Facebook</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about-me">
                    <h1>About Me</h1>
                    <p>Passionate Full Stack Web Developer with a strong background in competitive programming, 
                        specializing in ASP.NET and Vue.js. I have spent three years improving my coding skills
                        in various online judges, and I bring that same dedication to crafting innovative and 
                        efficient web solutions. I have also use cloud computing, particularly in AWS and 
                        Microsoft Azure and I have hands-on experience with serverless development. I thrive in 
                        dynamic environments and enjoy collaborating with cross-functional teams, leveraging Agile 
                        Methodology and CI/CD practices to deliver high-quality results on time and within budget.
                        <br><br>
                        As a tech enthusiast, I constantly strive to stay updated with the latest advancements in the tech industry, and I take pride in my ability to quickly adapt and implement cutting-edge technologies in my projects.
                        I never fear to learn new things.</p>
                </div>
                <div class="button-container">
                    <div class="projects-button">
                        <a href="">My Projects</a>
                    </div>
                    <div class="resume-button">
                        <a href="">My resume</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
    .wrapper{
        display: flex;
        justify-content: center;
    }
    .main-container{
        display: flex;
        flex-direction: row;
        background-color: #cecece;
        border-radius: 25px;
        width: 70%;
    }
    img{
        height: 20px;
    }
    .container-one{
        background-color: #ffb0b0;
        padding: 2.5%;
        width: 30%;
        border-radius: 25px;
    }
    .profile img{
        height: 5rem;
        border-radius: 50%;
    }
    .container-two{
        background-color: #cdc0fc;
        width: 70%;
        margin: 2.5%;
    }
    .link a{
        text-decoration: none;
        color: #000;
        font-size: 12px;
    }
    .link img{
        height: 2rem;
    }
    .about-me{
        text-align: left;
        padding: 2.5%;
    }
    .projects-button{
        background-color: #7c58ff;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;
    }
    .resume-button{
        background-color: #7c58ff;
        border-radius: 15px;
        padding: 5px;
        margin: 5px;
    }
    .button-container a{
        text-decoration: none;
        color: #fff;
    }
    .button-container{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin-top: 5%;
    }
    @media only screen and (max-width: 950px) {
        .main-container{
            width: 95%;
        }
    }
    </style>
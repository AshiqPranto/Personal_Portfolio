<template>
    <div class="main-container">
        <div class="project-card" v-for="(items,index) in jsonData.ProjectsArray" :key="items.id">
            <h2>{{ items.Title }}</h2>
            <img :src="items.Image" alt="">
            <p>{{ items.About }}</p>
            <div class="links">
                <a :href="items.GithubLink" target="_blank"><img src="../assets/github-logo.png" alt=""></a>
                <a :href="items.ExternalLink" target="_blank"><img src="../assets/external-link.png" alt=""></a>
            </div>
        </div>  
    </div>
</template>

<script setup lang="ts">
import jsonData from './projects.json';
</script>

<style scoped>
    .project-card img{
        height: 12rem;
    }
    .links{
        display: flex;
        align-items: center;
        justify-content: flex-end;
        flex-direction: row;
    }
    .links img{
        height: 1.5rem;
        margin: 5px;
    }
    .main-container{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
    }
    .project-card{
        margin: 2.5%;
        flex-wrap: 0 0 40%;
        box-shadow: rgba(0, 0, 0, 0.25) 0px 3px 8px;
        border-radius: 25px;
        background-color: #fff;
        padding: 20px;
    }
</style>
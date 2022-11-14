<template>
    <div class="project-div">
        <div v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items" class="project-card">
            <div class="card-content">
                <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
                <p><b>About Project: </b> {{ projectData.ProjectsArray[index].About }}</p>
                <p><b>Technologies: </b> {{ projectData.ProjectsArray[index].Technologies }}</p>
                <a :href="projectData.ProjectsArray[index].Link"><img src="../assets/link.png"></a>
            </div>
        </div>
    </div>

</template>
  
<script>
import jsonData from "/projects.json"
export default {
    data() {
        return {
            projectData: jsonData,
        }
    }
}


</script>
  
<style>
.project-card {

    margin-top: 4%;
    padding: 10px;
    width: 40%;
    background-color: #fff;
    border-radius: 25px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;

}

.project-div {
    flex-wrap: wrap;
    align-items: center;
    
    flex-direction: row;
    display: flex;
    justify-content: space-between;
    padding-left:20%;
    padding-right:20%;
}

.card-content {
    margin: 5%;
}

.card-content a {
    text-decoration: none;
}

.card-content a img {
    width: 2rem;
    float: right;
}
</style>
  
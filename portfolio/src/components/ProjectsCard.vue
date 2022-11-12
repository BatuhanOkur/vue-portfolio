<template>  
    <div v-for="(items,index) in projectData.ProjectsArray" v-bind:key="items">
        <div class="project-card">
            <div class="card-content">
                <h2>{{projectData.ProjectsArray[index].Title}}</h2>
                <p><b>About Project: </b> {{projectData.ProjectsArray[index].About}}</p>
                <p><b>Technologies: </b> {{projectData.ProjectsArray[index].Technologies}}</p>
                <a href="">Click here to go to "{{projectData.ProjectsArray[index].Title}}" repository. </a>
            </div>
        </div>
    </div>
   
</template>
  
<script>
    import jsonData from "/projects.json"
    export default{
        data(){
            return{
                projectData: jsonData,
            }
        }
    }


</script>
  
<style>    


    .project-card{
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
        flex-wrap: 0 0 40%;
        background-color: white;
        margin-left: 30%;
        margin-right: 30%;
        margin-top: 3rem;
        padding: 1%;
        border-radius: 25px;
    }

    .card-content{
        margin: 5%;
    }
</style>
  
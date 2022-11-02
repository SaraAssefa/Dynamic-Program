
<template>
    <h5>this is sara's {{whatever}} and {{buildingName}}</h5>
</template>

<script>
export default {
    name: 'Sara',
    props:{
        whatever: String
    },
    methods:{},
    components:{},
    data(){
        return {
            buildingName:"my bulding"
        }
    },
    //lifecycle methods 
    setup(){
        //load buiding name from db
        let loadedName = "this is name";
        this.buildingName = loadedName;
    }
}
</script>
<style></style>
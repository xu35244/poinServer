<template>
  <div id="headerBook">
     <div id="headerTitle">
         <span>
              {{message}}
         </span>
     </div>
  </div>
</template>

<script>
export default {
    name:"headerBook",
    data(){
        return {
            message:"江西软件大学-新型图书管理系统"
        }
    }
}
</script>

<style>
#headerBook{
    /* background-color: red; */
}
#headerTitle{
    /* background-color: blue; */
    width: 400px;
    height: 60px;
    color:white;
    font-size: 20px;
    font-weight: bolder;
    line-height: 60px;
}
</style>
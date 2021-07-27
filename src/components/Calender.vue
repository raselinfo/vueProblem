<template>
    <div>
     <h1>Vue Calender</h1>
     <section class="days">
         <p v-for="day in days" :key="day">{{day}}</p>
     </section>
     <section class="date">
         <p v-for="num in 30" :key="num">{{num}}</p>
        
     </section>
    </div>
</template>

<script>

export default {
    data(){
        return{
            days:['Sun','Mon','Tue',"Wed","Thu","Fri","Sat"]
        }
    }
}
</script>

<style>
.days{
    display:flex;
}
.days >p{
    text-align:center;
  width:14.28%;
    height:10px;
}
.date{
    display: flex;
    flex-wrap: wrap;
}
.date p{
  width:14.28%;
    height:10px;
    text-align:center;
}
</style>
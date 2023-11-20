<template>
    <h1 class="text-5xl">Home component {{"chandan".length}}</h1>
    <div class="text-3xl">Email:{{email}}</div>
    <div class="text-4xl">Mobile:{{mobile}}</div>
    <!-- value add in interpolation -->
    <div class="text-4xl">Mobile:{{mobile!=999}}</div>
    <div class="text-4xl">Name:{{getName()}}</div>
    <div class="text-4xl">Name:{{getId("Chandan Kumar Das")}}</div>
</template>

<script>
export default{
    name:'Home',
    data()
    {
        return{
            email:"dchandankumar07@gmail.com",
            mobile:"7991052216",
            getName:function()
            {
                return  "Chandan Kumar";  
            },
            getId:function(a){
                return a;
            }
        }
    }
}
</script>

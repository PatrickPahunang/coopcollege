<script setup>


</script>

<style>
.buttonview:hover {
    border: solid 2px rgb(0, 0, 43);
    background-color: white;
    color:rgb(0, 0, 43);
    transition: .5s;
}
.buttonedit:hover {
    border: solid 2px rgb(86, 154, 255);
    background-color: white;
    color:rgb(86, 154, 255);
    transition: .5s;
}

.buttondelete:hover {
    border: solid 2px red;
    background-color: white;
    color:red;
    transition: .5s;
}


</style>

<template>
      <div class="h-24 xl:h-32 max-w-7xl bg-white xl:px-8 xl:py-4 rounded-lg grid grid-cols-8 gap-4 max-h-30 xl:max-h-40 text-sm xl:text-md pr-4">
            <div class=" flex justify-center text-center items-center">
                1
            </div>
            <div class=" flex justify-center text-center items-center"> 
                <img src="../../asset/sample.jpg" class=" xl:h-24 xl:w-32 h-16 w-20">
            </div>
            <div class=" flex justify-center text-center items-center col-span-3">
                Lorem Ipsum dolor Lorem Ipsum dolor 
            </div>
          
            <div class=" flex justify-center text-center items-center">
                        <button class="py-2 px-8 bg-slate-900 xl:rounded-lg text-white text-xs xl:text-md buttonview border-2 border-slate-900">View</button>
            </div>
            <div class=" flex justify-center text-center items-center">
                        <button class="py-2 px-8 bg-blue-400 xl:rounded-lg text-white text-xs xl:text-md buttonedit border-2 border-blue-400">Edit</button>
            </div>
            <div class=" flex justify-center text-center items-center ">
                        <button class="py-2 px-8 bg-red-500 xl:rounded-lg text-white text-xs xl:text-md buttondelete border-2 border-red-500">Delete</button>
            </div>
        </div>
</template>
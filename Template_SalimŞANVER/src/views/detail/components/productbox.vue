<template>
    <div class="card">
        <div class="w-full  h-full  ">
            <div class="w-48 h-96 bg-gray-200     pt-12 rounded-md  ">
                <img class="px-6 h-28 " :src="img" alt=""><!--@/assets/img/detailimg1.png     Vegetable    Fresh Bread and Pastry Flour 200 g     (34)    $12.68  $14.69 Add-->
                <div class=" mt-4 px-2">
                    <p class="">{{ title }}</p>
                    <p class="w-36  text-lg">{{ title1 }}</p>
                    <div class="text-xs flex float-left  mt-2 text-yellow-500 w-full">
                        <i class="fa-sharp fa-solid fa-star "></i>
                        <i class="fa-sharp fa-solid fa-star "></i>
                        <i class="fa-sharp fa-solid fa-star"></i>
                        <i class="fa-sharp fa-solid fa-star"></i>
                        <i class="fa-sharp fa-regular fa-star "></i>
                        <p class="flex float-left  text-cyan-700">{{ title2 }}</p>
                    </div>
                    <p class="" >1 Kg</p>
                    <p class="text-green-700  font-bold">{{ title3 }}<span class="line-through text-black font-normal">{{ title4 }}</span></p>
                        <div class="w-40 ml-2 mt-2 h-10 rounded-3xl bg-gray-100">
                            <div class="bg-slate-500  rounded-2xl w-8 h-8  float-right mt-1 mr-1 max-sm:mr-4">
                                <i class="fa-solid fa-plus flex justify-center  pt-2 text-green-700"></i>
                            </div>
                            <p class="px-14 pt-2">{{ title5 }}</p>
                            
                        </div>

                </div>

            </div>

        </div>
    </div>
</template>
<script>

export default {
    name: 'productboxComp',
     
        props:["img","title","title1","title2","title3","title4","title5"]
    
}
</script>
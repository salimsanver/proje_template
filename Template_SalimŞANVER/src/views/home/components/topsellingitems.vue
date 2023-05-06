<template>
    <div>
        <div class=" px-28 flex h-16 mt-12 max-sm:-ml-24 max-sm:mt-8">
            <p class=" text-2xl font-bold max-sm:w-[96] max-sm:text-xl">Top Selling Items</p>
        </div>
     

<carousel class="px-28 max-sm:px-4 " :autoplay="true" :nav="false" :margin="10" :loop="true" :responsive="{0:{items:2,nav:false,dots:false},600:{items:5,nav:false,dots:false}}">

<card img="bg-[url('@/assets/img/topsellingitems1.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems2.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems3.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems4.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems6.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
    <card img="bg-[url('@/assets/img/topsellingitems4.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
<card img="bg-[url('@/assets/img/topsellingitems6.jpg')]" title="Brown Khadi Jacket" newPrince="26.69"
    prince="28.56" />
</carousel>




        <div class=" flex  justify-between items-center px-28 bg-cover bg-center gap-6 mt-8    max-sm:-mt-20 max-sm:px-4">
            <div class="relative max-sm:flex-none   max-sm:-mt-36  max-sm:items-center  max-sm:w-full max-sm:h-full ">
                <img class="rounded-xl h-60   max-sm:w-full max-sm:max-sm:object-cover  " src="@/assets/img/searchimage.jpg" alt="">
                <div class="absolute inset-0 hover:bg-gray-200 opacity-50 rounded-xl hover:transition-all duration-500">
                </div>
                <p class="absolute -mt-56 px-8 font-bold text-3xl italic text-cyan-700 max-sm:text-2xl max-sm:pt-2">Get Ready To</p>
                <p class="absolute -mt-44 px-8  text-3xl italic max-sm:pt-0 max-sm:text-xl">TAKE ON THE DAY!</p>
                <p class="absolute -mt-32 px-8   italic w-[450px]  max-sm:w-full max-sm:text-sm">In publishing and graphic design, Lorem ipsum is a
                    placeholder text commonly used to demonstrate.</p>
                <div class="absolute -mt-14 px-8 ">
                    <button
                        class="rounded-lg px-4 py-2 bg-red-500 text-gray-100 hover:bg-red-500 duration-300 text-sm max-sm:px-2 ">Show
                        Now <i class="fa-solid fa-arrow-right px-1 py-1  font-bold"></i></button>
                </div>
            </div>
          <div class="relative max-sm:flex-none  max-sm:mt-96 max-sm:right-[365px]  max-sm:w-full ">
                <img class="rounded-xl h-60 block w-full max-sm:w-full " src="@/assets/img/searchimage1.jpg" alt="">
                <div class="absolute inset-0 hover:bg-gray-200 opacity-50 rounded-xl hover:transition-all duration-500">
                </div>
                <p class="absolute -mt-44 px-8 font-bold text-3xl italic text-red-500">20% OFF</p>
                <p class="absolute -mt-36 px-8  text-3xl italic text-cyan-700">SUMMRY</p>
                <p class="absolute -mt-28 px-8  text-3xl italic">Product</p>
            </div> 
        </div>
    </div>
</template>

<script>
import card from '@/components/card.vue'
import carousel from 'vue-owl-carousel'

export default {
    name: 'topsellingitemsComp',
    components: {
        card,
        carousel
    },
}
</script>

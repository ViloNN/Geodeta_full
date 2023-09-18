<script setup>
import { initFlowbite } from 'flowbite'

onMounted(() => {
    initFlowbite();
})
</script>


<template>

<nav class="border-gray-200 bg-gray-50 dark:bg-white dark:border-gray-700">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
    <a href="#" class="flex items-center">
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-black">Geodeta</span>
    </a>
    <button data-collapse-toggle="navbar-solid-bg" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-white dark:focus:ring-white" aria-controls="navbar-solid-bg" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
    </button>
    <div class="hidden w-full md:block md:w-auto" id="navbar-solid-bg">
      <ul class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-transparent dark:bg-white md:dark:bg-transparent dark:border-white">
        <li>
          <a href="#aboutus" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-black md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent" aria-current="page">O nas</a>
        </li>
        <li>
          <a href="#offer" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-black md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Oferta</a>
        </li>
        <li>
          <a href="#adres" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-black md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Adres</a>
        </li>
        <li>
          <a href="#contact" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-black md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Kontakt</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<section class="bg-white dark:bg-gray-100">
    <div class="gap-16 items-center py-8 px-4 mx-auto max-w-screen-xl lg:grid lg:grid-cols-2 lg:py-16 lg:px-6">
        <div class="font-light text-gray-500 sm:text-lg dark:text-gray-900">
            <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-grey">GEODETA UPRAWNIONY <br> inż. Eryk Brodowski</h2>
            <p class="mb-4">Geodeta uprawniony Eryk Brodowski posiada wieloletnie doświadczenie w branży geodezyjnej, każdego klienta obsługuje indywidualnie i rzetelnie.</p>
        </div>
        <div class="grid grid-cols-2 gap-4 mt-8">
            <img class="w-full rounded-lg" src="./zdj1.png" alt="office content 1">
            <img class="mt-4 w-full lg:mt-10 rounded-lg" src="./zdj2.png" alt="office content 2">
        </div>
    </div>
</section>

<section class="bg-white dark:bg-white">
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center sm:py-16 lg:px-6">
    <div id="aboutus"></div>
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-black">O nas</h2>
      <p class="text-gray-500 sm:text-xl dark:text-black">Świadczymy profesjonalne usługi geodezyjne od 1993 r. Działamy w powiatach legionowskim i pułtuskim. <br> Wieloletnie doświadczenie przekłada się na wysoką jakość usług.</p> <br> <br> <br>

      <div class="space-y-8 md:grid md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 md:gap-2 xl:gap-2 md:space-y-0">
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-2 w-10 h-center rounded bg-primary-100 lg:h-center lg:w-center dark:bg-primary-900">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Świadczymy usługi dla firm, instytucji i klientów prywatnych</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-2 w-10 h-center rounded bg-primary-100 lg:h-center lg:w-center dark:bg-primary-900">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Zapewniamy doradztwo, miłą i fachową obsługę oraz korzystne ceny</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-2 w-10 h-center rounded bg-primary-100 lg:h-center lg:w-center dark:bg-primary-900"> 
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Jesteśmy dyspozycyjni i możemy dostosować się do klienta</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-2 w-10 h-center rounded bg-primary-100 lg:h-center lg:w-center dark:bg-primary-900">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Podpowiemy w wyborze lokalnych wykonawców</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
      </div>
      <div class="mt-8 lg:mt-12 space-y-8 md:grid md:grid-cols-2 lg:grid-cols-3 md:gap-12 md:space-y-0">
      </div>
</div>
</section>

<section class="bg-gray-50 dark:bg-gray-100">
  <div class="py-8 px-4 mx-auto max-w-screen-xl sm:py-16 lg:px-6">
      <div class="mx-auto max-w-screen-md text-center mb-8 lg:mb-16">
        <div id="offer"></div>
          <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-black dark:text-black">Oferta</h2>
          <p class="font-light text-gray-500 dark:text-gray-900 sm:text-xl">Świadczymy profesjonalne oraz kompleksowe usługi w zakresie</p>
      </div> 

      <div class="space-y-8 md:grid md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-5 md:gap-2 xl:gap-2 md:space-y-0">
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                  <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./inw.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Wszystkich map potrzebnych przy inwestycjach</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./komp.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Podziału działek</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./plan.png">                 
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Podpowiemy przy zakupie i sprzedaży nieruchomości</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./prz.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Projektowaniu przyłączy i budynków</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-orange-600">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./stojak.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Obsługi inwestycji</h3>
              <p class="font-light text-gray-500 dark:text-gray-400"></p>
          </div>

        </div>
  </div>
<!-- </div>
      </div> -->
<!-- </div> -->
</section>

<section class="bg-white dark:bg-white">
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center sm:py-16 lg:px-6">
    <div id="adres"></div> 
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 text-black">Adres</h2>
      <p class="text-black sm:text-xl text-black">
        Rynek 17 lokal 4 <br>
        05-140 Serock <br>
        <a href="https://goo.gl/maps/uKfGGE2mrXhKQsHq7">WYZNACZ TRASĘ</a>
      </p>
  </div>

</section>

<section class="bg-white dark:bg-gray-100">
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-6">
      <div class="grid mb-8 lg:mb-12 lg:grid-cols-2">
          <figure class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-6 lg:border-r dark:bg-orange-600 dark:border-white">
              <blockquote class="mx-auto mb-4 max-w-2xl text-gray-500 dark:text-white">
                <div id="contact"></div>
                  <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Konakt</h3>
                  <p class="my-4">
                    Geodeta Eryk Brodowski <br>
                    NIP: 5681544978 <br>
                    Adres e-mail: geodezja.serock@wp.pl, geodeta.eryk@gmail.com <br>
                    Tel. +48 535 855 260
                    </p>
              </blockquote>   
          </figure>
          <figure class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-6 dark:bg-orange-600 dark:border-white-700">
              <blockquote class="mx-auto mb-4 max-w-2xl text-gray-500 dark:text-white">
                  <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Godziny otwarcia</h3>
                  <p class="my-4">
                    poniedziałek - piątek: 7:00- 16:00 <br>
                    sobota - po wcześniejszym uzgodnieniu telefonicznym <br>
                    niedziela - zamknięte <br>
                  </p> 
              </blockquote>   
          </figure>
      </div>
      </div>
</section>

<footer class="bg-white shadow sm:flex sm:items-center sm:justify-between p-4 sm:p-6 xl:p-8 dark:bg-white antialiased">
  <p class="mb-4 text-sm text-center text-gray-500 dark:text-black sm:mb-0">
      &copy;2023 <a href="https://dreampire.pl/" class="hover:underline" target="_blank">Dreampire.pl</a>. All rights reserved.
  </p>
  <div class="flex justify-center items-center space-x-1">
</div>
</footer>
</template>

<style>

html {
  scroll-behavior: smooth;
}
</style>
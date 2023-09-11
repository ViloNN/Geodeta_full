<script setup>
import { initFlowbite } from 'flowbite'

onMounted(() => {
    initFlowbite();
})
</script>

<template>


<nav class="border-gray-200 bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
    <a href="#" class="flex items-center">
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Geodeta123123</span>
    </a>
    <button data-collapse-toggle="navbar-solid-bg" type="button" class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-solid-bg" aria-expanded="false">
        <span class="sr-only">Open main menu</span>
        <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
            <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
        </svg>
    </button>
    <div class="hidden w-full md:block md:w-auto" id="navbar-solid-bg">
      <ul class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:border-0 md:bg-transparent dark:bg-gray-800 md:dark:bg-transparent dark:border-gray-700">
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500 dark:bg-blue-600 md:dark:bg-transparent" aria-current="page">Strona główna</a>
        </li>
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Oferta</a>
        </li>
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Adres</a>
        </li>
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-white md:dark:hover:text-blue-500 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent">Kontakt</a>
        </li>
      </ul>
    </div>
  </div>
</nav>



<section class="bg-white bg-gray-300">
    <div class="gap-16 items-center py-8 px-4 mx-auto max-w-screen-xl lg:grid lg:grid-cols-2 lg:py-16 lg:px-6">
        <div class="font-light text-gray-500 sm:text-lg dark:text-gray-900">
            <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-gray-900">GEODETA UPRAWNIONY inż Eryk Brodowski</h2>
            <p class="mb-4">Geodeta uprawniony Eryk Brodowski posiada wieloletnie doświadczenie w branży geodezyjnej, każdego klienta obsługuje indywidualnie i rzetelnie.</p>
        </div>
        <div class="grid grid-cols-2 gap-4 mt-8">
            <img class="w-full rounded-lg" src="./zdj1.png" alt="office content 1">
            <img class="mt-4 w-full lg:mt-10 rounded-lg" src="./zdj2.png" alt="office content 2">
        </div>
    </div>
</section>


<section class="bg-white dark:bg-gray-300">
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center sm:py-16 lg:px-6">
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">O nas</h2>
      <p class="text-gray-500 sm:text-xl dark:text-gray-900">Świadczymy profesjonalne usługi geodezyjne od 1993 r. Działamy w powiatach legionowskim i pułtuskim. Wieloletnie doświadczenie przekłada się na wysoką jakość usług.. <br> <br> <br>
        · Świadczymy usługi dla firm, instytucji i klientów prywatnych <br>
        · Zapewniamy doradztwo, miłą i fachową obsługę oraz korzystne ceny <br> 
        · Jesteśmy dyspozycyjni i możemy dostosować się do klienta <br>
        · Podpowiemy w wyborze lokalnych wykonawców
      </p>
      <div class="mt-8 lg:mt-12 space-y-8 md:grid md:grid-cols-2 lg:grid-cols-3 md:gap-12 md:space-y-0">
      </div>
  </div>
</section>


<section class="bg-gray-50 dark:bg-gray-400">
  <div class="py-8 px-4 mx-auto max-w-screen-xl sm:py-16 lg:px-6">
      <div class="mx-auto max-w-screen-md text-center mb-8 lg:mb-16">
          <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Oferta</h2>
          <p class="font-light text-gray-500 dark:text-gray-900 sm:text-xl">Świadczymy profesjonalne oraz kompleksowe usługi w zakresie :</p>
      </div>
      <div class="space-y-8 md:grid md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 md:gap-8 xl:gap-8 md:space-y-0">
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-gray-700">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                  <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./inw.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Marketing</h3>
              <p class="font-light text-gray-500 dark:text-gray-400">Wszystkich map potrzebnych przy inwestycjach</p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-gray-700">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./komp.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Legal</h3>
              <p class="font-light text-gray-500 dark:text-gray-400">Podziału działek</p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-gray-700">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./plan.png">                 
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Business Automation</h3>
              <p class="font-light text-gray-500 dark:text-gray-400">Podpowiemy przy zakupie i sprzedaży nieruchomości</p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-gray-700">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./prz.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Finance</h3>
              <p class="font-light text-gray-500 dark:text-gray-400">Projektowaniu przyłączy i budynków</p>
          </div>
          <div class="p-6 bg-white rounded-2xl shadow dark:bg-gray-700">
              <div class="flex justify-center items-center mb-4 w-10 h-10 rounded bg-primary-100 lg:h-20 lg:w-20 dark:bg-primary-900">
                <img class="w-500 h-500 text-primary-600 lg:w-300 lg:h-300 dark:text-primary-300" src="./stojak.png">
              </div>
              <h3 class="mb-2 text-xl font-bold dark:text-white">Enterprise Design</h3>
              <p class="font-light text-gray-500 dark:text-gray-400">Obsługi inwestycji</p>
          </div>

      </div>
  </div>
</section>




<section class="bg-white dark:bg-gray-300">
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center sm:py-16 lg:px-6">
      <h2 class="mb-4 text-4xl tracking-tight font-extrabold text-gray-900 dark:text-white">Adres</h2>
      <p class="text-gray-500 sm:text-xl dark:text-gray-900">
        Rynek 17 lokal 4 <br>
        05-140 Serock <br>
        <a href="https://goo.gl/maps/uKfGGE2mrXhKQsHq7">WYZNACZ TRASĘ</a>
      </p>   
  </div>
</section>

<section class="bg-white dark:bg-gray-900">
  <div class="py-8 px-4 mx-auto max-w-screen-xl text-center lg:py-16 lg:px-6">
      <div class="grid mb-8 lg:mb-12 lg:grid-cols-2">
          <figure class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-6 lg:border-r dark:bg-gray-800 dark:border-gray-700">
              <blockquote class="mx-auto mb-4 max-w-2xl text-gray-500 dark:text-gray-400">
                  <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Konakt</h3>
                  <p class="my-4">
                    Geodeta Eryk Brodowski <br>
                    NIP: 5681544978 <br>
                    Adres e-mail: geodezja.serock@wp.pl, geodeta.eryk@gmail.com <br>
                    Tel. +48 535 855 260
                    </p>
              </blockquote>   
          </figure>
          <figure class="flex flex-col justify-center items-center p-8 text-center bg-gray-50 border-b border-gray-200 md:p-6 dark:bg-gray-800 dark:border-gray-700">
              <blockquote class="mx-auto mb-4 max-w-2xl text-gray-500 dark:text-gray-400">
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




<footer class="bg-white shadow sm:flex sm:items-center sm:justify-between p-4 sm:p-6 xl:p-8 dark:bg-gray-800 antialiased">
  <p class="mb-4 text-sm text-center text-gray-500 dark:text-gray-400 sm:mb-0">
      &copy; 2023<a href="https://dreampire.pl/" class="hover:underline" target="_blank">Dreampire.pl</a>. All rights reserved.
  </p>
  <div class="flex justify-center items-center space-x-1">
</div>
</footer>


</template>
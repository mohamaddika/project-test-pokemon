<template>
    <div class="bg-gray-100 py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row gap-4 m-10">
                <div class="md:w-1/4">
                    <center>
                        <svg class="h-40 w-40 text-red-700"  fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16l4.586-4.586a2 2 0 012.828 0L16 16m-2-2l1.586-1.586a2 2 0 012.828 0L20 14m-6-6h.01M6 20h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z"/>
                    </svg>
                    </center>
                    
                    <p class="mb-2 text-xl text-center font-bold tracking-tight text-red-600 dark:text-white">Tambah Image</p>
                </div>
                <div class="md:w-3/4">
                    <section class="bg-gray-50 dark:bg-gray-900">
         
              <div class="p-6 space-y-4 md:space-y-6 sm:p-8 border border-gray-200 rounded-lg shadow-xl">
                  <h1 class="text-2xl text-red-600 font-bold leading-tight tracking-tight text-gray-900 md:text-2xl dark:text-white">
                      Informasi Umum
                  </h1>
                  <form class="space-y-4 md:space-y-6" action="#">
                    <div>
                          <label for="email" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Nomor</label>
                          <p class="text-gray-700 font-semibold text-2xl pt-2">#16</p>
                      </div>
                      <div>
                          <label for="textl" class="block mb-2 text-sm font-medium text-gray-500 dark:text-white">Nama</label>
                          <input type="text" class="bg-red-50 border-gray-50 text-gray-900 sm:text-sm block w-full rounded-lg">
                      </div>
                      <div>
                          <label for="textl" class="block mb-2 text-sm font-medium text-gray-500 dark:text-white">Types</label>
                          <input type="text" class="bg-red-50 border-gray-50 text-gray-900 sm:text-sm block w-full rounded-lg">
                      </div>
                      <div>
                          <label for="textl" class="block mb-2 text-sm font-medium text-gray-500 dark:text-white">Classification</label>
                          <input type="text" class="bg-red-50 border-gray-50 text-gray-900 sm:text-sm block w-full rounded-lg">
                      </div>
                      <div>
                          <label for="textl" class="block mb-2 text-sm font-medium text-gray-500 dark:text-white">Resistant</label>
                          <input type="text" class="bg-red-50 border-gray-50 text-gray-900 sm:text-sm block w-full rounded-lg">
                      </div>
                      
                  </form>
              </div>
    
              <div class="p-6 mt-10 space-y-4 md:space-y-6 sm:p-8 border border-gray-200 rounded-lg shadow-xl">
                  <h1 class="text-2xl text-red-600 font-bold leading-tight tracking-tight text-gray-900 md:text-2xl dark:text-white">
                      Evolution
                  </h1>
                  <form class="space-y-4 md:space-y-6" action="#">
                      <div>
                        <button type="button" class="w-full  font-semibold focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-red-600 dark:hover:bg-red-700 dark:focus:ring-red-900">
                         + Tambah
                            </button>
                      </div>
                      
                  </form>
              </div>
    </section>
                </div>
                </div>
            </div>
        </div>
    
    </template>
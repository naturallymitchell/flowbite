---
layout: home
title: Tailwind CSS Colors - Flowbite
description: Customize the default colors of FlowBite using the Tailwind CSS configuration file
group: customize
toc: true

previous: Theming
previousLink: customize/theming/
next: Icons
nextLink: customize/icons/
---

## Default color palette

The team behind FlowBite carefully selected and extended the default Tailwind CSS color palette while keeping the same classes.

<div class="grid grid-cols-1 gap-8 my-12">
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Gray</div>
               <div><code class="text-xs text-gray-500">colors.coolGray</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#F9FAFB</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#F3F4F6</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#E5E7EB</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#D1D5DB</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#9CA3AF</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#6B7280</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#4B5563</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#374151</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#1F2937</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-gray-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#111827</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Red</div>
               <div><code class="text-xs text-gray-500">colors.red</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#FDF2F2</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#FDE8E8</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#FBD5D5</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#F8B4B4</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#F98080</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#F05252</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#E02424</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#C81E1E</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#9B1C1C</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-red-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#771D1D</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Yellow</div>
               <div><code class="text-xs text-gray-500">colors.amber</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#FDFDEA</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#FDF6B2</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#FCE96A</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#FACA15</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#E3A008</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#C27803</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#9F580A</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#8E4B10</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#723B13</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-yellow-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#633112</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Green</div>
               <div><code class="text-xs text-gray-500">colors.emerald</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#F3FAF7</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#DEF7EC</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#BCF0DA</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#84E1BC</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#31C48D</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#0E9F6E</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#057A55</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#046C4E</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#03543F</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-green-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#014737</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Blue</div>
               <div><code class="text-xs text-gray-500">colors.blue</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#EBF5FF</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#E1EFFE</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#C3DDFD</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#A4CAFE</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#76A9FA</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#3F83F8</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#1C64F2</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#1A56DB</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#1E429F</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-blue-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#233876</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Indigo</div>
               <div><code class="text-xs text-gray-500">colors.indigo</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#F0F5FF</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#E5EDFF</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#CDDBFE</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#B4C6FC</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#8DA2FB</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#6875F5</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#5850EC</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#5145CD</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#42389D</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-indigo-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#362F78</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Purple</div>
               <div><code class="text-xs text-gray-500">colors.violet</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#F6F5FF</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#EDEBFE</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#DCD7FE</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#CABFFD</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#AC94FA</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#9061F9</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#7E3AF2</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#6C2BD9</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#5521B5</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-purple-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#4A1D96</div>
               </div>
            </div>
         </div>
      </div>
   </div>
   <div>
      <div class="flex flex-col space-y-3 sm:flex-row text-xs sm:space-y-0 sm:space-x-4">
         <div class="w-32 flex-shrink-0">
            <div class="h-10 flex flex-col justify-center">
               <div class="text-sm font-semibold text-gray-900 dark:text-gray-400">Pink</div>
               <div><code class="text-xs text-gray-500">colors.pink</code></div>
            </div>
         </div>
         <div class="min-w-0 flex-1 grid grid-cols-5 2xl:grid-cols-10 gap-x-4 gap-y-3 2xl:gap-x-2">
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-50"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">50</div>
                  <div class="text-gray-900 dark:text-gray-400">#FDF2F8</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-100"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">100</div>
                  <div class="text-gray-900 dark:text-gray-400">#FCE8F3</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-200"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">200</div>
                  <div class="text-gray-900 dark:text-gray-400">#FAD1E8</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-300"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">300</div>
                  <div class="text-gray-900 dark:text-gray-400">#F8B4D9</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-400"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">400</div>
                  <div class="text-gray-900 dark:text-gray-400">#F17EB8</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-500"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">500</div>
                  <div class="text-gray-900 dark:text-gray-400">#E74694</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-600"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">600</div>
                  <div class="text-gray-900 dark:text-gray-400">#D61F69</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-700"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">700</div>
                  <div class="text-gray-900 dark:text-gray-400">#BF125D</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-800"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">800</div>
                  <div class="text-gray-900 dark:text-gray-400">#99154B</div>
               </div>
            </div>
            <div class="space-y-1.5">
               <div class="h-10 w-full rounded ring-1 ring-inset ring-black ring-opacity-0 bg-pink-900"></div>
               <div class="px-0.5 md:flex md:justify-between md:space-x-2 2xl:space-x-0 2xl:block">
                  <div class="w-6 font-medium text-gray-900 dark:text-gray-400">900</div>
                  <div class="text-gray-900 dark:text-gray-400">#751A3D</div>
               </div>
            </div>
         </div>
      </div>
   </div>
</div>

## Customize colors

If you'd like to customize and use your own colors instead of the default ones you can do so by changing the `color` object from the `tailwind.config.js` file.

```javascript
// tailwind.config.js
module.exports = {
  theme: {
    colors: {
      // Configure your color palette here
    }
  }
}
```

You can read more about <a href="https://tailwindcss.com/docs/customizing-colors" target="_blank">customizing colors on Tailwind CSS</a>.
---
layout: home
title: Tailwind CSS Table - Flowbite
description: Use the responsive table components from Flowbite to show complex data in an organized layout
group: components
toc: true

previous: Progress
previousLink: components/progress/
next: Tooltips
nextLink: components/tooltips/
---

Tables are important components when you want to show complex set of data within your website. You can use Flowbite's responsive table components and the multiple styles that it comes with.

## Default example

Use the following HTML markup and Tailwind CSS utility classes to show a data set using a table component.

{{< example class="dark:bg-gray-900" >}}
<div class="flex flex-col">
    <div class="overflow-x-auto sm:-mx-6 lg:-mx-8">
        <div class="py-2 inline-block min-w-full sm:px-6 lg:px-8">
            <div class="overflow-hidden sm:rounded-lg shadow-md">
                <table class="min-w-full">
                    <thead class="bg-gray-50 dark:bg-gray-700">
                        <tr>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Name
                            </th>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Color
                            </th>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Category
                            </th>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Price
                            </th>
                            <th scope="col" class="relative px-6 py-3">
                                <span class="sr-only">Edit</span>
                            </th>
                        </tr>
                    </thead>
                    <tbody>
                        <!-- Product 1 -->
                        <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple MacBook Pro 17"
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Sliver
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Laptop
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $2999
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                        <!-- Product 2 -->
                        <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple Imac 27"
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                White
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Desktop Pc
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $1999
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                        <!-- Product 3 -->
                        <tr class="bg-white dark:bg-gray-800">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple Magic Mouse 2
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                White
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Accessories
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $99
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</div>
{{< /example >}}

## Striped table

Use this alternative table style which uses an alternating background color for each row inside the table increasing readability overall.

{{< example class="dark:bg-gray-900" >}}
<div class="flex flex-col">
    <div class="overflow-x-auto sm:-mx-6 lg:-mx-8">
        <div class="py-2 inline-block min-w-full sm:px-6 lg:px-8">
            <div class="overflow-hidden sm:rounded-lg shadow-md">
                <table class="min-w-full">
                    <thead class="bg-gray-100 dark:bg-gray-700">
                        <tr>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Name
                            </th>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Color
                            </th>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Category
                            </th>
                            <th scope="col" class="text-xs font-medium text-gray-700 px-6 py-3 text-left uppercase tracking-wider dark:text-gray-400">
                                Price
                            </th>
                            <th scope="col" class="relative px-6 py-3">
                                <span class="sr-only">Edit</span>
                            </th>
                        </tr>
                    </thead>
                    <tbody>
                        <!-- Product 1 -->
                        <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-600">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple MacBook Pro 17"
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Sliver
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Laptop
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $2999
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                        <!-- Product 2 -->
                        <tr class="bg-gray-50 border-b dark:bg-gray-700 dark:border-gray-600">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple Imac 27"
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                White
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Desktop Pc
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $1999
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                        <!-- Product 3 -->
                        <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-600">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                iPhone 13 Pro 
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                White
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Phone
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $999
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                        <!-- Product 4 -->
                        <tr class="bg-gray-50 border-b dark:bg-gray-700 dark:border-gray-600">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple Magic Mouse 2
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                White
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Accessories
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $99
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                        <!-- Product 5 -->
                        <tr class="bg-white dark:bg-gray-800">
                            <td class="px-6 py-4 whitespace-nowrap text-sm font-medium text-gray-900 dark:text-white">
                                Apple Watch Series 7
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Pink
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                Accessories
                            </td>
                            <td class="text-sm text-gray-500 px-6 py-4 whitespace-nowrap dark:text-gray-400">
                                $599
                            </td>
                            <td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
                                <a href="#" class="text-blue-600 hover:text-blue-900 dark:text-blue-500 dark:hover:underline">Edit</a>
                            </td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
</div>
{{< /example >}}


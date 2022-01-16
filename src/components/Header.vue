<template>
  <div >

    <nav class="border-b border-white">
      <div class="container mx-auto flex flex-col md:flex-row items-center justify-between px-4 py-6" >
        <ul class="flex flex-col md:flex-row items-center" >

        <li>
          <a class="text-yellow-500"  href="#">

            <p> <font-awesome-icon icon="search" />
              Find my teacher
            </p>
          </a>
        </li>
          <li class="md:ml-16 mt-3 md:mt-0">
            <a class="hover:text-gray-300" href="#">Keress trénert</a>
          </li>
          <li class="md:ml-6 mt-3 md:mt-0">
            <a class="hover:text-gray-300" href="#">Tréner leszek</a>
          </li>
          <li class="md:ml-6 mt-3 md:mt-0">
            <a class="hover:text-gray-300" href="#">Előfizetés</a>
          </li>
        </ul>

        <div class="flex flex-col md:flex-row items-center ">
          <div class="relative  mt-3 md:mt-0">
            <input type="text" class="bg-gray-800 rounded-full w-64 px-4 py-1 pl-8" placeholder="Search">
            <div class="absolute top-0"><font-awesome-icon class="fill-current text-gray-500 mt-2 ml-2" icon="search" /></div>
          </div>
          
          <div class="ml-4 mt-3 md:mt-0">
            <img src="https://icon-library.com/images/avatar-icon-images/avatar-icon-images-4.jpg" alt="avatar" class="rounded-full w-8 h-8">
          </div>
        </div>



      </div>
    </nav>


  </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

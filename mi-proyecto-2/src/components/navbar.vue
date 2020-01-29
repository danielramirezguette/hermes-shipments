<template>
  <div>
 
<header class="lg:px-16 px-8 bg-blue-600 shadow-md py-4 md:py-0">
        <div class="container mx-auto flex flex-wrap items-center">
            <div class="flex-1 flex justify-between items-center">
                <a href="" class="text-xl font-semibold text-green-100 hover:text-white tracking-normal">Hermes shipments</a>
            </div>

            <label for="menu-toggle" class="pointer-cursor md:hidden block">
                <svg class="fill-current text-gray-300 hover:text-white" xmlns="http://www.w3.org/2000/svg" width="20" height="20"
                    viewBox="0 0 20 20">
                    <title>menu</title>
                    <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
                </svg>
            </label>
            <input class="hidden" type="checkbox" id="menu-toggle" />

            <div class="hidden md:flex md:items-center md:w-auto w-full" id="menu">
                <nav>
                    <ul class="md:flex items-center justify-between text-base pt-4 md:pt-0">
                        <li><a class="md:px-4 py-2 md:py-4 px-0 block text-green-100 hover:text-white md:hover:bg-green-800" href="">Log in</a></li>
                        <li><a class="md:px-4 py-2 md:py-4 px-0 block text-green-100 hover:text-white md:hover:bg-green-800" href="">Sing up</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
  </div>
  
</template>

<script>
  export default {

  }
  
</script>


<style media="screen">

  #menu-toggle:checked + #menu {
      display: block;
  }

  .dropdown:hover .dropdown-menu,
  .dropdown:active .dropdown-menu {
      display: block;
  }

</style>

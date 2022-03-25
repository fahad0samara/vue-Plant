<template>
<div class="div">

    <header class=" body-font   mt-14   ">
  <div class="container  mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
    <a class="flex title-font font-medium items-center  mb-4 md:mb-0">
     <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify  text-green-600 iconify--teenyicons" width="32" height="32" preserveAspectRatio="xMidYMid meet" viewBox="0 0 15 15"><path fill="currentColor" fill-rule="evenodd" d="M7 4.5A4.5 4.5 0 0 1 11.5 0H15v3.5A4.5 4.5 0 0 1 10.5 8H8v7H7v-4H4.5A4.5 4.5 0 0 1 0 6.5V3h3.5c1.414 0 2.675.652 3.5 1.671V4.5Zm1.146 1.646l3-3l.708.708l-3 3l-.708-.708Zm-2 3.708l-3-3l.708-.708l3 3l-.708.708Z" clip-rule="evenodd"></path></svg>
      <span class="ml-3 text-xl">Green Planet
      
      
      </span>
    </a>
    <nav class="md:ml-auto md:mr-auto flex flex-wrap items-center  justify-center text-4xl font-black ">
      <a class="mr-5 hover:text-white cursor-pointer  ">Home</a>
      <a class="mr-5 hover:text-white cursor-pointer">Catalog</a>
      <a class="mr-5 hover:text-white cursor-pointer">Blog</a>
      <a class="mr-5 hover:text-white cursor-pointer">Contacts</a>
    </nav>
   <button class="cssbuttons-io-button bg-green-500">  log in
  <div class="icon">
    <svg height="24" width="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"></path><path d="M16.172 11l-5.364-5.364 1.414-1.414L20 12l-7.778 7.778-1.414-1.414L16.172 13H4v-2z" fill="currentColor"></path></svg>
  </div>
</button>
  </div>
</header>
</div>
</template>
<script>

</script>
<style scoped>


.cssbuttons-io-button {

 color: white;
 font-family: inherit;
 padding: 0.35em;
 padding-left: 1.2em;
 font-size: 17px;
 font-weight: 500;
 border-radius: 0.9em;
 border: none;
 letter-spacing: 0.05em;
 display: flex;
 align-items: center;
 box-shadow: inset 0 0 1.6em -0.6em #00a975;
 overflow: hidden;
 position: relative;
 height: 2.8em;
 padding-right: 3.3em;
}

.cssbuttons-io-button .icon {
 background: white;
 margin-left: 1em;
 position: absolute;
 display: flex;
 align-items: center;
 justify-content: center;
 height: 2.2em;
 width: 2.2em;
 border-radius: 0.7em;
 box-shadow: 0.1em 0.1em 0.6em 0.2em #00a975;
 right: 0.3em;
 transition: all 0.3s;
}

.cssbuttons-io-button:hover .icon {
 width: calc(100% - 0.6em);
}

.cssbuttons-io-button .icon svg {
 width: 1.1em;
 transition: transform 0.3s;
 color: #7b52b9;
}

.cssbuttons-io-button:hover .icon svg {
 transform: translateX(0.1em);
}

.cssbuttons-io-button:active .icon {
 transform: scale(0.95);
}

</style>
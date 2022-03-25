<template>
  <div class="mt-12">

    <div class="grid grid-cols-2 gap-3">
      <div class="  space-y-10  mt-40">
        <h1 class="text-6xl text-white text-6xl font-extrabold">Plants for your home</h1>
        <h2 class="text-2xl font-bold ">
          Are you looking to add a little Zen to your home or office? The right houseplant
          acts as a beautiful decoration helping to purify the air and can even de stress
          the immediate area
        </h2>
        <button>BUY NOW</button>
      </div>
      <div  class=" w-auto">
        <img src="../assets/00.png" class="" alt="" />
      </div>
    </div>
    <div  class=" flex space-x-8 text-white hover:text-green-700">
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--cil" width="100" height="100"  preserveAspectRatio="xMidYMid meet" viewBox="0 0 512 512"><path fill="currentColor" d="M389.053 126.3A302.909 302.909 0 0 0 280.012 18.15L272 13.516l-8.012 4.634A301.084 301.084 0 0 0 113.4 279.042c0 3.445.06 6.944.177 10.4c1.592 46.856 19.511 86.283 51.82 114.018c24.724 21.225 56.438 34.182 90.607 37.273V496h32V240H256v168.528c-54.064-6.263-107.873-44.455-110.444-120.174c-.106-3.095-.16-6.228-.16-9.312A270.286 270.286 0 0 1 272 50.673a270.286 270.286 0 0 1 126.6 228.369c0 3.084-.054 6.217-.16 9.313c-2.056 60.573-36.907 97.127-78.444 112.536v33.867a156.188 156.188 0 0 0 58.607-31.3c32.309-27.735 50.228-67.162 51.82-114.017c.117-3.456.177-6.955.177-10.4A300.948 300.948 0 0 0 389.053 126.3Z"></path></svg>
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--akar-icons" width="100" height="100" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"><path d="M11.964 6.97s-3.075.306-4.685-1.035C5.669 4.593 6.036 2.03 6.036 2.03s3.075-.306 4.686 1.035c1.61 1.342 1.242 3.905 1.242 3.905Z"></path><path d="M12.036 6.97s3.075.306 4.685-1.035c1.61-1.342 1.243-3.905 1.243-3.905s-3.075-.306-4.685 1.035c-1.61 1.342-1.243 3.905-1.243 3.905ZM4 11a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-2Zm1 3h14l-2 8H7l-2-8Z"></path></g></svg>
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--tabler" width="100" height="100"  preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"><path d="M2 9a10 10 0 1 0 20 0"></path><path d="M12 19A10 10 0 0 1 22 9M2 9a10 10 0 0 1 10 10"></path><path d="M12 4a9.7 9.7 0 0 1 2.99 7.5m-5.98 0A9.7 9.7 0 0 1 12 4"></path></g></svg>
    
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--ri" width="100" height="100"  preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path fill="currentColor" d="M6 2a7 7 0 0 1 6.197 3.741A6.49 6.49 0 0 1 17.5 3H21v2.5a6.5 6.5 0 0 1-6.5 6.5H13v1h5v7a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-7h5v-2H9a7 7 0 0 1-7-7V2h4zm10 13H8v5h8v-5zm3-10h-1.5A4.5 4.5 0 0 0 13 9.5v.5h1.5A4.5 4.5 0 0 0 19 5.5V5zM6 4H4a5 5 0 0 0 5 5h2a5 5 0 0 0-5-5z"></path></svg>
    </div>
  </div>
</template>
<style scoped>
button {
  font-size: 30px;
  padding: 1em 3.3em;
  transform: perspective(200px) rotateX(15deg);
  color: white;
  font-weight: 900;
  border: none;
  border-radius: 5px;
  background: linear-gradient(0deg, #00a975 0%, rgb(55, 219, 49) 100%);
  box-shadow: rgba(63, 94, 251, 0.2) 0px 40px 29px 0px;
  will-change: transform;
  transition: all 0.3s;
  border-bottom: 2px solid rgb(247, 242, 242);
}

button:hover {
  transform: perspective(180px) rotateX(30deg) translateY(2px);
}

button:active {
  transform: perspective(170px) rotateX(36deg) translateY(5px);
}
</style>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="max-w-screen-lg mx-auto p-4">
    <!-- Header -->
    <header class="flex justify-between items-center bg-white p-4 shadow-md">
      <img
        src="https://storage.googleapis.com/a1aa/image/jqLQxLG4RvK9GJAFZ2MA1xYgLmMffpWX7dxcjKEHOQf5sbynA.jpg"
        alt="Logo"
        class="h-10"
        width="50"
        height="50"
      />
      <div class="flex space-x-4">
        <i class="fas fa-bell text-gray-600"></i>
        <i class="fas fa-user-circle text-gray-600"></i>
      </div>
    </header>

    <!-- Main Content -->
    <section class="bg-blue-900 text-white p-4 text-center">
      <h1 class="text-2xl font-bold">Roll with Patrol</h1>
      <div class="flex justify-center space-x-4 mt-4">
        <img
          src="https://storage.googleapis.com/a1aa/image/xrTp3T0f0ZS3OyXqntO7OqbiPrE39c4js8fUPG1xdQjg2N5TA.jpg"
          alt="Chase"
          class="h-24"
          width="100"
          height="100"
        />
        <img
          src="https://storage.googleapis.com/a1aa/image/uYK33chDeXTFeEzF9EKjFs74vBaomF7ModXPIbXnn0Fh2N5TA.jpg"
          alt="Marshall"
          class="h-24"
          width="100"
          height="100"
        />
        <img
          src="https://storage.googleapis.com/a1aa/image/zKcMuLZtUeyCNSQmxV5f5iq5EiaKcDmS82Xqlek5bKOGtbynA.jpg"
          alt="Skye"
          class="h-24"
          width="100"
          height="100"
        />
      </div>
    </section>

    <!-- Other sections -->
    <section class="bg-white p-4 mt-4 shadow-md">
      <div class="flex justify-between items-center">
        <h2 class="text-lg font-bold">Your Level</h2>
        <a href="#" class="text-blue-500">Learn More</a>
      </div>
      <div class="flex items-center mt-4">
        <div class="flex-1 text-center">
          <div class="bg-gray-200 p-2 rounded-full">Silver</div>
        </div>
        <div class="flex-1 text-center">
          <div class="bg-gray-200 p-2 rounded-full">Gold</div>
        </div>
        <div class="flex-1 text-center">
          <div class="bg-gray-200 p-2 rounded-full">Platinum</div>
        </div>
      </div>
      <p class="text-center mt-4">Spend 3,500,001 by 23 Nov 2024 to reach Gold</p>
      <div class="flex justify-between items-center mt-4">
        <p>Bakmi GM Points</p>
        <p>40</p>
      </div>
    </section>
    <section class="bg-white p-4 mt-4 shadow-md">
      <div class="flex justify-between items-center">
        <h2 class="text-lg font-bold">Your Level</h2>
        <a href="#" class="text-blue-500">Learn More</a>
      </div>
      <div class="flex items-center mt-4">
        <div class="flex-1 text-center">
          <div class="bg-gray-200 p-2 rounded-full">Silver</div>
        </div>
        <div class="flex-1 text-center">
          <div class="bg-gray-200 p-2 rounded-full">Gold</div>
        </div>
        <div class="flex-1 text-center">
          <div class="bg-gray-200 p-2 rounded-full">Platinum</div>
        </div>
      </div>
      <p class="text-center mt-4">Spend 3,500,001 by 23 Nov 2024 to reach Gold</p>
      <div class="flex justify-between items-center mt-4">
        <p>Bakmi GM Points</p>
        <p>40</p>
      </div>
    </section>
    <!-- Add other sections similarly -->
    <section class="bg-white p-4 mt-4 shadow-md text-center">
    <p class="text-sm text-gray-600">
     Dapatkan 5 poin dengan mengajak teman kamu
    </p>
    <button class="bg-blue-500 text-white px-4 py-2 rounded mt-4">
     REFER NOW
    </button>
   </section>
   <section class="bg-white p-4 mt-4 shadow-md">
    <div class="flex justify-between items-center">
     <h2 class="text-lg font-bold">
      Redeem Your Rewards
     </h2>
     <a class="text-blue-500" href="#">
      SEE ALL
     </a>
    </div>
    <div class="flex space-x-4 mt-4 overflow-x-auto">
     <div class="flex-none w-40">
      <img alt="Es Teh Manis" class="w-full h-32 object-cover rounded" height="150" src="https://storage.googleapis.com/a1aa/image/2e3nYedl90p7NUoHTu9QvvQhIPH8queAoTAI9hvCXxU2hbynA.jpg" width="150"/>
      <p class="text-sm mt-2">
       Es Teh Manis
      </p>
      <p class="text-sm text-gray-600">
       40 Pts
      </p>
     </div>
     <div class="flex-none w-40">
      <img alt="Lemon Es Teh" class="w-full h-32 object-cover rounded" height="150" src="https://storage.googleapis.com/a1aa/image/Hl5klR8Z3iYtLhU3WQnucfNqenK0Nn4tgoqGVPzPSQp8wN5TA.jpg" width="150"/>
      <p class="text-sm mt-2">
       Lemon Es Teh
      </p>
      <p class="text-sm text-gray-600">
       45 Pts
      </p>
     </div>
     <div class="flex-none w-40">
      <img alt="Paw Patrol" class="w-full h-32 object-cover rounded" height="150" src="https://storage.googleapis.com/a1aa/image/Cf41DKfLhDvrPkByeALIO8fY4bPh9AfxZdWfyuXsvBdfg4m8JA.jpg" width="150"/>
      <p class="text-sm mt-2">
       Paw Patrol
      </p>
      <p class="text-sm text-gray-600">
       155 Pts
      </p>
     </div>
    </div>
   </section>
   <section class="bg-white p-4 mt-4 shadow-md">
    <h2 class="text-lg font-bold">
     Privileges
    </h2>
    <div class="grid grid-cols-2 gap-4 mt-4">
     <div class="bg-yellow-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       PLATINUM Member
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 Dec 2024
      </p>
     </div>
     <div class="bg-yellow-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       GOLD Member
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 Dec 2024
      </p>
     </div>
     <div class="bg-blue-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       Birthday Reward
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 Dec 2024
      </p>
     </div>
     <div class="bg-red-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       Redeem Point
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 Dec 2024
      </p>
     </div>
     <div class="bg-yellow-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       Sign Up Reward
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 Dec 2024
      </p>
     </div>
     <div class="bg-red-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       Benefit GMania
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 Dec 2024
      </p>
     </div>
     <div class="bg-yellow-100 p-4 rounded">
      <h3 class="text-sm font-bold">
       FAQ MEMBER
      </h3>
      <p class="text-sm text-gray-600">
       Exp. 31 May 2024
      </p>
     </div>
    </div>
   </section>
   <section class="bg-white p-4 mt-4 shadow-md">
    <h2 class="text-lg font-bold">
     Outlet Location
    </h2>
    <ul class="mt-4 space-y-4">
     <li>
      <h3 class="text-sm font-bold">
       Citra Garden 6
      </h3>
      <p class="text-sm text-gray-600">
       Jalan Citra Garden 6 Blok J2 No. 1, Citra Garden City, Jakarta Barat
      </p>
     </li>
     <li>
      <h3 class="text-sm font-bold">
       Emporium Mall
      </h3>
      <p class="text-sm text-gray-600">
       Emporium Pluit Mall Lt. 2 Jalan Pluit Selatan Raya, Jakarta Utara
      </p>
     </li>
     <li>
      <h3 class="text-sm font-bold">
       Puri Indah Mall
      </h3>
      <p class="text-sm text-gray-600">
       Puri Indah Mall, Jalan Puri Indah Raya Blok U1, Puri Indah, Kembangan, Jakarta Barat
      </p>
     </li>
     <li>
      <h3 class="text-sm font-bold">
       Lippo Mall Puri
      </h3>
      <p class="text-sm text-gray-600">
       Bakmi GM Lippo Mall Puri, Food Avenue Unit FSD 07, Gedung B, Puri Indah Mall, Puri Indah CBD, Jalan Puri Indah Raya, Jakarta Barat
      </p>
     </li>
     <li>
      <h3 class="text-sm font-bold">
       Terminal 3 Ultimate
      </h3>
      <p class="text-sm text-gray-600">
       Bandara Soekarno Hatta, Terminal 3 Ultimate Domestic Landside, Lantai 2 Ultimate Food Emporium, Tangerang
      </p>
     </li>
    </ul>
    <div class="text-center mt-4">
     <a class="text-blue-500" href="#">
      SEE ALL
     </a>
    </div>
   </section>
  </div>
</template>

<style scoped>

</style>

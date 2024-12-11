<script setup>
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <div class="max-w-screen-lg mx-auto p-4">
    <header class="flex justify-between items-center bg-white p-2 shadow">

      <div class="flex items-center space-x-4 ml-3">
      <img
        src="https://cdn-icons-png.flaticon.com/512/1946/1946488.png"
        alt="Logo"
        class="h-12 w-12"
      />
    </div>

    <div class="flex items-center mr-3">
      <img
        src="https://cdn-icons-png.flaticon.com/512/5509/5509636.png"
        alt="Logo"
        class="h-12 w-12"
      />
    </div>
    </header>

    <section class="text-white text-center py-2">
      <div
        id="indicators-carousel"
        class="relative w-full"
        data-carousel="static"
      >
        <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
          <div
            class="hidden duration-700 ease-in-out"
            data-carousel-item="active"
          >
            <img
              src="https://gratisography.com/wp-content/uploads/2024/01/gratisography-cyber-kitty-800x525.jpg"
              class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
              alt="..."
            />
          </div>

          <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img
              src="https://img.freepik.com/free-photo/buddha-bowl-dish-with-vegetables-legumes-top-view_1150-42589.jpg"
              class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
              alt="..."
            />
          </div>

          <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img
              src="https://t4.ftcdn.net/jpg/01/20/28/25/360_F_120282530_gMCruc8XX2mwf5YtODLV2O1TGHzu4CAb.jpg"
              class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
              alt="..."
            />~
          </div>

          <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img
              src="https://img.freepik.com/free-photo/buddha-bowl-dish-with-vegetables-legumes-top-view_1150-42589.jpg"
              class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
              alt="..."
            />
          </div>

          <div class="hidden duration-700 ease-in-out" data-carousel-item>
            <img
              src="https://t4.ftcdn.net/jpg/01/20/28/25/360_F_120282530_gMCruc8XX2mwf5YtODLV2O1TGHzu4CAb.jpg"
              class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2"
              alt="..."
            />
          </div>
        </div>

        <div
          class="absolute z-30 flex -translate-x-1/2 space-x-3 rtl:space-x-reverse bottom-5 left-1/2"
        >
          <button
            type="button"
            class="w-3 h-3 rounded-full"
            aria-current="true"
            aria-label="Slide 1"
            data-carousel-slide-to="0"
          ></button>
          <button
            type="button"
            class="w-3 h-3 rounded-full"
            aria-current="false"
            aria-label="Slide 2"
            data-carousel-slide-to="1"
          ></button>
          <button
            type="button"
            class="w-3 h-3 rounded-full"
            aria-current="false"
            aria-label="Slide 3"
            data-carousel-slide-to="2"
          ></button>
          <button
            type="button"
            class="w-3 h-3 rounded-full"
            aria-current="false"
            aria-label="Slide 4"
            data-carousel-slide-to="3"
          ></button>
          <button
            type="button"
            class="w-3 h-3 rounded-full"
            aria-current="false"
            aria-label="Slide 5"
            data-carousel-slide-to="4"
          ></button>
        </div>

        <button
          type="button"
          class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none"
          data-carousel-prev
        >
          <span
            class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none"
          >
            <svg
              class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 6 10"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 1 1 5l4 4"
              />
            </svg>
            <span class="sr-only">Previous</span>
          </span>
        </button>
        <button
          type="button"
          class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none"
          data-carousel-next
        >
          <span
            class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none"
          >
            <svg
              class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180"
              aria-hidden="true"
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 6 10"
            >
              <path
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="m1 9 4-4-4-4"
              />
            </svg>
            <span class="sr-only">Next</span>
          </span>
        </button>
      </div>
    </section>

    <section class="bg-white shadow mt-2 p-6 rounded">
      <div class="flex justify-between items-center">
        <h2 class="text-lg font-semibold">Your Level</h2>
        <a href="#" class="text-orange-500 hover:underline">Learn More</a>
      </div>

      <div class="flex flex-col items-center mt-6">
        <div
          class="flex items-center space-x-4 sm:space-x-8 flex-wrap justify-center"
        >
          <div class="relative flex flex-col items-center">
            <div
              class="w-14 h-14 rounded-full flex items-center justify-center border-4 border-green-500"
            >
              <img
                src="https://cdn-icons-png.flaticon.com/512/12624/12624745.png"
                alt="Silver Icon"
                class="w-10 h-10"
              />
            </div>
            <p class="mt-2 text-sm font-semibold text-gray-700">Silver</p>
          </div>

          <div class="w-8 h-1 bg-gray-300 sm:w-12"></div>

          <div class="relative flex flex-col items-center">
            <div
              class="w-14 h-14 bg-gray-100 rounded-full flex items-center justify-center border-4 border-yellow-400"
            >
              <!-- <div class="w-6 h-6 bg-yellow-300 rounded-full"></div> -->
              <img
                src="https://cdn-icons-png.flaticon.com/512/891/891399.png"
                alt="Silver Icon"
                class="w-10 h-10"
              />
            </div>
            <p class="mt-2 text-sm font-semibold text-gray-700">Gold</p>
          </div>

          <div class="w-8 h-1 bg-gray-300 sm:w-12"></div>

          <div class="relative flex flex-col items-center">
            <div
              class="w-14 h-14 bg-gray-100 rounded-full flex items-center justify-center border-4 border-gray-300"
            >
              <!-- <div class="w-6 h-6 bg-gray-500 rounded-full"></div> -->
              <img
                src="https://cdn-icons-png.flaticon.com/512/891/891399.png"
                alt="Silver Icon"
                class="w-10 h-10"
              />
            </div>
            <p class="mt-2 text-sm font-semibold text-gray-700">Platinum</p>
          </div>
        </div>

        <p class="text-center text-sm mt-6 text-gray-600">
          Spend
          <span class="font-bold text-black">3,500,001</span> by
          <span class="font-bold text-black">23 Nov 2024</span> to reach
          <span class="text-yellow-500 font-semibold">Gold</span>
        </p>

        <div class="relative w-full mt-4">
          <div class="bg-gray-200 h-2 rounded-full">
            <div
              class="bg-yellow-400 h-2 rounded-full"
              style="width: 40%"
            ></div>
          </div>
        </div>
      </div>
    </section>

    <section class="bg-white shadow mt-2 p-4 rounded">
      <div class="flex justify-between items-center">
        <span class="text-gray-700 font-medium">Bakmi GM Points</span>
        <span class="font-bold text-lg">40</span>
      </div>
      <p class="text-sm text-gray-600">
        40 will expire on <span class="font-bold text-black">22 Feb 2024</span>
        <a href="#" class="text-blue-500 hover:underline">See Details</a>
      </p>
    </section>

    <section class="bg-blue-900 rounded-lg text-white text-center py-6 my-2">
      <h1 class="text-3xl font-bold">Roll with Patrol</h1>
      <div class="flex justify-center space-x-6 mt-6">
        <img
          src="https://cdn-icons-png.flaticon.com/512/6485/6485869.png"
          alt="Sign Up Reward"
          class="w-24 h-24 mr-4"
        />
        <div class="p-4">
          <h2 class="text-lg font-bold flex items-center space-x-2">
            <span>Sign Up Reward</span>
            <i class="fas fa-coins text-yellow-500"></i>
          </h2>
          <p class="text-gray-600">Exp. 31 Dec 2024</p>
        </div>
      </div>
    </section>

    <section class="bg-white p-4">
      <div class="grid grid-cols-3 gap-4 text-center mb-8">
        <div>
          <div class="bg-blue-100 rounded-full p-4 mb-2">
            <img
              alt="Basket with items icon"
              class="mx-auto"
              height="50"
              width="50"
              src="https://cdn-icons-png.flaticon.com/512/6632/6632848.png"
            />
          </div>
          <p class="text-gray-700">Order</p>
        </div>
        <div>
          <div class="bg-red-100 rounded-full p-4 mb-2">
            <img
              alt="Basket with items icon"
              class="mx-auto"
              height="50"
              src="https://cdn-icons-png.flaticon.com/512/5499/5499587.png"
              width="50"
            />
          </div>
          <p class="text-gray-700">Redeem</p>
        </div>
        <div>
          <div class="bg-pink-100 rounded-full p-4 mx-auto mb-2">
            <img
              alt="Voucher icon"
              class="mx-auto"
              height="50"
              src="https://cdn-icons-png.flaticon.com/512/5939/5939991.png"
              width="50"
            />
          </div>
          <p class="text-gray-700">My Vouchers</p>
        </div>
        <div>
          <div class="bg-purple-100 rounded-full p-4 mx-auto mb-2">
            <img
              alt="Envelope with crown icon"
              class="mx-auto"
              height="50"
              src="https://cdn-icons-png.flaticon.com/512/3053/3053782.png"
              width="50"
            />
          </div>
          <p class="text-gray-700">Privilege</p>
        </div>
        <div>
          <div class="bg-purple-100 rounded-full p-4 mx-auto mb-2">
            <img
              alt="Calendar icon"
              class="mx-auto"
              height="50"
              src="https://cdn-icons-png.flaticon.com/512/1373/1373354.png"
              width="50"
            />
          </div>
          <p class="text-gray-700">History</p>
        </div>
        <div>
          <div class="bg-green-100 rounded-full p-4 mx-auto mb-2">
            <img
              alt="Chat bubbles icon"
              class="mx-auto"
              height="50"
              src="https://cdn-icons-png.flaticon.com/512/8090/8090718.png"
              width="50"
            />
          </div>
          <p class="text-gray-700">Contact Us</p>
        </div>
      </div>
      <div class="bg-blue-500 rounded-lg p-6 text-white text-center">
        <div class="flex items-center justify-center mb-4">
          <img
            alt="People celebrating with coins"
            class="w-32 h-24"
            height="100"
            src="https://png.pngtree.com/png-vector/20220520/ourmid/pngtree-a-man-holds-a-megaphone-in-his-hands-and-invites-friends-png-image_4688819.png"
            width="100"
          />
        </div>
        <p class="text-lg font-semibold mb-4">
          Dapatkan 500 poin dengan mengajak teman kamu
        </p>
        <button class="bg-white text-blue-500 font-semibold py-2 px-4 rounded">
          REFER NOW
        </button>
      </div>
    </section>

    <section class="bg-white shadow mt-6 p-6 rounded">
      <div class="flex justify-between items-center">
        <h2 class="text-lg font-semibold">Redeem Your Rewards</h2>
        <a href="#" class="text-blue-500 hover:underline">SEE ALL</a>
      </div>
      <div class="flex overflow-x-auto space-x-4 mt-4">
        <div class="flex-none w-40">
          <img
            src="https://natashaskitchen.com/wp-content/uploads/2021/07/Iced-Tea-3-1.jpg"
            alt="Es Teh Manis"
            class="w-full h-32 object-cover rounded"
          />
          <p class="mt-2 text-sm">Es Teh Manis</p>
          <p class="text-sm text-gray-500">40 Pts</p>
        </div>
        <div class="flex-none w-40">
          <img
            src="https://img.freepik.com/free-photo/front-view-fresh-cool-lemonade-with-ice-lemon-blue-background-fruit-water-cocktail-drink-color-bar-juice-cold_140725-157107.jpg"
            alt="Lemon Es Teh"
            class="w-full h-32 object-cover rounded"
          />
          <p class="mt-2 text-sm">Lemon Es Teh</p>
          <p class="text-sm text-gray-500">45 Pts</p>
        </div>
        <div class="flex-none w-40">
          <img
            src="https://www.eatingwell.com/thmb/d9os8qr1Qn89eyrnYmNIyM2e-MU=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/CreamyWatermelonSmoothie_03114_preview-672780aa7a53471cb0db422245da039c.jpg"
            alt="juice drink"
            class="w-full h-32 object-cover rounded"
          />
          <p class="mt-2 text-sm">Juice drink</p>
          <p class="text-sm text-gray-500">155 Pts</p>
        </div>
      </div>
    </section>

    <section class="mt-8">
      <h1 class="text-3xl font-bold mb-2">Privileges</h1>
      <p class="text-gray-600 mb-6">Keep discovering our promo and news</p>
      <div class="grid grid-cols-2 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div
          class="bg-white rounded-lg shadow-md"
          style="height: auto; width: 100%"
        >
          <img
            src="https://honeyland.com.my/wp-content/uploads/2020/03/Platinum-Member.jpeg"
            alt="PLATINUM Member"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold flex items-center space-x-2">
              <span>PLATINUM Member</span>
              <i class="fas fa-gem text-blue-500"></i>
            </h2>
            <p class="text-gray-600">Exp. 31 Dec 2024</p>
          </div>
        </div>

        <div class="bg-white rounded-lg shadow-md">
          <img
            src="https://t4.ftcdn.net/jpg/00/73/86/15/360_F_73861526_LtpJx2lVn4Q1pd88r8yJLvDFfc1xxuC8.jpg"
            alt="GOLD Member"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold flex items-center space-x-2">
              <span>GOLD Member</span>
              <i class="fas fa-star text-yellow-500"></i>
            </h2>
            <p class="text-gray-600">Exp. 31 Dec 2024</p>
          </div>
        </div>

        <div class="bg-white rounded-lg shadow-md">
          <img
            src="https://cdn-icons-png.flaticon.com/512/5434/5434028.png"
            alt="Birthday Reward"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold flex items-center space-x-2">
              <span>Birthday Reward</span>
              <i class="fas fa-birthday-cake text-pink-500"></i>
            </h2>
            <p class="text-gray-600">Exp. 31 Dec 2024</p>
          </div>
        </div>

        <div class="bg-white rounded-lg shadow-md">
          <img
            src="https://cdn-icons-png.flaticon.com/512/5499/5499587.png"
            alt="Redeem Point"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold flex items-center space-x-2">
              <span>Redeem Point</span>
              <i class="fas fa-coins text-yellow-500"></i>
            </h2>
            <p class="text-gray-600">Exp. 31 Dec 2024</p>
          </div>
        </div>

        <div class="bg-white rounded-lg shadow-md">
          <img
            src="https://cdn-icons-png.freepik.com/256/3480/3480971.png?semt=ais_hybrid"
            alt="Sign Up Reward"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold flex items-center space-x-2">
              <span>Sign Up Reward</span>
              <i class="fas fa-coins text-yellow-500"></i>
            </h2>
            <p class="text-gray-600">Exp. 31 Dec 2024</p>
          </div>
        </div>

        <div class="bg-white rounded-lg shadow-md">
          <img
            src="https://cdn-icons-png.flaticon.com/512/11443/11443702.png"
            alt="Benefit GMania"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold flex items-center space-x-2">
              <span>Benefit GMania</span>
              <i class="fas fa-coins text-yellow-500"></i>
            </h2>
            <p class="text-gray-600">Exp. 31 Dec 2024</p>
          </div>
        </div>

        <div class="bg-white rounded-lg shadow-md">
          <img
            src="https://cdn-icons-png.flaticon.com/512/16744/16744214.png"
            alt="FAQ MEMBER"
            class="w-full h-48 object-cover"
          />
          <div class="p-4">
            <h2 class="text-lg font-bold">FAQ MEMBER</h2>
            <p class="text-gray-600">Exp. 31 Mar 2024</p>
          </div>
        </div>
      </div>
    </section>
    <section class="bg-white shadow mt-6 p-6 rounded">
      <h2 class="text-lg font-semibold">Outlet Location</h2>
      <ul class="mt-4 space-y-4 text-gray-600 text-sm">
        <li>
          <h3 class="font-semibold">Citra Garden 6</h3>
          <p>Jalan Citra Garden 6 Blok J2 No. 1, Jakarta Barat</p>
        </li>
        <li>
          <h3 class="font-semibold">Emporium Mall</h3>
          <p>Emporium Pluit Mall Lt. 2, Jakarta Utara</p>
        </li>
        <li>
          <h3 class="font-semibold">Puri Indah Mall</h3>
          <p>Puri Indah Mall, Jakarta Barat</p>
        </li>
      </ul>
      <div class="text-center mt-4">
        <a href="#" class="text-blue-500 hover:underline">SEE ALL</a>
      </div>
    </section>
  </div>
</template>

<style scoped></style>

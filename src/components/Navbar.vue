<template>
  <nav
    class="bg-white dark:bg-gray-900 fixed w-full z-20 top-0 start-0 border-b border-gray-200 dark:border-gray-600"
  >
    <div
      class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4"
    >
      <a href="#" class="flex items-center space-x-3 rtl:space-x-reverse">
        <!-- <img
          src="https://flowbite.com/docs/images/logo.svg"
          class="h-8"
          alt="Flowbite Logo"
        /> -->
        <span
          class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white"
          >web portfolio | noval rialan</span
        >
      </a>
      <div class="flex md:order-2 space-x-3 md:space-x-0 rtl:space-x-reverse">
        <!-- <button
          type="button"
          class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800"
        >
          Get started
        </button> -->
        <button
          data-collapse-toggle="navbar-sticky"
          type="button"
          class="inline-flex items-center p-2 w-10 h-10 justify-center text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
          aria-controls="navbar-sticky"
          aria-expanded="false"
        >
          <span class="sr-only">Open main menu</span>
          <svg
            class="w-5 h-5"
            aria-hidden="true"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 17 14"
          >
            <path
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M1 1h15M1 7h15M1 13h15"
            />
          </svg>
        </button>
      </div>
      <div
        class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
        id="navbar-sticky"
      >
        <ul
          class="flex flex-col p-4 md:p-0 mt-4 font-medium border border-gray-100 rounded-lg bg-gray-50 md:space-x-8 rtl:space-x-reverse md:flex-row md:mt-0 md:border-0 md:bg-white dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700"
        >
          <li>
            <a
              href="#"
              class="block py-2 px-3 text-white bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 md:dark:text-blue-500"
              aria-current="page"
              >Home</a
            >
          </li>
          <li>
            <a
              href="#Experience"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >Experience</a
            >
          </li>
          <li>
            <a
              href="#Supports"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
            >
              Supports</a
            >
          </li>
          <li>
            <a
              href="#Service"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >Services</a
            >
          </li>
          <li>
            <a
              href="#Tools"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
            >
              Tools</a
            >
          </li>
          <li>
            <a
              href="#Contact"
              class="block py-2 px-3 text-gray-900 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-blue-500 dark:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
              >Contact</a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- end Navigation -->

  <div class="bg-gradient-to-r from-blue-500 w-full mt-10">
    <br />
    <br />
    <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 mr2">
      <!-- quote content -->
      <div class="bg-white dark:bg-gray-800 rounded-md p-8">
        <figure class="max-w-md">
          <blockquote>
            <p
              class="text-2xl text-justify font-semibold text-gray-900 dark:text-white"
            >
              Hi, let me introduce myself to you <br />
              I'm Noval Rialan a <strong> software engineer</strong> and I like
              drinking coffee during work and breaks
            </p>
          </blockquote>
          <figcaption
            class="flex items-center mt-6 space-x-3 rtl:space-x-reverse"
          >
            <img
              class="w-6 h-6 rounded-full"
              src="/src/assets/images/person.png"
              alt="profile picture"
            />
            <div
              class="flex items-center divide-x-2 rtl:divide-x-reverse divide-gray-300 dark:divide-gray-700"
            >
              <cite class="pe-3 font-medium text-gray-900 dark:text-white"
                >Noval Rialan</cite
              >
              <cite class="ps-3 text-sm text-gray-500 dark:text-gray-400"
                >Junior software engineer web and mobile</cite
              >
            </div>
          </figcaption>
        </figure>
      </div>
      <!-- quote content -->

      <div class="flex justify-center md:flex-wrap md:order-2">
        <div class="relative h-100 w-100">
          <img
            class="h-190 rounded-full md:h-auto md:-mb-2 mb-4"
            src="/src/assets/images/person.png"
            alt="person"
            srcset=""
          />
        </div>
      </div>
    </div>

    <br />
  </div>
</template>
<script setup>
import { onMounted } from "vue";
import {
  initAccordions,
  initCarousels,
  initCollapses,
  initDials,
  initDismisses,
  initDrawers,
  initDropdowns,
  initModals,
  initPopovers,
  initTabs,
  initTooltips,
} from "flowbite";

// initialize components based on data attribute selectors
onMounted(() => {
  initAccordions();
  initCarousels();
  initCollapses();
  initDials();
  initDismisses();
  initDrawers();
  initDropdowns();
  initModals();
  initPopovers();
  initTabs();
  initTooltips();
});

// const navLinks = [
//   { dashboard: "Dashboard" },

//   { profile: "Profile" },

//   { tools: "Tools" },

//   { news: "News" },
// ];
</script>


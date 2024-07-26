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
        >
          web portfolio | noval rialan</span
        >
      </a>
      <div class="flex md:order-2 space-x-3 md:space-x-0 rtl:space-x-reverse">
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
  <div
    id="container"
    class="p-20 w-auto flex px-24 justify-center relative font-poppins bg-black"
  >
    <div
      id="container "
      class="p-20 sm:p-16 lg:p-24 xl:p-20 w-auto flex flex-col md:flex-row px-4 sm:px-8 md:px-24 lg:px-24 xl:px-24 relative"
    >
      <div class="relative">
        <img
          class="bg-sky-500 rounded-full min-w-[100px] w-90 h-90 md:w-auto md:h-auto m-8 md:content-center"
          src="/src/assets/images/person.png"
          alt="image of myself"
        />
      </div>
      <div class="w-full sm:w-[70%] md:w-[60%] lg:w-[50%]">
        <h1 class="text-white font-bold text-3xl mt-6 mb-10 m-8">
          Hey I'm, Noval Rialan
        </h1>
        <p
          class="text-justify text-white w-full sm:w-[35rem] md:w-[30rem] lg:w-[35rem] m-8"
        >
          Nickname, Noval, passion for web development. My tech journey started
          with HTML, CSS, and JavaScript, and I was hooked by the thrill of
          crafting dynamic, interactive websites. As I grew, Node.js, vue.jS,
          and ReactJS became my go-to tools for building scalable applications.
          Feel free to connect if you have questions, collaboration ideas, or
          just want to discuss the latest in web development !
        </p>
        <div
          id="social"
          class="flex flex-wrap justify-start items-center gap-2 m-7"
        >
          <a
            rel="noopener"
            target="_blank"
            href="https://www.github.com/novalrialan"
            class="bg-gray-800 rounded-lg p-5 w-64 flex items-center gap-2 text-white"
            ><img
              class="mr-2 hover:scale-105 transition duration-300 ease-in-out"
              src="https://ucarecdn.com/1f465c47-4849-4935-91f4-29135d8607af/github2.svg"
              width="20px"
              height="20px"
              alt="Github"
            /><span>Visit my Github</span></a
          ><a
            rel="noopener"
            target="_blank"
            href="https://www.linkedin.com/in/noval-rialan"
            class="bg-gray-800 rounded-lg p-5 w-64 flex items-center gap-2 text-white"
            ><img
              class="mr-2 hover:scale-105 transition duration-300 ease-in-out"
              src="https://ucarecdn.com/95eebb9c-85cf-4d12-942f-3c40d7044dc6/linkedin.svg"
              width="20px"
              height="20px"
              alt="LinkedIn"
            /><span>Follow me on Linkedin</span></a
          >
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
import { onMounted } from "vue";
import {
  initDropdowns,
  initModals,
  initPopovers,
  initTabs,
  initTooltips,
} from "flowbite";

// initialize components based on data attribute selectors
onMounted(() => {
  initDropdowns();
  initModals();
  initPopovers();
  initTabs();
  initTooltips();
  type();
});

const words = [
  "Hello, Welcome to My Personal Website",
  "I'm Noval Rialan",
  "a Software Engineer",
];
let i = 0;
let j = 0;
let currentWord = "";
let isDeleting = false;

function type() {
  currentWord = words[i];
  if (isDeleting) {
    document.getElementById("typewriter").textContent = currentWord.substring(
      0,
      j - 1
    );
    j--;
    if (j == 0) {
      isDeleting = false;
      i++;
      if (i == words.length) {
        i = 0;
      }
    }
  } else {
    document.getElementById("typewriter").textContent = currentWord.substring(
      0,
      j + 1
    );
    j++;
    if (j == currentWord.length) {
      isDeleting = true;
    }
  }
  setTimeout(type, 300);
}

// const observer = new IntersectionObserver((entires) => {
//   entires.forEach((entry) => {
//     console.log(entry);
//     if (entry.isIntersecting) {
//       entry.target.classList.add("show");
//     } else {
//       entry.target.classList.remove("show");
//     }
//   });
// });

// const hiddenElements = document.querySelectorAll(".hidden");
</script>



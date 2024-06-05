
<template>
  <br />
  <!-- Support Development services -->
  <div id="Supports">
    <h1 class="text-2xl md:text-1xl font-medium text-center">Supports</h1>
    <p class="font-bold text-4xl md:text-3xl text-center">
      Development services
    </p>
    <br />

    <!-- language Image -->
    <div class="flex items-center justify-center flex-wrap-reverse">
      <img
        width="100"
        height="110"
        src="https://img.icons8.com/color/122/java-coffee-cup-logo--v1.png"
        alt="java-coffee-cup-logo--v1"
      />

      <img
        width="100"
        height="120"
        src="https://img.icons8.com/external-those-icons-flat-those-icons/122/external-PHP-programming-and-development-those-icons-flat-those-icons.png"
        alt="external-PHP-programming-and-development-those-icons-flat-those-icons"
      />
      <img
        width="100"
        height="120"
        src="https://img.icons8.com/fluency/122/javascript.png"
        alt="javascript"
      />

      <img
        width="100"
        height="120"
        src="https://img.icons8.com/fluency/122/python.png"
        alt="python"
      />
      <img
        width="100"
        height="120"
        src="https://img.icons8.com/color/122/dart.png"
        alt="dart"
      />
      <img
        width="100"
        height="120"
        src="https://img.icons8.com/color/122/kotlin.png"
        alt="kotlin"
      />
    </div>
    <br />
    <div class="container mx-auto mb-10">
      <div class="content-separator"></div>
    </div>
  </div>

  <br />

  <Experience />

  <br />
  <div class="bg-black w-full h-60 p-10">
    <div class="container mx-auto p-5">
      <h1 class="text-white font-semibold text-4xl">
        Let's Discuss Careers and Technology
      </h1>

      <div class="flex flex-nowrap">
        <div class="container mx-auto text-2xl text-white p-0">
          Contact :
          <br />
        </div>

        <div>
          <a target="_blank" href="https://www.linkedin.com/in/noval-rialan"
            ><img
              width="115"
              height="120"
              src="https://img.icons8.com/3d-fluency/188/linkedin.png"
              alt="linkedin"
          /></a>
        </div>

        <div>
          <a href="https://www.github.com/novalrialan">
            <img
              width="115"
              height="120"
              src="https://img.icons8.com/color/144/github--v1.png"
              alt="github--v1"
            />
          </a>
        </div>
        <div>
          <a href="#Contact">
            <img
              width="115"
              height="120"
              src="https://img.icons8.com/3d-fluency/188/gmail.png"
              alt="gmail"
            />
          </a>
        </div>
      </div>
    </div>
  </div>
  <br class="mb-10" />
  <!-- dialog content center -->
  <section class="text-black hidden-con">
    <div id="Service" class="relative mx-auto text-center">
      <h2 class="text-2xl">Service Offering</h2>

      <h1
        class="mb-4 text-3xl font-extrabold leading-none tracking-tight text-gray-900 md:text-4xl lg:text-5xl dark:text-white"
      >
        Backend Service, Frontend Service
      </h1>
      <h1
        class="mb-4 text-3xl font-extrabold leading-none tracking-tight text-gray-900 md:text-4xl lg:text-5xl dark:text-white"
      >
        Monolith Service , Performance Testing API
      </h1>
      <p
        class="mb-20 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48 dark:text-gray-400"
      >
        I am ready to help procure development resources for your IT projects
        and application testing services
      </p>
    </div>
  </section>
  <!-- end dialog content center -->

  <!-- start content center -->
  <div>
    <CenterContaint />
  </div>
  <!-- end content center -->

  <div class="bg-[#F8FAFC] w-full mt-5 mb-20">
    <Tools />
  </div>
  <div id="Contact" class="contact">
    <Contact />
  </div>
</template>


<script setup>
import { onMounted } from "vue";
import Tools from "./sub-body/Tools.vue";
import Contact from "./sub-body/Contact.vue";
import Experience from "./sub-body/Experience.vue";
import CenterContaint from "./sub-body/CenterContaint.vue";

onMounted(() => {
  effect();
});

function effect() {
  const observer = new IntersectionObserver((entries) => {
    entries.forEach((entry) => {
      console.log(entry);
      if (entry.isIntersecting) {
        entry.target.classList.add("show");
      } else {
        entry.target.classList.remove("show");
      }
    });
  });
  const hiddenElements = document.querySelectorAll(".hidden-con");
  hiddenElements.forEach((el) => observer.observe(el));
}

let userHasScrolled = false;
let lastScrollY = window.scrollY;

// Fungsi yang akan dipanggil setiap interval waktu untuk memeriksa posisi scroll
function checkScroll() {
  if (window.scrollY !== lastScrollY) {
    userHasScrolled = true;

    lastScrollY = window.scrollY;
    console.log(
      `User has scrolled. Current scroll position: ${window.scrollY}`
    );
  } else {
    userHasScrolled = false;
  }
}

// Menambahkan event listener untuk mendeteksi scroll manual
window.onscroll = function (e) {
  userHasScrolled = true;
  lastScrollY = window.scrollY;
};

// Menjalankan checkScroll setiap 500 milidetik (0.5 detik)
setInterval(checkScroll, 500);
</script>

<template>
  <ul class="container mx-auto grid w-full gap-4 md:grid-cols-3 p-4">
    <li>
      <label
        data-tooltip-target="tooltip-default-fe-vjs"
        for="flowbite-option"
        class="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-blue-600 hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700"
      >
        <div class="block">
          <!-- <svg
            class="mb-2 text-green-400 w-7 h-7"
            fill="currentColor"
            aria-hidden="true"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 448 512"
          >
            <path
              d="M356.9 64.3H280l-56 88.6-48-88.6H0L224 448 448 64.3h-91.1zm-301.2 32h53.8L224 294.5 338.4 96.3h53.8L224 384.5 55.7 96.3z"
            />
          </svg> -->
          <img
            src="/src/assets/images/laravelicon.png"
            width="28"
            height="28"
            alt="laravel"
            srcset=""
          />
          <div class="w-full text-lg font-semibold">Laravel</div>
          <div class="w-full text-sm">
            Laravel aims to simplify common tasks in web projects such as
            routing, authentication, sessions, and caching, by providing
            efficient tools and resources. The framework follows the MVC
            (Model-View-Controller) architecture, facilitating the separation of
            application logic and user interface. With features like Eloquent
            ORM for database manipulation, schema migration, the Blade
            templating system, and a rich ecosystem of packages, Laravel enables
            developers to build applications that are powerful, scalable, and
            easy to maintain. Additionally, Laravel has a large community and
            good documentation, making it one of the most popular and widely
            used PHP frameworks in the world.
          </div>
        </div>
        <div
          id="tooltip-default-fe-vjs"
          role="tooltip"
          class="absolute z-10 invisible inline-block px-3 py-2 text-sm font-medium text-white transition-opacity duration-300 bg-gray-900 rounded-lg shadow-sm opacity-0 tooltip dark:bg-gray-700"
        >
          Laravel already
          <div class="tooltip-arrow" data-popper-arrow></div>
        </div>
      </label>
    </li>
    <li>
      <label
        data-tooltip-target="tooltip-default-fe-ajs"
        for="angular-option"
        class="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-blue-600 hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700"
      >
        <div class="block">
          <img
            src="/src/assets/images/springbooticon.png"
            width="28"
            height="28"
            alt="spring-boot"
            srcset=""
          />
          <div class="w-full text-lg font-semibold">Spring boot3</div>
          <div class="w-full text-sm">
            Spring Boot 3 is the latest version of the Spring Boot framework,
            designed to simplify the development of Spring-based Java
            applications by providing automatic configuration, efficient
            development tools, and ready-to-use setup. Spring Boot 3 supports
            Java 17, and includes performance improvements, security, and
            support for cloud-native development. This framework makes it easier
            to build microservice applications with better integration into the
            Spring ecosystem, including Spring Cloud and Spring Data. Features
            like Spring Boot Actuator for application monitoring, as well as
            easy configuration and dependency management, make Spring Boot 3 a
            top choice for developers looking to build powerful, scalable, and
            easy-to-maintain applications quickly.
          </div>
        </div>
        <div
          id="tooltip-default-fe-ajs"
          role="tooltip"
          class="absolute z-10 invisible inline-block px-3 py-2 text-sm font-medium text-white transition-opacity duration-300 bg-gray-900 rounded-lg shadow-sm opacity-0 tooltip dark:bg-gray-700"
        >
          Angular.js is still in the learning stage
          <div class="tooltip-arrow" data-popper-arrow></div>
        </div>
      </label>
    </li>
    <li>
      <!-- <input type="checkbox" id="react-option" value="" class="hidden peer" /> -->
      <label
        data-tooltip-target="tooltip-default-fe-rjs"
        for="react-option"
        class="inline-flex items-center justify-between w-full p-5 text-gray-500 bg-white border-2 border-gray-200 rounded-lg cursor-pointer dark:hover:text-gray-300 dark:border-gray-700 peer-checked:border-blue-600 hover:text-gray-600 dark:peer-checked:text-gray-300 peer-checked:text-gray-600 hover:bg-gray-50 dark:text-gray-400 dark:bg-gray-800 dark:hover:bg-gray-700"
      >
        <div class="block">
          <img
            src="/src/assets/images/laravellumenicon.png"
            width="28"
            height="28"
            alt="laravel-lumen"
            srcset=""
          />
          <div class="w-full text-lg font-semibold">Lumen</div>
          <div class="w-full text-sm">
            React is a JavaScript library developed by Facebook for building
            user interfaces. With its component-based approach, React makes it
            easy to manage and develop complex applications. React uses Virtual
            DOM to improve performance by only updating the parts that change.
            JSX syntax makes it easier to combine HTML elements in JavaScript
            code, making development more intuitive.
          </div>
        </div>
        <div
          id="tooltip-default-fe-rjs"
          role="tooltip"
          class="absolute z-10 invisible inline-block px-3 py-2 text-sm font-medium text-white transition-opacity duration-300 bg-gray-900 rounded-lg shadow-sm opacity-0 tooltip dark:bg-gray-700"
        >
          React.js is still in the learning stage
          <div class="tooltip-arrow" data-popper-arrow></div>
        </div>
      </label>
    </li>
  </ul>
</template>

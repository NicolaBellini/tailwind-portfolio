<script>
export default {};
</script>

<template>
  <div class="px-10 md:px-20 lg:px-40 dark:bg-slate-900 dark:text-white">
    <div class="h-screen min-h-screen">
      <nav class="pt-10 flex justify-between">
        <h1 class="text-xl font-thin">developedbyNic</h1>
        <ul class="flex items-center">
          <li @click="$emit('darkMode')">
            <i class="fa-solid fa-moon cursor-pointer text-xl dark:hidden"></i>
            <i
              class="fa-solid fa-sun cursor-pointer text-xl hidden dark:block"
            ></i>
          </li>
          <li>
            <a
              href=""
              class="bg-gradient-to-r from-cyan-500 to-teal-600 text-white px-4 py-2 rounded-lg ml-8"
              >resume</a
            >
          </li>
        </ul>
      </nav>
      <div class="text-center p-10 py-10">
        <h2 class="text-5xl py-2 text-teal-400 font-medium md:text-6xl">
          Nicola Bellini
        </h2>
        <h3 class="text-2xl py-2 md:text-3xl">Developer and Designer</h3>
        <p
          class="text-medium leading-8 text-gray-700 md:text-xl max-w-xl mx-auto dark:text-white"
        >
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo,
          eaque. Lorem ipsum dolor, sit amet consectetur adipisicing elit.
          Autem, exercitationem.
        </p>
      </div>
      <div
        class="text-3xl flex justify-center gap-12 text-gray-500 mb-4 dark:text-white"
      >
        <a href="https://www.linkedin.com/in/nicola-bellini-2b0369312/"
          ><i class="fa-brands fa-linkedin"></i
        ></a>
        <a href="https://github.com/NicolaBellini"
          ><i class="fa-brands fa-github"></i
        ></a>
      </div>
      <div
        class="bg-gradient-to-b mx-auto from-teal-500 rounded-full w-80 h-80 overflow-hidden mt-14 md:h-96 md:w-96"
      >
        <img src="/dev-ed-wave.png" class="h-full object-cover" alt="" />
      </div>
    </div>
  </div>
</template>

<style></style>

<template>
  <main>
    <footer class="relative px-4 xl:px-56 py-16 lg:py-48 brightness-125">
      <img src="/img/porto-2.jpg" class="w-full h-full object-cover absolute top-0 left-0 -z-10 opacity-30 shadow-inner shadow-secondary"/>
    <main class="flex items-start flex-col lg:flex-row justify-center gap-6 xl:gap-11 w-full z-30 text-base md:text-xl">
      <section class="order-1 w-full lg:w-1/5 xl:w-1/3 flex flex-col items-center lg:items-start">
        <h2 class="text-xl md:text-2xl">QUICK LINK <br/>
          <div class="h-1 w-14 mt-2 bg-primary"></div>
        </h2>
        <ul class="pl-0 md:pl-4 flex flex-row lg:flex-col gap-2 md:gap-7 pt-4">
          <li class="list-none lg:list-disc">Home</li>
          <li class="list-none lg:list-disc">About</li>
          <li class="list-none lg:list-disc">Services</li>
          <li class="list-none lg:list-disc">Portfolio</li>
          <li class="list-none lg:list-disc">Contact</li>
        </ul>
      </section>
      <section class="order-2 w-full lg:w-1/5 xl:w-1/3 flex flex-col items-center lg:items-start">
        <h2 class="text-xl md:text-2xl">SUPPORT :<br/>
          <div class="w-16 h-1 bg-primary mt-2"></div>
        </h2>
        <ul class="flex flex-row lg:flex-col gap-2 md:gap-7 pt-4 pl-0 md:pl-4">
          <li class="list-none lg:list-disc">FAQ</li>
          <li class="list-none lg:list-disc">Employment</li>
          <li class="list-none lg:list-disc">Request A Quote</li>
        </ul>
      </section>
      <section class="order-5 lg:order-3 flex flex-col items-center w-1/3 h-full self-center lg:hidden xl:flex">
        <img src="~/assets/images/logo.png" alt="logo" width="1000" class="w-96"/>
        <ul class="flex gap-4">
          <li><Icon name="mdi:facebook" class="text-3xl"/></li>
          <li><Icon name="mdi:pinterest" class="text-3xl"/></li>
          <li><Icon name="mdi:instagram" class="text-3xl"/></li>
        </ul>
      </section>
      <section class="order-3 lg:order-4 w-full lg:w-1/5 xl:w-1/3  flex flex-col items-center lg:items-start">
        <h2 class="text-xl md:text-2xl">MORE INFO<br/>
          <div class="w-14 h-1 bg-primary mt-2"></div>
        </h2>
        <ul class="flex flex-row lg:flex-col gap-7 pt-4 pl-0 lg:pl-4">
          <li class="list-none lg:list-disc">News</li>
          <li class="list-none lg:list-disc">Media</li>
          <li class="list-none lg:list-disc">Videos</li>
          <li class="list-none lg:list-disc">Blog</li>
        </ul>
      </section>
      <section class="order-4 lg:order-5 w-full lg:w-1/5 xl:w-1/3 flex flex-col items-center lg:items-start">
        <h2 class="text-xl md:text-2xl">CONTACT<br/>
          <div class="w-20 h-1 bg-primary mt-2"></div>
        </h2>
        <ul class="flex flex-col gap-7 pt-4 ">
          <li class="flex items-center lg:items-start gap-2 flex-col lg:flex-row">
            <Icon name="mdi:location" class="text-2xl lg:text-5xl"/>
            <p class="lg:text-left text-center">105059 Schoger Dr. Unit 23 Nopeville, JL 60564</p>
          </li>
          <li class="flex items-center lg:items-start gap-2 flex-col lg:flex-row">
            <Icon name="mdi:email" class="text-xl"/>
            <p>sales@myguysknowyou.com</p>
          </li>
        </ul>
      </section>
    </main>
  </footer>
  <div class="bg-secondary w-full h-20 flex items-center justify-center py-8">
    <p class="text-white text-xs md:text-xl">&copy; 2023 <span class="text-primary">MY GUYS KNOW YOU</span>. ALL RIGHTS RESERVED</p>
  </div>
</main>
</template>

<style scoped>
footer::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 500px;
  background: linear-gradient(to top, rgba(255, 255, 255, 0) 0%, rgba(255, 255, 255, 1) 100%);
  top: 0;
  left: 0;
  pointer-events: none;
  z-index: -1;
}
</style>

<script setup>
const productLinks = ["Product", "Features", "Pricing", "Changelog", "Support"];
const legalLinks = ["Legal", "Terms of Privacy", "Privacy Policy", "Security"];
const companyLinks = ["Company", "Blog", "Contact"];
const socialLinks = ["Social", "Dribbble", "Behance", "Discord"];
</script>
<template>
  <div
    class="px-4 lg:px-[200px] pt-5 space-y-6 lg:flex lg:gap-30 max-w-[1240px] align-center"
  >
    <div>
      <img src="../assets/images/BoxOrangeSmall.png" alt="" />
    </div>
    <div class="flex flex-col gap-5 lg:flex-row lg:gap-30">
      <div class="flex flex-col gap-1">
        <div v-for="(productLink, index) in productLinks">
          <p class="text-sm font-bold" v-if="index === 0">{{ productLink }}</p>
          <a class="text-sm text-[#5F6980]" v-else href="">{{ productLink }}</a>
        </div>
      </div>
      <div class="flex flex-col gap-1">
        <div v-for="(legalLink, index) in legalLinks">
          <p class="text-sm font-bold" v-if="index === 0">{{ legalLink }}</p>
          <a class="text-sm text-[#5F6980]" v-else href="">{{ legalLink }}</a>
        </div>
      </div>
      <div class="flex flex-col gap-1">
        <div v-for="(companyLink, index) in companyLinks">
          <p class="text-sm font-bold" v-if="index === 0">{{ companyLink }}</p>
          <a class="text-sm text-[#5F6980]" v-else href="">{{ companyLink }}</a>
        </div>
      </div>
      <div class="flex flex-col gap-1">
        <div v-for="(socialLink, index) in socialLinks">
          <p class="text-sm font-bold" v-if="index === 0">{{ socialLink }}</p>
          <a class="text-sm text-[#5F6980]" v-else href="">{{ socialLink }}</a>
        </div>
      </div>
    </div>
  </div>

  <div class="p-12">
    <p class="text-sm text-[#5F6980]">
      All rights reserved.© 2024 DejectStudio
    </p>
  </div>
</template>

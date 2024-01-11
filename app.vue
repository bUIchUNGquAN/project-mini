<template>
  <div>
    <header class="bg-white">
      <nav class="w-full mx-auto flex max-w-7x1 p-6 lg:px-8">
        <div class="flex items-center justify-center space-x-4 text-left">
          <a href="#" class="-m-1.5 p-1.5">
            <img
              class="h-12 w-auto rounded-lg"
              src="https://technewsdaily.vn/uploads/2021/10/14/Eimi-Fukada-1-696x503.jpg"
              alt=""
            />
          </a>
          <div
            class="flex inline-flex grid grid-cols-5 items-center justify-items-center"
          >
            <div class="justify-between mx-7 flex">
              <UButton
                size="sm"
                color="white"
                variant="ghost"
                class="inline-flex rounded-md p-2.5 dark:text-white"
              >
                <UIcon name="i-bx-caret-left" class="h-6 w-6" dynamic></UIcon>
              </UButton>
              <UButton
                size="sm"
                color="white"
                variant="ghost"
                class="inline-flex rounded-md p-2.5 dark:text-white"
              >
                <UIcon name="i-bx-caret-right" class="h-6 w-6" dynamic></UIcon>
              </UButton>
            </div>

            <div class="mx-7 flex">
              <UInput
                size="xl"
                placeholder="search"
                icon="i-heroicons-magnifying-glass-20-solid"
              ></UInput>
            </div>
            <div class="mx-7 flex">
              <UButton
                size="xl"
                color="white"
                variant="ghost"
                class="inline-flex rounded-md p-2.5 dark:text-white"
              >
                <UIcon name="i-bx-wallet" class="h-6 w-6" dynamic> </UIcon
                >32023.3$
              </UButton>
            </div>
            <div class="justify-between mx-7 flex inline-flex grid grid-cols-3">
              <div class="items-center flex-cols">
                <UButton
                  size="xl"
                  color="white"
                  variant="ghost"
                  class="rounded-md p-2.5 dark:text-white"
                >
                  <UIcon name="i-bx-baguette" class="h-6 w-6" dynamic> </UIcon>
                </UButton>
              </div>
              <div class="items-center flex-cols">
                <UButton
                  size="xl"
                  color="white"
                  variant="ghost"
                  class="rounded-md p-2.5 dark:text-white"
                >
                  <UIcon name="i-bx-message-dots" class="h-6 w-6" dynamic>
                  </UIcon>
                </UButton>
              </div>
              <div class="items-center flex-cols">
                <UButton
                  size="xl"
                  color="white"
                  variant="ghost"
                  class="rounded-md p-2.5 dark:text-white"
                >
                  <UIcon name="i-bxs-bell" class="h-6 w-6" dynamic> </UIcon>
                </UButton>
              </div>
            </div>

            <div class="flex items-center justify-center space-x-4 text-left">
              <UAvatar
                size="lg"
                chip-color="primary"
                chip-position="top-right"
                src="https://technewsdaily.vn/uploads/2021/10/14/Eimi-Fukada-1-696x503.jpg"
              />
              <p class="text-slate-900 font-semibold dark:text-white">
                Quan chung
              </p>
            </div>
          </div>
        </div>
      </nav>
    </header>
  </div>
  <!-- contet -->
  <div class="bg-gray-100 flex flex-cols">
    <!-- sidebar -->
    <nav class="w-1/16 h-screen flex max-w-7x1 p-6 lg:px-8 bg-red-100">
      <div class="mt-6 flex flex-col">
        <div class="border-b border-gray-900/10 pb-12">
          <div class="flex items-center justify-center space-x-4">
            <UButton
              size="xl"
              color="white"
              variant="ghost"
              class="rouded-md p-2.5 dark:text-white"
            >
              <UIcon name="i-bx-home-alt" class="h-6 w-6" dynamic />
            </UButton>
          </div>
          <div class="flex items-center justify-center space-x-4">
            <UButton
              size="xl"
              color="white"
              variant="ghost"
              class="rouded-md p-2.5 dark:text-white"
            >
              <UIcon name="i-bx-game" class="h-6 w-6" dynamic />
            </UButton>
          </div>
          <div class="flex items-center justify-center space-x-4">
            <UButton
              size="xl"
              color="white"
              variant="ghost"
              class="rouded-md p-2.5 dark:text-white"
            >
              <UIcon name="i-bx-lemon" class="h-6 w-6" dynamic />
            </UButton>
          </div>
          <div class="flex items-center justify-center space-x-4">
            <UButton
              size="xl"
              color="white"
              variant="ghost"
              class="rouded-md p-2.5 dark:text-white"
            >
              <UIcon name="i-bxs-leaf" class="h-6 w-6" dynamic />
            </UButton>
          </div>
          <div class="flex items-center justify-center space-x-4">
            <UButton
              size="xl"
              color="white"
              variant="ghost"
              class="rouded-md p-2.5 dark:text-white"
            >
              <UIcon name="i-bxl-flutter" class="h-6 w-6" dynamic />
            </UButton>
          </div>
        </div>
        <div class="flex items-center justify-center space-x-4">
          <UButton
            size="xl"
            color="white"
            variant="ghost"
            class="rouded-md p-2.5 dark:text-white"
          >
            <UIcon name="i-bx-home-alt" class="h-6 w-6" dynamic />
          </UButton>
        </div>
        <div class="flex items-center justify-center space-x-4">
          <UButton
            size="xl"
            color="white"
            variant="ghost"
            class="rouded-md p-2.5 dark:text-white"
          >
            <UIcon name="i-bx-game" class="h-6 w-6" dynamic />
          </UButton>
        </div>
        <div class="flex items-center justify-center space-x-4">
          <UButton
            size="xl"
            color="white"
            variant="ghost"
            class="rouded-md p-2.5 dark:text-white"
          >
            <UIcon name="i-bx-lemon" class="h-6 w-6" dynamic />
          </UButton>
        </div>
      </div>
    </nav>
    <!-- about -->
    <nav class="w-3/4 flex max-w-7x1 p-6 lg:px-8 bg-red-200">
      <div class="grid grid-rows-2 items-center justify-betwenn flex">
        <div class="flex items-center justify-center space-x-4 text-left">
          <img
            class="rounded-lg w-screen h-56"
            src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
            alt=""
          />
        </div>
        <div class="flex space-x-4 text-left">
          <p class="font-semibold text-gray-900 size-20">mygame</p>
          <div class="flex grid grid-cols-6 scroll-ml-6 gap-x-6 items-center">
            <div class="">
              <img
                src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </nav>
    <!-- sidebar2 -->
    <nav class="w-1/6 flex max-w-7x1 p-6 lg:px-8 bg-red-300">
      <div class="mt-6 flex flex-col">
        <div class="border-b border-gray-900/10 pb-12">
          <p class="text-gray-900 font-semibold lg:text-lg">Frieen onlien</p>
          <div class="rounded-lg shadow-2xl snap-y">
            <div class="flex justify-between gap-x-6 py-5 snap-always">
              <div class="flex min-w-0 gap-x-4">
                <img
                  class="h-12 w-12 flex-none rounded-lg bg-gray-50"
                  src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                  alt=""
                />
                <div class="min-w-0 flex-auto">
                  <p class="font-semibold text-gray-900 text-sm">Quan</p>
                  <p class="font-semibold text-gray-900 text-xs mt-1">apex</p>
                </div>
                <div class="hidden shrink-0 sm:flex sm:flex-col sm:items-end">
                  <div class="min-w-0 flex-auto">
                    <UButton size="sm" class=""></UButton>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex justify-between gap-x-6 py-5">
              <div class="flex min-w-0 gap-x-4">
                <img
                  class="h-12 w-12 flex-none rounded-lg bg-gray-50"
                  src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                  alt=""
                />
                <div class="min-w-0 flex-auto">
                  <p class="font-semibold text-gray-900 text-sm">Quan</p>
                  <p class="font-semibold text-gray-900 text-xs mt-1">apex</p>
                </div>
              </div>
            </div>
            <div class="flex justify-between gap-x-6 py-5">
              <div v class="flex min-w-0 gap-x-4">
                <img
                  class="h-12 w-12 flex-none rounded-lg bg-gray-50"
                  src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                  alt=""
                />
                <div class="min-w-0 flex-auto">
                  <p class="font-semibold text-gray-900 text-sm">Quan</p>
                  <p class="font-semibold text-gray-900 text-xs mt-1">apex</p>
                </div>
              </div>
              <div class="hidden shrink-0 sm:flex sm:flex-col sm:items-end">
                <div class="min-w-0 flex-auto">
                  <UButton size="sm" class=""></UButton>
                </div>
              </div>
            </div>
          </div>
          <div class="rounded-lg shadow-2xl snap-y">
            <div class="flex justify-between gap-x-6 py-5 snap-always">
              <div class="flex min-w-0 gap-x-4">
                <img
                  class="h-12 w-12 flex-none rounded-lg bg-gray-50"
                  src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                  alt=""
                />
                <div class="min-w-0 flex-auto">
                  <p class="font-semibold text-gray-900 text-sm">Quan</p>
                  <p class="font-semibold text-gray-900 text-xs mt-1">apex</p>
                </div>
                <div class="hidden shrink-0 sm:flex sm:flex-col sm:items-end">
                  <div class="min-w-0 flex-auto">
                    <UButton size="sm" class=""></UButton>
                  </div>
                </div>
              </div>
            </div>
            <div class="flex justify-between gap-x-6 py-5">
              <div class="flex min-w-0 gap-x-4">
                <img
                  class="h-12 w-12 flex-none rounded-lg bg-gray-50"
                  src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                  alt=""
                />
                <div class="min-w-0 flex-auto">
                  <p class="font-semibold text-gray-900 text-sm">Quan</p>
                  <p class="font-semibold text-gray-900 text-xs mt-1">apex</p>
                </div>
              </div>
            </div>
            <div class="flex justify-between gap-x-6 py-5">
              <div v class="flex min-w-0 gap-x-4">
                <img
                  class="h-12 w-12 flex-none rounded-lg bg-gray-50"
                  src="https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg"
                  alt=""
                />
                <div class="min-w-0 flex-auto">
                  <p class="font-semibold text-gray-900 text-sm">Quan</p>
                  <p class="font-semibold text-gray-900 text-xs mt-1">apex</p>
                </div>
              </div>
              <div class="hidden shrink-0 sm:flex sm:flex-col sm:items-end">
                <div class="min-w-0 flex-auto">
                  <UButton size="sm" class=""></UButton>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script setup>
// const list = ref([
//   {
//     id:1,
//   name:Quan,
//   title:Apex,
//   imageUrl:'https://photo.znews.vn/w960/Uploaded/ygtmvd/2023_02_23/FmaZHbIacAE_qMT.jpg',
//   lastSeen:null
// },
// {
//   id:2,
//   name:bi,
//   title:Apex,
//   imageUrl:'https://we25.vn/media2018/Img_News/2023/02/23/2_20230223163204.jpg',
//   lastSeen:null
// },
// {
//   id:3,
//   name:bun,
//   title:Apex,
//   imageUrl:'https://technewsdaily.vn/uploads/2023/01/20/f-14.jpg  ',
//   lastSeen:null
// },
// ])
</script>

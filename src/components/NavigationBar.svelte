<nav class="w-full flex justify-between py-2 items-center border-black border-b-[2px]">
  <div class="ml-4">
    <div on:click={() => window.location.href = '/'} class="flex flex-col items-center justify-center cursor-pointer">
      <img src="/icons/placeholder-icon.svg" alt="placeholder icon" class="h-[30px]" />
      <p class="text-sm">Logo</p>
    </div>
  </div>
  <ul class="flex mx-4">
    <li class="mx-4 px-2">
      <div on:click={() => window.location.href = './design'} class="hover:border-b-[1px] border-black cursor-pointer">Design</div>
    </li>
    <li class="mx-4 px-2">
      <div on:click={() => window.location.href = './publishing'} class="hover:border-b-[1px] border-black cursor-pointer">Publishing</div>
    </li>
    <li class="mx-4 px-2">
      <div on:click={() => window.location.href = './profile'} class="hover:border-b-[1px] border-black cursor-pointer">Profile</div>
    </li>
  </ul>
</nav>
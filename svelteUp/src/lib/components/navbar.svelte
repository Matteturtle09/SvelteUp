<script>
  import ThemeChangeButton from "./themeChangeButton.svelte";
</script>

<div class="navbar bg-base-100 shadow-sm ">
  <div class="flex-1">
    <a class="btn btn-ghost text-xl">Navbar</a>
  </div>
  <div class="flex-none mx-4">
    <ThemeChangeButton />
  </div>
  <div class="flex-none">
    <button class="btn btn-primary h-12"> Login </button>
  </div>
</div>

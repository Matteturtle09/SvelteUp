<script>
    export let imageSrc;
    export let mainTitle;
    export let description;
</script>

<div class="hero min-h-screen" style="background-image: url({imageSrc});">
    <div class="hero-overlay bg-opacity-60"></div>
    <div class="hero-content text-center text-neutral-content">
      <div class="max-w-md">
        <h1 class="mb-5 text-5xl font-bold">{mainTitle}</h1>
        <p class="mb-5">{description}</p>
      </div>
    </div>
  </div>
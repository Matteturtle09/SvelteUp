<script>
  import { onMount } from "svelte";
  import { themeChange } from "theme-change";
  onMount(() => {
    themeChange(false);
    // 👆 false parameter is required for svelte
  });
</script>

<button class="btn btn-square btn-outline btn-primary" data-toggle-theme="dark,light" data-act-class="ACTIVECLASS">
    <svg xmlns="http://www.w3.org/2000/svg" class="m-2" viewBox="0 0 24 24" id="Layer_1" data-name="Layer 1">
        <defs>
          <style>
            .cls-1 {
              fill: none;
              stroke: currentColor; /* Set stroke color to current color */
              stroke-miterlimit: 10;
              stroke-width: 1.91px;
            }
          </style>
        </defs>
        <circle class="cls-1" cx="12" cy="12" r="10.5"/>
        <path class="cls-1" d="M8.66,22A10.51,10.51,0,0,0,8.66,2"/>
      </svg>
      </button>

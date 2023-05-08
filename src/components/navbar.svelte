<script>
  //   import imgUrl from "../assets/logo.png";
  import Whatsapp from "./whatsapp.svelte";
  import { onMount } from "svelte";

  import { themeChange } from "theme-change";

  // NOTE: the element that is using one of the theme attributes must be in the DOM on mount
  onMount(() => {
    themeChange(false);
    // 👆 false parameter is required for svelte
  });
</script>

<div class="navbar fixed bg-base-100 z-40">
  <div class="navbar-start">
    <!-- Hamburguer menu -->
    <div class="dropdown">
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          ><path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h8m-8 6h16"
          /></svg
        >
      </label>
      <!-- svelte-ignore a11y-no-noninteractive-tabindex -->
      <ul
        tabindex="0"
        class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
      >
        <li>
          <a data-sveltekit-reload href="#inicio">Inicio</a>
        </li>
        <li>
          <a href="#sobre">Sobre</a>
        </li>
        <li>
          <a href="#consulta">Consulta</a>
        </li>

        <li>
          <a href="#contato">Contato</a>
        </li>
      </ul>
    </div>
    <a href="/">
      <!-- <img class="mask mask-circle" src={imgUrl} width="50" alt="mask" /> -->
    </a>
  </div>

  <div class="navbar-center hidden lg:flex">
    <ul class="menu menu-horizontal p-0">
      <li>
        <a data-sveltekit-reload href="#inicio">Inicio</a>
      </li>
      <li>
        <a href="#sobre">Sobre</a>
      </li>
      <li>
        <a href="#consulta">Consulta</a>
      </li>
      <li>
        <a href="#contato">Contato</a>
      </li>
    </ul>
    <div class="pl-10">
      <Whatsapp />
    </div>
    <div class="mx-4">
      <select
        name="themes"
        id="themes"
        data-choose-theme
        class="select select-ghost w-full max-w-xs"
      >
        <option value="light">Default</option>
        <option value="dark">Dark</option>
        <option value="cupcake">Cupcake</option>
        <option value="bumblebee">Bumblebee</option>
        <option value="emerald">Emerald</option>
        <option value="corporate">Corporate</option>
        <option value="synthwave">Synthwave</option>
        <option value="retro">Retro</option>
        <option value="cyberpunk">Cyberpunk</option>
        <option value="valentine">Valentine</option>
        <option value="halloween">Halloween</option>
        <option value="garden">Garden</option>
        <option value="forest">Forest</option>
        <option value="aqua">Aqua</option>
        <option value="lofi">Lofi</option>
        <option value="pastel">Pastel</option>
        <option value="fantasy">Fantasy</option>
        <option value="wireframe">Wireframe</option>
        <option value="black">Black</option>
        <option value="luxury">Luxury</option>
        <option value="dracula">Dracula</option>
        <option value="cmyk">CMYK</option>
        <option value="autumn">Autumn</option>
        <option value="business">Business</option>
        <option value="acid">Acid</option>
        <option value="lemonade">Lemonade</option>
        <option value="night">Night</option>
        <option value="coffee">Coffee</option>
        <option value="winter">Winter</option>
      </select>
    </div>
  </div>
  <div class="navbar-end" />
</div>

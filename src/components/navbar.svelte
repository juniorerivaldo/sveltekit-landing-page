<script>
//   import imgUrl from "../assets/logo.png";
import Whatsapp from "./whatsapp.svelte";
  import { page } from "$app/stores";
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
          <a href="#servicos">Serviços</a>
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
        <a href="#servicos">Serviços</a>
      </li>
      <li>
        <a href="#contato">Contato</a>
      </li>
    </ul>
    <div class="pl-10">
			<Whatsapp />
		</div>
  </div>
  <div class="navbar-end" />
</div>

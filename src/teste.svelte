<script>
  import Whatsapp from "../../components/whatsapp.svelte";
</script>

<div class="hero min-h-screen bg-secondary" id="inicio">
  <div class="hero-content flex-col lg:flex-row">
    <div class="container mx-auto py-9 md:py-12 lg:py-24">
      <div class="flex flex-col lg:flex-row justify-center items-strech mx-4">
      <h3 class="text-5xl md:text-5xl xl:text-5xl font-bold text-center">
        Como funciona a consulta
      </h3>
      <div class="grid grid-cols-1 md:lg:xl:grid-cols-4 group">
        <div class="p-10 flex flex-col items-center text-center group  hover:bg-base-300 cursor-pointer hover:scale-105">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
              <svg
                class="h-10 w-10 bg-secondary rounded-full"
                fill="none"
                stroke="currentColor"
                stroke-width="1.5"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <h2 class="card-title text-3xl font-semibold py-5">Sessões</h2>
              <p>Sessões com 50 minutos de duração.</p>
            </div>
          </div>
        </div>
        <div class="p-10 flex flex-col items-center text-center group  hover:bg-base-300 cursor-pointer hover:scale-105">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
              <svg
                class="h-10 w-10 bg-secondary rounded-full"
                fill="none"
                stroke="currentColor"
                stroke-width="1.5"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <h2 class="card-title text-3xl font-semibold py-5">Frequência</h2>
              <p>Sessões semanais, quinzenais ou mensais.</p>
            </div>
          </div>
        </div>
        <div class="p-10 flex flex-col items-center text-center group  hover:bg-base-300 cursor-pointer hover:scale-105">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
              <svg
                class="h-10 w-10 bg-secondary rounded-full"
                fill="none"
                stroke="currentColor"
                stroke-width="1.5"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <h2 class="card-title text-3xl font-semibold py-5">Local</h2>
              <p>Atendimento presencial ou online.</p>
            </div>
          </div>
        </div>
        <div class="p-10 flex flex-col items-center text-center group  hover:bg-base-300 cursor-pointer hover:scale-105">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
              <svg
                class="h-10 w-10 bg-secondary rounded-full"
                fill="none"
                stroke="currentColor"
                stroke-width="1.5"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <h2 class="card-title text-3xl font-semibold py-5">Pagamento</h2>
              <p>Atendimento particular ou por convênio.</p>
            </div>
          </div>
        </div>
      </div>
      <h3
        class="text-2xl md:text-2xl xl:text-2xl font-semibold text-center py-3"
      >
        Clique no botão abaixo e agende sua consulta comigo!
      </h3>
      <div class="py-9 mt-5 flex items-center justify-center">
        <Whatsapp />
      </div>
    </div>
  </div>
</div>
</div>

<script>
  import Whatsapp from "../../components/whatsapp.svelte";
</script>

<div class="hero min-h-screen bg-base-200" id="consulta">
  <div class="hero-content flex-col lg:flex-row">
    <div class="container mx-auto py-9 md:py-12 lg:py-24">
      <div class="flex flex-col lg:flex-row justify-center mx-4">
            <div class="py-5 max-w-screen-lg">
              <h3 class="text-5xl md:text-5xl xl:text-5xl font-bold text-center">
                Como funciona a consulta
              </h3>
              <div class="grid sm:grid-cols-2 gap-9 py-12 mt-10">
                <div class="flex items-center space-x-2">
                
                <div class="card sm:w-96 bg-base-100 shadow-xl space-x-2 w-full">
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
                <div class="flex items-center space-x-2">
                  <div class="card sm:w-96 bg-base-100 shadow-xl space-x-2 w-full">
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
                      <h2 class="card-title text-3xl font-semibold py-5">
                        Frequência
                      </h2>
                      <p>Sessões semanais, quinzenais ou mensais.</p>
                    </div>
                  </div>
                </div>
                <div class="flex items-center space-x-2">
                  <div class="card sm:w-96 bg-base-100 shadow-xl space-x-2 w-full">
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
                <div class="flex items-center space-x-2">
                  <div class="card sm:w-96 bg-base-100 shadow-xl space-x-2">
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
                      <h2 class="card-title text-3xl font-semibold py-5">
                        Pagamento
                      </h2>
                      <p>Atendimento particular ou por convênio.</p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="py-6 mt-10 flex-auto">
                <h3
                  class="text-2xl md:text-2xl xl:text-2xl font-semibold text-center py-3"
                >
                Clique no botão abaixo e agende sua consulta comigo!
                </h3>
              </div>
              <div class="flex justify-center items-center py-6">
                <Whatsapp />
              </div>
            </div>
          </div>
        </div>
  </div>
</div>

<script>
  import imgUrl1 from "../assets/profile1.jpg";
  import imgUrl2 from "../assets/profile2.jpg";
  import Whatsapp from "../components/whatsapp.svelte";
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="PSICO INSTITUCIONAL" />
</svelte:head>
<main>
  <!-- INICIO -->
  <div class="hero min-h-screen bg-secondary" id="inicio">
    <div class="hero-content flex-col lg:flex-row">
      <div class="container mx-auto py-9 md:py-12 lg:py-24">
        <div class="flex flex-col lg:flex-row justify-center items-strech mx-4">
          <div class="lg:w-6/12 flex justify-center items-center">
            <div class="py-5">
              <h3 class="text-4xl md:text-5xl xl:text-4xl font-bold">
                Encontre a solução para seus problemas emocionais com a ajuda de
                um psicólogo especialista
              </h3>
              <div class="mt-2">
                <span class="inline-block w-40 h-1 rounded-full bg-green-500" />
                <span
                  class="inline-block w-3 h-1 ml-1 rounded-full bg-green-500"
                />
                <span
                  class="inline-block w-1 h-1 ml-1 rounded-full bg-green-500"
                />
              </div>
              <p
                class="   md:w-7/12 lg:w-11/12 xl:w-10/12 mt-4 lg:mt-5 text-base leading-normal font-semibold"
              >
                Tenha ao seu lado um profissional capacitado para você falar
                sobre seus medos, angústias e aflições e busque alívio através
                de um processo terapêutico
              </p>
              <div class="py-9 mt-5 flex-auto">
                <Whatsapp />
              </div>
            </div>
          </div>
          <div class="lg:w-8/12 mt-6 md:mt-8 lg:mt-0 px-7">
            <div class="relative w-full h-full ml-10 lg:justify-center">
              <img
                src={imgUrl1}
                alt="home pic"
                width="427"
                class="rounded-xl hover:scale-105"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- INFO -->
  <div class="hero min-h-4/5 bg-base-200">
    <div class="hero-content flex-col lg:flex-row">
      <div class="py-5 max-w-screen-lg">
        <h3 class="text-4xl md:text-5xl xl:text-4xl font-bold">
          Se você esta passando por um desses problemas:
        </h3>
        <div class="grid sm:grid-cols-2 gap-4 py-12 mt-10">
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Ansiedade</span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Angústia</span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Alterações de humor</span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Transtornos de personalidade </span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl"
              >Dificuldade na tomada de decisões
            </span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Sentimento de solidão constante </span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Depressão </span>
          </div>
          <div class="flex items-left items-center">
            <svg
              class="h-6 w-6 font-bold"
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
                d="M11.25 4.5l7.5 7.5-7.5 7.5m-6-15l7.5 7.5-7.5 7.5"
              />
            </svg>
            <span class="ml-2 text-2xl">Autoestima e medos </span>
          </div>
        </div>
        <div class="py-6 mt-10 flex-auto">
          <h3
            class="text-2xl md:text-2xl xl:text-2xl font-semibold text-center"
          >
            Um psicólogo pode te ajudar e você está no lugar certo!
          </h3>
        </div>
        <div class="flex justify-center items-center py-6">
          <Whatsapp />
        </div>
      </div>
    </div>
  </div>
  <!-- SOBRE-->
  <div
    class="hero min-h-screen bg-gradient-to-l from-secondary to-base-200"
    id="sobre"
  >
    <div class="hero-content flex-col lg:flex-row">
      <div class="lg:w-10/12 mt-6 md:mt-8 lg:mt-0 px-7">
        <img
          src={imgUrl2}
          alt="home pic"
          class="rounded-s-full hover:scale-105"
        />
      </div>
      <div class="container mx-auto py-9 md:py-12 lg:py-24">
        <div class="flex flex-col lg:flex-row justify-center items-strech mx-4">
          <div class="lg:w-10/12 flex justify-center items-center">
            <div>
              <h3 class="text-3xl md:text-5xl xl:text-4xl font-semibold">
                Um pouco sobre o psicólogo
              </h3>
              <p
                class="   md:w-7/12 lg:w-11/12 xl:w-10/12 mt-4 lg:mt-5 text-base leading-normal font-semibold"
              >
                Bernardo é um psicólogo altamente experiente com mais de 10 anos
                de atuação na área. Durante sua carreira, ele tem ajudado
                inúmeras pessoas a lidar com seus problemas emocionais, mentais
                e comportamentais.<br /><br />
                Com sua ampla experiência, Bernardo é capaz de compreender os desafios
                enfrentados por cada indivíduo que procura sua ajuda, independentemente
                do contexto. Ele tem trabalhado com pessoas de todas as idades, gêneros
                e origens, o que lhe proporcionou uma visão abrangente e profunda
                das diversas dinâmicas psicológicas que podem afetar as pessoas.
                <br /><br />
                Bernardo possui uma abordagem terapêutica centrada no cliente, que
                visa criar um ambiente seguro e acolhedor para seus pacientes. Ele
                valoriza a empatia, a escuta ativa e a compreensão da perspectiva
                do paciente, a fim de ajudá-lo a explorar suas emoções e comportamentos
                de maneira efetiva. <br /><br />
              </p>
              <div class="py-9 mt-5 flex-auto">
                <Whatsapp />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- SERVICOS -->
  <div class="hero min-h-screen bg-base-200" id="consulta">
	
    <div class="hero-content flex-col lg:flex-row">
		<div class="py-5 max-w-screen-lg">
        <h3 class="text-5xl md:text-5xl xl:text-5xl font-bold text-center">
         Como funciona a consulta
        </h3>
      <div class="grid sm:grid-cols-4 gap-9">
        <div class="flex items-center space-x-2 py-14">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
				<svg class="h-10 w-10 bg-secondary rounded-full" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
</svg>
              <h2 class="card-title text-3xl font-semibold">Atendimento Humanizado</h2>
              <p>If a dog chews shoes whose shoes does he choose?</p>
              <div class="card-actions justify-end">
                <button class="btn btn-primary">Buy Now</button>
              </div>
            </div>
          </div>
        </div>
		  <div class="flex items-center space-x-2">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
				<svg class="h-10 w-10 bg-secondary rounded-full" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
</svg>
              <h2 class="card-title text-3xl font-semibold">Card title!</h2>
              <p>If a dog chews shoes whose shoes does he choose?</p>
              <div class="card-actions justify-end">
                <button class="btn btn-primary">Buy Now</button>
              </div>
            </div>
          </div>
        </div>
		  <div class="flex items-center space-x-2">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
				<svg class="h-10 w-10 bg-secondary rounded-full" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
</svg>
              <h2 class="card-title text-3xl font-semibold">Card title!</h2>
              <p>If a dog chews shoes whose shoes does he choose?</p>
              <div class="card-actions justify-end">
                <button class="btn btn-primary">Buy Now</button>
              </div>
            </div>
          </div>
        </div>
		  <div class="flex items-center space-x-2">
          <div class="card w-96 bg-base-100 shadow-xl space-x-2">
            <div class="card-body">
				<svg class="h-10 w-10 bg-secondary rounded-full" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75L11.25 15 15 9.75M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
</svg>
              <h2 class="card-title text-3xl font-semibold">Card title!</h2>
              <p>If a dog chews shoes whose shoes does he choose?</p>
              <div class="card-actions justify-end">
                <button class="btn btn-primary">Buy Now</button>
              </div>
            </div>
          </div>
        </div>
        </div>
      </div>
    </div>
  </div>
  <!-- CONTATO -->
  <div
    class="hero min-h-screen bg-gradient-to-l from-base-200 to-secondary"
    id="contato"
  >
    <div class="hero-content flex-col lg:flex-row">
      <div class="lg:w-6/12 mt-6 md:mt-8 lg:mt-0 px-7">
        <div class="relative w-full h-full ml-10">
          <!-- <img src={imgUrl2} alt="home pic" width="427" class="rounded-xl   hover:scale-105 " /> -->
        </div>
      </div>
      <div class="container mx-auto py-9 md:py-12 lg:py-24">
        <div class="flex flex-col lg:flex-row justify-center items-strech mx-4">
          <div class="lg:w-6/12 flex justify-center items-center">
            <div>
              <h3 class="text-3xl md:text-5xl xl:text-4xl font-semibold">
                COMO A PSICOTERAPIA PODE TE AJUDAR
              </h3>
              <p
                class="   md:w-7/12 lg:w-11/12 xl:w-10/12 mt-4 lg:mt-5 text-base leading-normal font-semibold"
              >
                A vida nos traz desafio e necessidade de mudança. Doenças,
                perdas, conflitos familiares, a chegada de um filho, casamento
                ou dificuldades na carreira exigem redirecionamento. <br /><br
                />
                A psicoterapia promove o autoconhecimento, o desenvolvimento de habilidades
                de resolução de problemas e a capacidade de tomar decisões. Além
                disso, leva a melhora nas relações familiares, conjugais e socials.
                É o caminho indicado com bases científicas para o alívio de sintomas
                como ansiedade, depressão, fobias, compulsão e outros transtornos
                mentais ou de personalidade que levam ao sofrimento psíquico.
              </p>
              <div class="py-9 mt-5 flex-auto">
                <Whatsapp />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</main>

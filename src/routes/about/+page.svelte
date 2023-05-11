<script>
  import imgUrl2 from "../../assets/profile2.jpg";
  import Whatsapp from "../../components/whatsapp.svelte";
</script>

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
              de atuação na área. Durante sua carreira, ele tem ajudado inúmeras
              pessoas a lidar com seus problemas emocionais, mentais e
              comportamentais.<br /><br />
              Com sua ampla experiência, Bernardo é capaz de compreender os desafios
              enfrentados por cada indivíduo que procura sua ajuda, independentemente
              do contexto. Ele tem trabalhado com pessoas de todas as idades, gêneros
              e origens, o que lhe proporcionou uma visão abrangente e profunda das
              diversas dinâmicas psicológicas que podem afetar as pessoas.
              <br /><br />
              Bernardo possui uma abordagem terapêutica centrada no cliente, que
              visa criar um ambiente seguro e acolhedor para seus pacientes. Ele
              valoriza a empatia, a escuta ativa e a compreensão da perspectiva do
              paciente, a fim de ajudá-lo a explorar suas emoções e comportamentos
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

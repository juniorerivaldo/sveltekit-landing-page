<script>
  import imgUrl1 from "../../assets/profile1.jpg";
  import Whatsapp from "../../components/whatsapp.svelte";
</script>

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
              Tenha ao seu lado um profissional capacitado para você falar sobre
              seus medos, angústias e aflições e busque alívio através de um
              processo terapêutico
            </p>
            <div class="py-9 mt-5 flex-auto">
              <Whatsapp />
            </div>
          </div>
        </div>
        <div class="lg:w-8/12 mt-6 md:mt-8 lg:mt-0 px-7">
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

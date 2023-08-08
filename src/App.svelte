<script>
  let introImage = "https://api.lorem.space/image/face?hash=47449";
  let instagramLPF = "https://instagram.com/limitlessperformancepr";
  let instagramBAFF = "https://instagram.com/bafunctionalfitness";
  let facebookLPF = "https://facebook.com/BLimitlesspr";
  let facebookBAFF = "https://facebook.com/bafunctionalfitness";
  let whatsAppLPF = "https://wa.me/message/FA2CYLI44TYKO1";
  let whatsAppBAFF = "https://wa.me/message/VOMBCO73LC7LD1";
  let formLPF = "https://form.jotform.com/210524379360857";
  let formBAFF = "https://form.jotform.com/211533091932854";
  let phoneBAFF = "7875462042";
  let payPal = "https://paypal.me/teamlmitless";
  let athMovil = whatsAppLPF;
  let LPF = "Limitless Performance & Fitness";
  let BAFF = "BA Functional Fitness";
  let BAlogo = "./BALogo.svg";
  let BAHorario = "./horario.png";
  let BAPaquetes = "./paquetes.png";
  let trainerNeslie = "./neslie.jpg";
  let trainerYadira = "./yadira.jpg";
</script>

<main>
  <!-- <div class="bg-gradient-to-r from-cyan-500 to-blue-500 ..."> -->
  <div class="flex flex-col h-screen">
    <div class="flex-grow pt-4">
      <div class="tooltip tooltip-bottom" data-tip="Trainer Yadira">
        <div class="avatar">
          <div class="w-32 rounded-full">
            <img src={trainerYadira} alt="trainerYadira"/>
          </div>
        </div>
      </div>
      <div class="tooltip tooltip-bottom" data-tip="Trainer Neslie">
        <div class="avatar">
          <div class="w-32 rounded-full">
            <img src={BAlogo} alt={BAFF}/>
          </div>
        </div>
      </div>
      <div class="tooltip tooltip-bottom" data-tip="Trainer Neslie">
        <div class="avatar">
          <div class="w-32 rounded-full">
            <img src={trainerNeslie} alt="trainerNeslie"/>
          </div>
        </div>
      </div>
      <div class="intro">
        <p>
          Nuestra sesión de Cross Training es una experiencia grupal que combina una variedad de ejercicios de alta intensidad (HIIT), diseñados tanto para fortalecer como para mejorar la salud cardiovascular, abarcando todos los grupos musculares.
          Nuestro enfoque principal es mejorar la condición física de nuestros participantes y elevar su calidad de vida. Lo mejor de todo es que esta clase es adaptable para personas de todas las edades y niveles de condición física. ¡Únete a nosotros y transforma tu rutina de ejercicios!
        </p>
      </div>
      <div class="rating gap-1">
        <svg
          class="h-8 w-8 text-red-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <circle cx="12" cy="12" r="9" /> <path d="M6 5.3a9 9 0 0 1 0 13.4" />
          <path d="M6 5.3a9 9 0 0 1 0 13.4" transform="rotate(180 12 12)" />
        </svg>
        <svg
          class="h-8 w-8 text-indigo-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <circle cx="5" cy="18" r="3" /> <circle cx="19" cy="18" r="3" />
          <polyline points="12 19 12 15 9 12 14 8 16 11 19 11" />
          <circle cx="17" cy="5" r="1" /></svg
        >
        <svg
          class="h-8 w-8 text-yellow-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <circle cx="12" cy="12" r="9" />
          <line x1="5.65" y1="5.65" x2="18.35" y2="18.35" />
          <line x1="5.65" y1="18.35" x2="18.35" y2="5.65" />
          <path d="M12 3a9 9 0 0 0 9 9" /> <path d="M3 12a9 9 0 0 1 9 9" /></svg
        >
        <svg
          class="h-8 w-8 text-pink-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <circle cx="17" cy="6" r="2" />
          <path d="M9 11a4.97 4.97 0 1 0 3.95 7.95" />
          <path d="M19 20l-4 -5h-4l3 -5l-4 -3l-4 1" /></svg
        >
        <svg
          class="h-8 w-8 text-green-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <circle cx="12" cy="12" r="9" />
          <path d="M12 12a8 8 0 0 0 8 4M7.5 13.5a12 12 0 0 0 8.5 6.5" />
          <path
            d="M12 12a8 8 0 0 0 8 4M7.5 13.5a12 12 0 0 0 8.5 6.5"
            transform="rotate(120 12 12)"
          />
          <path
            d="M12 12a8 8 0 0 0 8 4M7.5 13.5a12 12 0 0 0 8.5 6.5"
            transform="rotate(240 12 12)"
          />
        </svg>
        <svg
          class="h-8 w-8 text-purple-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <line x1="8" y1="21" x2="16" y2="21" />
          <line x1="12" y1="17" x2="12" y2="21" />
          <line x1="7" y1="4" x2="17" y2="4" />
          <path d="M17 4v8a5 5 0 0 1 -10 0v-8" /> <circle cx="5" cy="9" r="2" />
          <circle cx="19" cy="9" r="2" /></svg
        >
        <svg
          class="h-8 w-8  text-gray-400"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          stroke-width="2"
          stroke="currentColor"
          fill="none"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <path stroke="none" d="M0 0h24v24H0z" />
          <circle cx="12" cy="12" r="9" />
          <line x1="9" y1="12" x2="15" y2="12" />
          <line x1="12" y1="9" x2="12" y2="15" /></svg
        >
      </div>
    
      <!-- <p class="titulo">Expertos con mas de 15 anos</p> -->
      <div class="grid gap-4">

        <!-- The button to open modal -->
        <label for="my-modal-3" class="btn modal-button">PRECIOS</label>

        <!-- Put this part before </body> tag -->
        <input type="checkbox" id="my-modal-3" class="modal-toggle" />
        <div class="modal">
          <div class="modal-box relative">
            <label for="my-modal-3"class="btn btn-sm btn-circle absolute right-2 top-2">✕</label>
            <div>
              <img class="rounded-xl" alt="paquetes" src={BAPaquetes} />
            </div>
          </div>
        </div>
       
          <!-- The button to open modal -->
       <label for="my-modal-2" class="btn modal-button">Horarios</label>
       <!-- Put this part before </body> tag -->
       <input type="checkbox" id="my-modal-2" class="modal-toggle" />
       <div class="modal">
         <div class="modal-box relative">
           <label for="my-modal-2"class="btn btn-sm btn-circle absolute right-2 top-2">✕</label>
           <div>
             <img class="rounded-xl" alt="horario" src={BAHorario} />
           </div>
         </div>
       </div>
       <div>
          <a href={instagramBAFF}
            ><button class="btn btn-block">Instagram</button></a
          >
        </div>
        <div>
          <a href={facebookBAFF}
            ><button class="btn btn-block">Facebook</button></a
          >
        </div>
        <div>
          <a href={whatsAppBAFF}
            ><button class="btn btn-block">whatsApp</button></a
          >
        </div>
        <div class="tooltip" data-tip="(787)546-2042">
          <a type="tel" href="tel:7875462042"
            ><button class="btn btn-block">Telefono</button></a
          >
        </div>
      </div>
      <!-- -space-x-6 -->

      <div class="flex payments pt-4">
        <p>Aceptamos:</p>
      </div>
      <div class="flex">
        <a href={athMovil}>
          <svg
            class="h-8 w-8 text-yellow-500"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z" />
            <path d="M4 12v-3a3 3 0 0 1 3 -3h13m-3 -3l3 3l-3 3" />
            <path d="M20 12v3a3 3 0 0 1 -3 3h-13m3 3l-3-3l3-3" /></svg
          >
        </a>
        <a href={payPal}>
          <svg
            class="h-8 w-8 text-blue-500"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z" />
            <path
              d="M10 13l2.538-.003c2.46 0 4.962-2.497 4.962-4.997 0-3-1.89-5-4.962-5H7c-.5 0-1 .5-1 1L4 18c0 .5.5 1 1 1h2.846L9 14c.089-.564.43-1 1-1zm7.467-5.837C19.204 8.153 20 10 20 12c0 2.467-2.54 4.505-5 4.505h.021-2.629l-.576 3.65a.998.998 0 01-.988.844l-2.712-.002a.5.5 0 01-.494-.578L7.846 19"
            /></svg
          >
        </a>
        <a href={payPal}>
          <svg
            class="h-8 w-8 text-red-500"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <line x1="12" y1="1" x2="12" y2="23" />
            <path d="M17 5H9.5a3.5 3.5 0 0 0 0 7h5a3.5 3.5 0 0 1 0 7H6" /></svg
          >
        </a>
      </div>
    </div>

    <footer>
      <div class="items-center grid-flow-col pt-4 text-gray-400">
        <p>
          © 2022 <a
            class="link"
            href="https://www.linkedin.com/in/jethzabell-medina/"
            >Jethzabell Medina</a
          > - All right reserved
        </p>
      </div>
    </footer>
  </div>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  main {
    text-align: center;
    padding-left: 2em;
    padding-right: 2em;
    margin: 0 auto;
  }
  .intro {
    text-align: center;
    padding-bottom: 1.5rem;
    margin: 0 auto;
    font-size: 18px;
  }

  .payments {
    text-align: center;
    margin: 0 auto;
    font-size: 18px;
  }

  .titulo {
    text-align: center;
    padding-bottom: 1rem;
    margin: 0 auto;
    font-size: 25px;
  }

  .logos {
    text-align: center;
    margin: 0 auto;
  }
</style>

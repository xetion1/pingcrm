<template>
<div>
    <div >
        <Headers></Headers>
    </div>
    <main class="relative container mx-auto bg-white px-4">
    <div class="relative -mx-4 top-0 pt-[17%] overflow-hidden">
        <img class="absolute inset-0 object-cover object-top w-full h-full filter blur" src="https://prod-ne-cdn-media.puregym.com/media/806016/glutes.jpg?quality=80&mode=pad&width=992" alt="" />
    </div>

    <div class="mt-[-10%] w-1/2 mx-auto">
        <div class="relative pt-[56.25%] overflow-hidden rounded-2xl">
        <img class="w-full h-full absolute inset-0 object-cover" src="https://prod-ne-cdn-media.puregym.com/media/806016/glutes.jpg?quality=80&mode=pad&width=992" alt="" />
        </div>
    </div>

    <article class="max-w-prose mx-auto py-8">
        <h1 class="text-2xl font-bold">SUSTIPRINKITE KOJAS ATLIKDAMI ŠIĄ ŠLAUNIES IR SĖDMENŲ TRENIRUOTĘ</h1>
        <h2 class="mt-2 text-sm text-gray-500">Admin, 28 November 2021</h2>

        <p class="mt-6 font-medium">Ieškote dienos treniruotės kojoms, kurios padidintų jūsų sėdmenis ir pakaušio raumenis? „Pure Gym“ asmeninis treneris „Harley“ pasidalino 5 geriausiais šlaunies ir sėdmenų pratimais, kurie sustiprins ir patobulins jūsų raumenis.</p>
        <p class="mt-6 font-bold">KODĖL REIKIA STIPRINTI SĖDMENIS IR ŠLAUNIES RAUMENIS?</p>
        <p class="mt-4">Stiprios kojos yra daugiau nei „Instagram“ vertas užpakalis – beveik kiekvienas gali turėti naudos iš stiprinant sėdmenis ir pakaušio raumenis. Abu raumenys dalyvauja atliekant pagrindinius funkcinius judesius: sėdmenys padeda stabilizuoti klubus ir dubenį ir yra atsakingi už klubų tiesimo judesius, o jūsų pakaušio raumenys dalyvauja tiesiant kojas ir sulenkiant kelius.

        Stiprūs, lankstūs sėdmenys ir šlaunies raumenys padeda:

        Pagerinti laikyseną<br>
        Užkirsti kelią traumoms<br>
        Sumažinti nugaros skausmą<br>
        Padidinkite sportinius rezultatus<br>
        Deja, sėdimas gyvenimo būdas kenkia šiems raumenims. Ilgas sėdėjimas gali sukelti silpnus ir įtemptus sėdmenis ir šlaunies raumenis, todėl tiems, kurie sėdi dėl darbo, labai svarbu atlikti specialius sėdmenų ir sėdmenų pratimus.</p>
        <p class="mt-6 font-bold">KAIP SUSTIPRINTI SĖDMENIS IR ŠLAUNIES RAUMENIS</p>
        <p class="mt-4">Geriausias būdas sustiprinti ir auginti bet kokius raumenis yra reguliarios pasipriešinimo treniruotės, užtikrinančios, kad laipsniškai perkrautumėte pasipriešinimą (pavyzdžiui, didindami pakartojimų skaičių, laiką ar svorį), kad išbandytumėte raumenis.</p>
        <p class="mt-6 font-bold">SĖDMENŲ IR ŠLAUNIES RAUMENŲ TRENIRUOTĖS</p>
        <p class="mt-4">Atlikite 3–4 kiekvieno pratimo serijas su 45–60 sekundžių pertrauka tarp kiekvieno pratimo. Kiekvieną savaitę didinkite svorį arba pakartojimų skaičių, kad užtikrintumėte, jog nuolatos stengiatės raumenims augti.<br>
        Pritūpimų pauzė – 10 pakartojimų<br>
        Rumunų trauka – 8 pakartojimai</p>
        <p>https://www.puregym.com/blog/5-exercises-to-strengthen-your-glutes-and-hamstrings/</p>
    </article>
    </main>
    <div>
        <Blog></Blog>
    </div>

    <div>
        <Footer></Footer>
    </div>

</div>
</template>

  <!-- component -->
<style>
  .pt-\[17\%\] {
    padding-top: 17%;
  }
  .mt-\[-10\%\] {
    margin-top: -10%;
  }
  .pt-\[56\.25\%\] {
    padding-top: 56.25%;
  }
</style>
<script>
import Headers from '@/Shared/Headers'
import Footer from '@/Shared/Footer'
import Blog from '@/Shared/Blog'

export default {
  metaInfo: { title: 'Blog-1' },
  components: {
    Headers,
    Blog,

    Footer,
  },
}
</script>

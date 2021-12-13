<template>
<div>
    <div >
        <Headers></Headers>
    </div>
    <main class="relative container mx-auto bg-white px-4">
    <div class="relative -mx-4 top-0 pt-[17%] overflow-hidden">
        <img class="absolute inset-0 object-cover object-top w-full h-full filter blur" src="https://prod-ne-cdn-media.puregym.com/media/792582/mindful.jpg?quality=80&mode=pad&width=992" alt="" />
    </div>

    <div class="mt-[-10%] w-1/2 mx-auto">
        <div class="relative pt-[56.25%] overflow-hidden rounded-2xl">
        <img class="w-full h-full absolute inset-0 object-cover" src="https://prod-ne-cdn-media.puregym.com/media/792582/mindful.jpg?quality=80&mode=pad&width=992" alt="" />
        </div>
    </div>

    <article class="max-w-prose mx-auto py-8">
        <h1 class="text-2xl font-bold">3 POPULIARIAUSIOS PROGRAMOS
</h1>
        <h2 class="mt-2 text-sm text-gray-500">Admin, 28 November 2021</h2>

        <p class="mt-6 font-medium">Norime to ar ne, mūsų išmanieji telefonai tapo svarbia mūsų sveikatos ir gerovės dalimi. Nesvarbu, ar tai būtų bendravimas su draugais, naujų santykių kūrimas , vakarienės receptų paieška ar muzikos transliavimas treniruotėms , daugumai mūsų telefonai yra didžiulė mūsų gyvenimo dalis.</p>
        <p class="mt-4"><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Stebėkite savo mėnesines, valdykite </font></font><a href="https://www.hellomagazine.com/tags/sleep/" target="_blank" rel=""><strong><font style="vertical-align: inherit;"></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ciklą, malšinkite stresą ir raskite sveikatą stiprinančių receptų naudodami mūsų telefono parduotuvėje šiuo metu esančias geriausias sveikatingumo programas – galų gale, jei vienu mygtuko paspaudimu galime užsisakyti išsinešimui ir taksi, kodėl nebandytum ir meditacijos? </font><font style="vertical-align: inherit;">Jūsų kūnas (ir protas) jums už tai padėkos…</font></font></p>
        <p class="mt-6 font-bold">1. Viršutinė erdvė</p>
        <p class="mt-4"><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class="">Meditacija ir dėmesingumas yra paprasti naudojant „Headspace“ programą, kurios </font><font style="vertical-align: inherit;" class="">gerbėjai </font><font style="vertical-align: inherit;" class="">laikosi </font></font><a href="https://www.hellomagazine.com/tags/gwyneth-paltrow/" target="_blank" rel=""><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class="">Gwyneth Paltrow</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class=""> ir </font></font><a href="https://www.hellomagazine.com/tags/emma-watson/" target="_blank" rel=""><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class="">Emma Watson</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class=""> .</font></font></p>
        <p class="mt-6 font-bold">2. Viršutinė erdvė</p>
        <p class="mt-4"> <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class="">Suaktyvinkite savo ciklą naudodami mėnesinių stebėjimo programą „Clue“ ir sužinokite daugiau apie tai, kaip mėnesinės jus veikia.</font></font></p>
        <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class="">Naudodami parinktis įvesti simptomus, tokius kaip mėšlungis ir galvos skausmas visą mėnesį, taip pat gyvenimo būdo veiksnius, tokius kaip alkoholis, miegas ir seksas, greitai susidarysite vaizdą apie tai, kaip ciklas veikia ne tik jūsų fizinę, bet ir psichinę sveikatą. sveikata taip pat. </font><font style="vertical-align: inherit;" class="">Esminis įrankis kiekvienai moteriai, norinčiai geriau pažinti savo kūną.</font></font></p>
        <p class="mt-6 font-bold">3. Noom</p>
        <p class="mt-4"><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;" class="">Pakeiskite požiūrį į maistą ir dietas, kad taptumėte sveikesni naudodami svorio metimo programą „Noom“.</font></font></p>
        <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Remdamasis maisto psichologija ir mūsų elgesiu su juo, Noom daugiausia dėmesio skiria elgesio keitimui, o ne maisto atsisakymui ir intensyvaus kūno rengybos tvarkaraščiui – visa tai rekomenduoja mitybos specialistų, asmeninių trenerių ir elgesio psichologų komanda.</font></font></p>
        <p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Programoje yra 1:1 sveikatos instruktavimas, sveikatos viktorinos ir straipsniai, kurie jus motyvuoja, taip pat galite stebėti savo pratimus, svorį, cukraus kiekį kraujyje ir kraujospūdį.</font></font></p>
        <p class="mt-4"> https://www.hellomagazine.com/healthandbeauty/health-and-fitness/2019010866354/wellness-apps-to-download/</p>


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
  metaInfo: { title: 'Blog-2' },
  components: {
    Headers,
    Blog,
    Footer,
  },
}
</script>

<script setup lang="ts">
import { useUserStore } from '~/stores/user'

const user = useUserStore()
const name = ref(user.savedName)

const router = useRouter()
const go = () => {
  if (name.value)
    router.push(`/hi/${encodeURIComponent(name.value)}`)
}

const { t } = useI18n()

</script>

<template>
  <div class="top-0 left-0 h-screen w-screen z-0 flex bg-cover dark:bg-gray-700" style="background-image: url(/img/hero_bg.jpg);">
    <div class="m-auto text-white">
      <span class="text-3xl lg:text-9xl md:text-4xl font-mono font-bold">
        CG LAB
      </span>

      <p class="text-gray-300 text-4xl pt-7 uppercase">
        NISER, Bhubaneswar
      </p>
    </div>
  </div>
  <section id="pain" class="container mx-auto flex h-screen pt-40">
    <img src="https://www.niser.ac.in/~chandan/images/slideshow/Coverpic.jpg" class="w-100 h-100">
    <div class="flex-grow text-left ml-10">
      <p class="text-xl">
        "Pain" is a common phenomenon which has been experienced by most of us at some
        point of time. It is known that different defined physical stimuli like low pH
        and/or noxious heat, and different noxious substances activating different
        receptors at the peripheral nervous system induce pain. Apart from these
        defined stimuli, immune system of individual and his/her psychological state
        can also influence the pain to a large extent. However, in most of these cases,
        the pain is "acute" in nature. This kind of pain is transient and is directly
        related to the availability of the stimuli. In other words, in absence of these
        noxious stimuli, the acute pain decays fast if not vanishes.
      </p>
      <p class="text-xl">
        However, in case of "chronic pain", the pain can be long lasting and medical
        treatment is not satisfactory. Also many analgesic drugs, like morphine which
        are effective against acute pain, are not effective against chronic pain. In
        fact, at present chronic pain has very little scope of medical treatment if at
        all. The factors involved in the development of chronic pain, their effect as
        well as their regulation remain unclear. In a simplified manner, the chronic
        pain can be partially explained by the permanent changes in the signaling events
        within the peripheral nervous system and by an alternate neuronal connections
        resulting abnormal transmission of the pain signal. At the neuronal level,
        changes in the cellular structures like mitochondria, cytoskeleton, vesicles and
        others may form the basis of chronification. Transient Receptor Potential (TRP)
        ion channels are also known to play central role in different forms of pain.
        Therefore, with regard to pain chronification, the involvement of TRP ion
        channels and other proteins involved in the regulation of different cellular
        components are worth to study at the molecular level.
      </p>
    </div>
  </section>
  <section id="contact-us" class="container mx-auto h-screen pt-10">
    <h1 class="text-4xl">
      Contact/Join Us
    </h1>
    <br>
    <p class="text-2xl uppercase mb-3 mt-6">
      Dr.Chandan Goswami
    </p>

    <p class="text-3xl">
      <a class="icon-btn " href="mailto:chandan@niser.ac.in">
        <ant-design:mail-outlined class="mr-4" />
      </a>

      <a class="icon-btn" href="#">
        <akar-icons:facebook-fill class="mr-4" />
      </a>

      <a class="icon-btn" href="#">
        <akar-icons:twitter-fill class="mr-4" />
      </a>
    </p>
    <h2 class="text-3xl text-left mt-7 mb-4">
      Graduate and Postdoctoral Reseach
    </h2>
    <p class="text-xl text-left">
      Candidates with an excellent research record and an excitement for asking
      tough questions should email Dr.Chandan Ghoswami with a brief introduction, CV, and the
      names and contact information of at least two references.
    </p>

    <h2 class="text-3xl text-left my-4">
      Master's Student
    </h2>
    <p class="text-xl text-left">
      Master's student will need to apply throught the <a href="https://www.nestexam.in/" target="__blank" class="text-blue-800 dark:text-blue-400">NEST exam</a> before joining NISER.
    </p>
  </section>
</template>

<route lang="yaml">
meta:
  layout: home
</route>

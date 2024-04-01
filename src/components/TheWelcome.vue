<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Pendidikan</template>

    saya merupakan seorang mahasiswa disebuah kampus yg bernama 
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">universitas islam riau</a>
    sebelumnya saya bersekolah di sman 2 tambang
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>tempat tanggal lahir</template>

    saya lahir di
    <a href="" target="_blank" rel="noopener">Tembilahan</a>. sebuah kabupaten dengan "seribu parit"
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>jurusan</template>

    saya memilih
    <a href="https://pinia.vuejs.org/" target="_blank" rel="noopener">teknik informatika</a>,
    sebagai jurusan saya
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Game</template>

    saat ini saya memainkan game
    <a href="https://www.callofduty.com/mobile" target="_blank" rel="noopener">call of duty mobile</a>,
    <a href="https://www.cookierun-kingdom.com/en/" target="_blank" rel="noopener"
      >cookie run kingdom</a>,
    <a href="https://pubg.com/en-na" target="_blank" rel="noopener">pubgm.</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>social media</template>
    <a href="" target="_blank" rel="noopener">IG:Fauzandiffas</a>.
  </WelcomeItem>
</template>

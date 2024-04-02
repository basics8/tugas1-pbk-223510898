<script setup lang="ts">
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
    <template #heading style="color: hsl(83, 93%, 49%);">Biodata</template>

    Hai, Perkenalkan nama saya Dimas AlQhifari.
    Saya merupakan mahasiswa dari Universitas Islam Riau di Kota Pekanbaru.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading style="color: hsl(83, 93%, 49%);">Riwayat Kuliah</template>

    Saya kuliah di jurusan Teknik Informatika di Universitas Islam Riau.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading style="color: hsl(83, 93%, 49%);">Hobi</template>

    Hobi saya adalah bermain musik, olahraga khususnya badminton, dan bermain game.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading style="color: hsl(83, 93%, 49%);">Minat dan Bakat</template>

    Saya memiliki minat dalam bidang teknologi dan bakat dalam bermain musik.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading style="color: hsl(83, 93%, 49%);">Riwayat Pendidikan</template>
    <ul>
      <li>SD AL AZHAR SYIFA BUDI PEKANBARU</li>
      <li>SMP AL AZHAR SYIFA BUDI PEKANBARU II</li>
      <li>SMA AL AZHAR SYIFA BUDI PEKANBARU II</li>
      <li>UNIVERSITAS ISLAM RIAU</li>
    </ul>

  </WelcomeItem>
</template>



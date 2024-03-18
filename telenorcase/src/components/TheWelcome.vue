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
    <template #heading>Om nettbutikken</template>

    Velkommen til verdens feteste nettbutikk! 
    <br>
    Her kan du kjøpe høykvalitets-merch av Telenors kuleste bedrepper.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Produkter</template>

    Hva slags produkter er du ute etter i dag?
    <br>
    Vi har alt fra sokker til matbokser! Eller kan vi friste med en snøkule?

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Våre favoritter</template>

    Prøv vår bestselger!
    <br>
    ♥Hoodie with a lifechanging quote♥
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Kontakt oss</template>

    Add oss på linkedIn dersom dere har spørsmål.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    ♥Hilsen gruppe 2. data♥
  </WelcomeItem>
</template>

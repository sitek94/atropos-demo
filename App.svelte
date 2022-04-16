<script>
  import Atropos from 'atropos/svelte'
</script>

<main class="container">
  <Atropos class="atropos-banner" highlight={false} on:enter={() => console.log('enter')}>
    <img class="atropos-banner-spacer" src="/atropos-bg.svg" alt="" />
    <img data-atropos-offset="-4.5" src="/atropos-bg.svg" alt="" />
    <img data-atropos-offset="-2.5" src="/atropos-mountains.svg" alt="" />
    <img data-atropos-offset="0" src="/atropos-forest-back.svg" alt="" />
    <img data-atropos-offset="2" src="/atropos-forest-mid.svg" alt="" />
    <img data-atropos-offset="4" src="/atropos-forest-front.svg" alt="" />
    <img data-atropos-offset="5" src="/atropos-logo-en.svg" alt="" />
  </Atropos>
</main>
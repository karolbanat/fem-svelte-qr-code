<script lang="ts">
  import Card from "./lib/Card.svelte";
  import QRCode from './assets/image-qr-code.png'


</script>

<main>
    <Card imageSrc={QRCode} imageAlt='Frontend Mentor Page QR Code' heading='Improve your front-end skills by building projects' text='Scan the QR code to visit Frontend Mentor and take your coding skills to the next level'/>
</main>

<style>
    main {
        padding-inline: 1.75rem;
    }
</style>

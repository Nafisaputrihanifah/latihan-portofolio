<script setup>
import { TheCard } from 'flowbite-vue'
</script>
<template>
<svg id="wave" style="transform:rotate(180deg); transition: 0.3s" viewBox="0 0 1440 240" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(243, 62, 86.908, 1)" offset="0%"></stop><stop stop-color="rgba(255, 179, 11, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,168L16,172C32,176,64,184,96,176C128,168,160,144,192,144C224,144,256,168,288,164C320,160,352,128,384,104C416,80,448,64,480,84C512,104,544,160,576,176C608,192,640,168,672,136C704,104,736,64,768,40C800,16,832,8,864,32C896,56,928,112,960,112C992,112,1024,56,1056,56C1088,56,1120,112,1152,120C1184,128,1216,88,1248,84C1280,80,1312,112,1344,140C1376,168,1408,192,1440,168C1472,144,1504,72,1536,56C1568,40,1600,80,1632,84C1664,88,1696,56,1728,68C1760,80,1792,136,1824,144C1856,152,1888,112,1920,104C1952,96,1984,120,2016,112C2048,104,2080,64,2112,60C2144,56,2176,88,2208,120C2240,152,2272,184,2288,200L2304,216L2304,240L2288,240C2272,240,2240,240,2208,240C2176,240,2144,240,2112,240C2080,240,2048,240,2016,240C1984,240,1952,240,1920,240C1888,240,1856,240,1824,240C1792,240,1760,240,1728,240C1696,240,1664,240,1632,240C1600,240,1568,240,1536,240C1504,240,1472,240,1440,240C1408,240,1376,240,1344,240C1312,240,1280,240,1248,240C1216,240,1184,240,1152,240C1120,240,1088,240,1056,240C1024,240,992,240,960,240C928,240,896,240,864,240C832,240,800,240,768,240C736,240,704,240,672,240C640,240,608,240,576,240C544,240,512,240,480,240C448,240,416,240,384,240C352,240,320,240,288,240C256,240,224,240,192,240C160,240,128,240,96,240C64,240,32,240,16,240L0,240Z"></path></svg>
<div align="center">
    <h3 class="text-3xl font-bold dark:text-white">My Hobby</h3>
</div>
<br>
    <center>

        <div class="flex flex-row">
      <div class="grid grid-cols-1 gap-1 m-8">
        <the-card variant="image" img-src="https://i.pinimg.com/1200x/32/08/b5/3208b5a940422915983f4b6f14c6bfa1.jpg" img-alt="Desk">
    <h5 class="mb-3 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Reading Books & Comics</h5>
  </the-card>
      </div>

      <div class="grid grid-cols-1 gap-1 m-8">
        <the-card variant="image" img-src="https://i.pinimg.com/736x/03/5b/8b/035b8b30ee409263a91405afd121e088.jpg" img-alt="Desk">
    <h5 class="mb-3 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Watching Anime</h5>
  </the-card>
      </div>

      <div class="grid grid-cols-1 gap-1 m-8">
        <the-card variant="image" img-src="https://i.pinimg.com/474x/1d/32/e0/1d32e059aeeaa81bfd497f7f2c7b841a.jpg" img-alt="Desk">
    <h5 class="mb-3 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Listening to music</h5>
  </the-card>
      </div>

      <div class="grid grid-cols-1 gap-1 m-8">
        <the-card variant="image" img-src="https://i.pinimg.com/550x/2c/cf/d6/2ccfd676ad3a75b837e062c9991191c0.jpg" img-alt="Desk">
    <h5 class="mb-3 text-1xl font-bold tracking-tight text-gray-900 dark:text-white">Sleep</h5>
  </the-card>
      </div>



</div>
</center>

<svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 230" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(243, 62, 86.908, 1)" offset="0%"></stop><stop stop-color="rgba(209.784, 181.356, 118.513, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,161L17.1,164.8C34.3,169,69,176,103,168.7C137.1,161,171,138,206,138C240,138,274,161,309,157.2C342.9,153,377,123,411,99.7C445.7,77,480,61,514,80.5C548.6,100,583,153,617,168.7C651.4,184,686,161,720,130.3C754.3,100,789,61,823,38.3C857.1,15,891,8,926,30.7C960,54,994,107,1029,107.3C1062.9,107,1097,54,1131,53.7C1165.7,54,1200,107,1234,115C1268.6,123,1303,84,1337,80.5C1371.4,77,1406,107,1440,134.2C1474.3,161,1509,184,1543,161C1577.1,138,1611,69,1646,53.7C1680,38,1714,77,1749,80.5C1782.9,84,1817,54,1851,65.2C1885.7,77,1920,130,1954,138C1988.6,146,2023,107,2057,99.7C2091.4,92,2126,115,2160,107.3C2194.3,100,2229,61,2263,57.5C2297.1,54,2331,84,2366,115C2400,146,2434,176,2451,191.7L2468.6,207L2468.6,230L2451.4,230C2434.3,230,2400,230,2366,230C2331.4,230,2297,230,2263,230C2228.6,230,2194,230,2160,230C2125.7,230,2091,230,2057,230C2022.9,230,1989,230,1954,230C1920,230,1886,230,1851,230C1817.1,230,1783,230,1749,230C1714.3,230,1680,230,1646,230C1611.4,230,1577,230,1543,230C1508.6,230,1474,230,1440,230C1405.7,230,1371,230,1337,230C1302.9,230,1269,230,1234,230C1200,230,1166,230,1131,230C1097.1,230,1063,230,1029,230C994.3,230,960,230,926,230C891.4,230,857,230,823,230C788.6,230,754,230,720,230C685.7,230,651,230,617,230C582.9,230,549,230,514,230C480,230,446,230,411,230C377.1,230,343,230,309,230C274.3,230,240,230,206,230C171.4,230,137,230,103,230C68.6,230,34,230,17,230L0,230Z"></path></svg>
</template>

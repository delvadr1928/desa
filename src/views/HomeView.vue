<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Sejarah Desa Singajaya</p>
     
      <p>
        Desa Singajaya adalah salah satu desa yang terletak di Kecamatan Jonggol Kabupaten Bogor Provinsi Jawa Barat. Terbentuknya Desa Singajaya sekitar tahun 1952,tetapi terbentuknya Desa Singajaya awal berasal dari zaman Belanda. Waktu itu ada 4 kemandoran, yaitu Kemandoran Nyangegeng, Sukaati, Rawa Gede dan Cibodas.Dibentuklah Rembuk Desa pada tahun 1952, nama Singajaya dicetuskan oleh KH. Mamun Ma’rup dan para tokoh keempat kemandoran diatas.</p>
        <ul>
          <li>1.	KARTOBI				          : dari tahun ..... sampai …..   (ditunjuk)</li>
          <li>2.	H.M. SA’ID			        : dari tahun ..... sampai 1998 (definitif)</li>
          <li>3.	SUMADI SA’ID			      : dari tahun 1998 sampai 2013 (definitif)</li>
          <li>4.	NENENG AHMAD FAUZI	    : dari tahun 2013 sampai 2019 (definitif)</li>
          <li>5.	H. PEIH MARKOWI		      : dari tahun 2019 sampai 2020 (definitif)</li>
          <li>6.	HJ. LILI MULYATI, S.Pd  : dari tahun 2021 sampai 2025 (definitif)</li>
        </ul>
      <p class="text-3xl font-semibold my-4">Struktur Desa Singajaya</p>
      <img src="@/assets/struktur-desa-singajaya.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>

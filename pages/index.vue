<template>
  <div>
    <div id="header" class="bg-[url('/hero-bg.jpg')] px-20">
      <div id="menu" class="grid grid-cols-2 py-5">
        <div id="menu-left">
          <img src="logo_white.png" alt="" />
        </div>

        <div id="menu-right">
          <ul class="grid grid-cols-4 text-2xl font-oswald text-white pt-5">
            <li class="pr-5 text-center">Mengenai Kami</li>
            <li>Produk</li>
            <li>Lokasi</li>
            <li>Hubungi</li>
          </ul>
        </div>
      </div>

      <div class="grid grid-cols-2 pb-30 pt-10">
        <img src="robot_tifia.png" class="pr-8" alt="" />

        <div class="text-center pt-30">
          <h1 class="text-8xl text-white text-center font-oswald uppercase py-1">
            Automasi Trading Anda!
          </h1>
          <h2 class="text-6xl text-white text-center font-roboto uppercase my-5">
            CopyTrade Bersama Kami
          </h2>
          <p class="text-2xl text-white font-roboto font-light text-center">
            Belajar Trading Percuma Sambil Copytrade Dari Trader yang Berjaya !
          </p>
        </div>
      </div>
    </div>
    <div id="section-1" class="text-center bg-[url('/three-burgers.jpg')] pb-96 bg-cover">
      <h1 class="text-6xl uppercase font-oswald text-center pt-20 px-24">
        90% Trader Gagal Dalam Trading Dan Hanya 10% Sahaja Yang Berjaya!
      </h1>
      <p
        class="font-roboto italic font-light text-grey-500 text-center text-lg py-6 px-28"
      >
      Dalam Setiap Website Broker Mengandungi "Risk Closure" Bahawa Forex Trading Merupakan Instrumen Pelaburan Yang Bahaya Dimana Pedagang Boleh Hilang Kesemua Wang Yang Dilaburkan Dan Jumlah Pedagang Yang Gagal Mengatasi Jumlah Pedagang Yang Berjaya.
      </p>
      <p
        class="font-roboto italic font-light text-grey-500 text-center text-lg py-6 px-28"
      >
      Jalan Terbaik Bagi Pemula adalah dengan mempelbagaikan akaun trading kepada berperingkat mengikut aras risiko.Dengan Meletakan Modal Di Beberapa Akaun Untuk Berdagang Tidak Menjanjikan UNTUNG Yang Luar Biasa Tapi Mampu Mengurangkan Risiko Kehilangan SEMUA modal.TOTAL LOSS!
      </p>
      <p
        class="font-roboto italic font-light text-grey-500 text-center text-lg py-6 px-28"
      >
      Persoalannya mampu ke Trader menguruskan pelbagai akaun trading dalam satu-satu masa?Tidak mustahil bagi yang buat secara FULL TIME. Tapi Bagi Yang Bekerja MASA adalah terhad dan BEBAN membuat kajian dan analisa Chart Menganggu Masa Luar Bersama Keluarga.Langkah Terbaik Adalah Menyerahkan Tugasan kepada PAKAR yang mampu menguruskan akaun trading.
      </p>
      <button class="font-oswald uppercase bg-red-500 text-white text-center py-3 px-8">
        Daftar Akaun
      </button>
    </div>
    <div id="section-3" class="font-oswald">
      <h1
        class="text-6xl text-center font-oswald text-red-500 uppercase font-medium py-10"
      >
        Produk dan Servis
      </h1>
      <p class="text-center px-20 font-light text-gray-500 py-5">
        Selain Berdagang, kami juga menyediakan platform Pendidikan,Merchandise dan cabutan Bertuah!
      </p>
      <div class="grid grid-cols-2 px-40 gap-5">
        <div id="left-item-columns">
          <Item
          image="topi.png"
          title="Topi"
          description="Topi Limited TIFIA"
          price="11.99" />
          <Item
          image="baju.png"
          title="Baju TIFIA"
          description="BAJU TIFIA 2022"
          price="13.99" />
        </div>
        <div id="right-item-columns">
          <Item
          image="cawan.png"
          title="cawan classic"
          description="cawan TIFIA"
          price="20.99" />
          <item
          image="lucky.png"
          title="lucky DRAW"
          description="lucky draw bagi yang bertuah"
          price="1.00" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

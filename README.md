<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hapizzz</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>

<body class="bg-gray-100 text-gray-800">

  <!-- Navbar -->
  <header class="bg-black text-white">
    <div class="container mx-auto px-4 py-4 flex flex-col md:flex-row justify-between items-center">
      <h1 class="text-2xl font-bold mb-4 md:mb-0">Hapizzz</h1>
      <nav class="flex flex-wrap gap-4 space-x-0 md:space-x-6 text-center">
        <a href="#home" class="hover:underline">Ahnaf Hafizh Putra Efendi</a>
        <a href="#about" class="hover:underline">About Me</a>
        <a href="#team" class="hover:underline">My Team</a>
      </nav>
    </div>
  </header>

  <!-- About Section -->
  <section id="about" class="bg-white py-16 px-4">
    <div class="container mx-auto flex flex-col md:flex-row items-center gap-4 justify-between items-center">
      <div class="text-center md:text-left max-w-xl mx-44">
        <h3 class="text-2xl font-bold mb-4">About Me!!</h3>
        <p class="text-gray-600">
          Aku Hapizzz, 18 Tahun dari Nganjuk, Jawa Timur. Aku adalah seorang Mahasiswa Teknik Informatika Politeknik Elektronika Negeri Surabaya, saat ini aku masih menjalani perkuliahanku di semester 1.
          Aku menjalani perkuliahanku dengan memiliki hobi bermain motor / jalan-jalan dengan sepeda motorku. Jika tertarik dengan kehidupanku bisa langsung kepoin ke Instagramku yaa @aku.hapizzz
        </p>
      </div>
      <img src="Hapizzz.jpg" alt="Ahnaf Hafizh" class="w-full md:w-64 h-auto rounded">
    </div>
  </section>

  <!-- Gallery Section -->
  <section id="gallery" class="bg-black py-16 text-white px-4">
    <div class="container mx-auto text-center">
      <h3 class="text-2xl font-bold mb-6">Gallery With My Motorcycle</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <img src="1.jpg" alt="Image 1" class="w-full h-auto rounded">
        <img src="2.jpg" alt="Image 2" class="w-full h-auto rounded">
        <img src="3.jpg" alt="Image 3" class="w-full h-auto rounded">
        <img src="4.jpg" alt="Image 4" class="w-full h-auto rounded">
      </div>

      <h3 class="text-2xl font-bold mt-12 mb-6">Gallery My Motorcycle</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <img src="5.jpg" alt="Image 5" class="w-full h-auto rounded">
        <img src="6.jpg" alt="Image 6" class="w-full h-auto rounded">
        <img src="7.jpg" alt="Image 7" class="w-full h-auto rounded">
        <img src="8.jpg" alt="Image 8" class="w-full h-auto rounded">
      </div>
    </div>
  </section>

  <!-- Keahlian, Pengalaman, Edukasi -->
  <section id="service" class="bg-gray-100 py-16 px-4">
    <div class="container mx-auto text-center">
      <h3 class="text-2xl font-bold mb-6">Keahlian, Pengalaman, Edukasi</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div>
          <h4 class="text-xl font-bold mb-4">Software</h4>
          <div class="flex justify-center gap-4">
            <img src="Pixellab.png" alt="Pixellab" class="w-16 h-16 rounded-full">
            <img src="canva.png" alt="Canva" class="w-16 h-16 rounded-full">
            <img src="picsart.png" alt="PicsArt" class="w-16 h-16 rounded-full">
            <img src="CapCut.png" alt="CapCut" class="w-16 h-16 rounded-full">
          </div>
        </div>
        <div>
          <h4 class="text-xl font-bold mb-4">Pengalaman</h4>
          <p class="text-gray-600">Editor Feed Instagram</p>
          <p class="text-gray-600">JJ Capcut / Alight Motion</p>
          <p class="text-gray-600">Cinematic Motor</p>
        </div>
        <div>
          <h4 class="text-xl font-bold mb-4">Edukasi</h4>
          <p class="text-gray-600">MI AL-Muttaqin Lengkong (2012-2018)</p>
          <p class="text-gray-600">MTsN 4 Nganjuk (2018-2021)</p>
          <p class="text-gray-600">MAN 1 Nganjuk (2021-2024)</p>
          <p class="text-gray-600">Politeknik Elektronika Negeri Surabaya (2024-Now)</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="bg-black text-white py-12 px-4">
    <div class="container mx-auto text-center">
      <nav class="flex flex-wrap justify-center gap-4 mb-6">
        <a href="#" class="hover:underline">My Team</a>
        <a href="#" class="hover:underline">About Me</a>
        <a href="#" class="hover:underline">Contact</a>
      </nav>
      <p class="text-gray-400 mb-4">Enjoy the Steps<br>For my Future, I will fight !!!</p>
      <div class="text-sm text-gray-500">
        <p>akuhapizz@gmail.com | +62 895-0239-1355</p>
        <p>Nganjuk, Jawa Timur, Indonesia</p>
        <p>© 2024 Ahnaf Hafizh. All Rights Reserved</p>
      </div>
    </div>
  </footer>

</body>
</html>

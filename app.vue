<template>
  <div class="bg-gray-100 min-h-screen text-gray-800 font-serif">
    <!-- Header -->
    <header class="p-6 flex justify-between items-center shadow-lg bg-white sticky top-0 z-50" id="head">
      <div class="text-3xl font-bold text-slate-800">brenaufal</div>
      <nav class="hidden md:flex space-x-4">
        <a href="#about" class="text-slate-800 hover:text-slate-950 transition duration-300">About Me</a>
        <a href="#Res" class="text-slate-800 hover:text-slate-950 transition duration-300">Resume</a>
        <a href="#skill" class="text-slate-800 hover:text-slate-950 transition duration-300">Skills</a>
      </nav>
    </header>


   <!-- Hero Section -->
    <section class="relative container mx-auto px-6 py-20 text-center bg-fixed bg-cover bg-center" id="bg-1" style="background-image: url('https://i.pinimg.com/736x/e9/2b/8c/e92b8c9b21501d9517105d7b47a326bb.jpg');">
      <div class="relative z-10">
        <h1 class="text-6xl font-bold mb-4 text-slate-100 parallax-text">PORTFOLIO</h1>
        <p class="text-lg mb-2 text-slate-100 parallax-text">| IG : @brenaufal |</p>
        <div class="mt-10">
          <button class="bg-slate-900 text-white px-6 py-3 rounded-full hover:bg-slate-950 transition duration-300 transform hover:scale-105">
            <a href="#about">Scroll Down</a>
          </button>
        </div>
      </div>
      <div class="absolute inset-0 bg-black opacity-50"></div>
    </section>


    <!-- About Section -->
    <section class="bg-white text-gray-800 py-20" id="about">
    <div class="container mx-auto px-6">
      <!-- Title -->
      

      <!-- Content Grid -->
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12 flex flex-col justify-center items-center">
        <!-- Left Section -->
        <div>
          <h2 class="text-9xl font-bold mb-8 text-slate-800">Hello,<br>I'm Bren!</h2>
          <p class="text-2xl text-lg mb-6 my-16">
            Nama saya Brenayaka Naufal Abdillah. <br>
            Saya adalah mahasiswa Fakultas Vokasi Jurusan Teknologi Informasi. <br>
            Saya Tinggal di Bekasi Tetapi sedang belajar di Universitas Brawijaya, Malang, Indonesia.
          </p>
          <a href="https://id.linkedin.com/in/brenayaka-naufal-abdillah-947a55288" 
            target="_blank" 
            class="text-slate-600 hover:underline bg-yellow-300 px-4 py-2 rounded-lg hover:bg-yellow-400 transition duration-300">
            linkedin.com/in/brenayaka-naufal-abdillah
          </a>
        </div>

        <!-- Right Section (Image and Contact Info) -->
        <div class="relative flex flex-col items-center">
          <!-- Image placeholder -->
          <div class="w-80 h-80 bg-gray-300 rounded-full mb-4 overflow-hidden">
            <img 
              src="./assets/WhatsApp Image 2024-09-25 at 3.42.21 AM.jpeg" 
              alt="Bren's photo" 
              class="w-full h-full object-cover"
            />
          </div>
          <!-- Text Overlays -->
          <div class="absolute top-20 left-24 bg-yellow-400 text-slate-950 px-4 py-2 rounded-full">
            23rd May 2005
          </div>
          <div class="absolute top-40 right-1 bg-yellow-400 text-slate-950 px-4 py-2 rounded-full">
            Indonesia, Malaysia, Bekasi WELL!
          </div>

         <!-- Contact Info -->
        <div class="bg-slate-800 p-8 rounded-lg text-white transform hover:scale-105 transition duration-300 w-full">
          <h3 class="text-5xl font-bold mb-4">Contact</h3>
          <!-- Location -->
          <p class="flex items-center mb-2">
            <img src="https://cdn-icons-png.flaticon.com/512/61/61942.png" 
                class="w-6 h-6 mr-2" />
            Bekasi, Indonesia
          </p>
          <!-- Email -->
          <p class="flex items-center mb-2">
            <img src="https://cdn-icons-png.flaticon.com/512/860/860758.png" 
                class="w-5 h-5 mr-3" />
            br3n235@gmail.com
          </p>
          <!-- Phone -->
          <p class="flex items-center mb-2">
            <img src="https://cdn-icons-png.freepik.com/256/455/455705.png?semt=ais_hybrid" 
                class="w-6 h-6 mr-2" />
            +6287830672908
          </p>
        </div>
        </div>
      </div>
    </div>
  </section>

    <!-- Resume Section -->
    <section class="py-20 bg-gray-200" id="Res">
  <div class="container mx-auto px-6">
    <h2 class="text-4xl font-bold mb-12 text-slate-100 text-center">RESUME</h2>
    <div class="flex justify-center">
      <div class="max-w-2xl w-full">
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h3 class="text-2xl font-bold mb-6 text-slate-800 text-center">Education</h3>
          <ul class="list-none space-y-4">
            <li class="text-center">
              <span class="font-bold block">2017-2020:</span>
              SMP 259 Jakarta
            </li>
            <li class="text-center">
              <span class="font-bold block">2020-2023:</span>
              SMA 42 Jakarta (Covid)
            </li>
            <li class="text-center">
              <span class="font-bold block">2023-Now:</span>
             Universitas Brawijaya, Teknologi Informasi
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>

    <!-- Skills Section -->
    <section class="bg-white text-gray-800 py-20" id="skill">
  <div class="container mx-auto px-6">
    <h2 class="text-4xl font-bold mb-12 text-slate-800">Technical Skills</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
      <!-- Software Skills -->
      <div>
        <h3 class="text-2xl font-bold mb-6 text-slate-700">Software Skills</h3>
        <div class="flex flex-wrap gap-4 my-4">
          <!-- Photoshop -->
          <div class="text-center">
            <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">
              Photoshop
            </span>
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/af/Adobe_Photoshop_CC_icon.svg" alt="Photoshop Logo" class="mt-2 w-12 h-12 mx-auto">
          </div>
          <!-- Illustrator -->
          <div class="text-center">
            <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">
              Illustrator
            </span>
            <img src="https://upload.wikimedia.org/wikipedia/commons/f/fb/Adobe_Illustrator_CC_icon.svg" alt="Illustrator Logo" class="mt-2 w-12 h-12 mx-auto">
          </div>
          <!-- Roblox Studio -->
          <div class="text-center">
            <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">
              Roblox Studio
            </span>
            <img src="https://devforum-uploads.s3.dualstack.us-east-2.amazonaws.com/uploads/optimized/4X/6/2/f/62f64963b3b8eda573996bdfb646729e818ef77b_2_750x750.png" alt="Roblox Studio Logo" class="mt-2 w-12 h-13 mx-auto">
          </div>
          <!-- Premiere Pro -->
          <div class="text-center">
            <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">
              Premiere Pro
            </span>
            <img src="https://upload.wikimedia.org/wikipedia/commons/4/40/Adobe_Premiere_Pro_CC_icon.svg" alt="Premiere Pro Logo" class="mt-2 w-12 h-12 mx-auto">
          </div>
        </div>
      </div>

      <!-- Coding Skills -->
      <div>
        <h3 class="text-2xl font-bold mb-6 text-slate-700">Coding Skills</h3>
        <ul class="list-disc list-inside space-y-2">
          <li>Basic knowledge of HTML</li>
          <li>Basic CSS</li>
          <li>Basic JavaScript</li>
          <li>Basic SQL</li>
        </ul>
      </div>
    </div>
  </div>
</section>

  <!-- Language and Hobbies Section -->
  <section class="py-20 bg-gray-200" id="last">
    <div class="container mx-auto px-6">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
        <!-- Languages Section -->
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h2 class="text-4xl font-bold mb-8 text-slate-800">Languages</h2>
          <ul class="list-disc list-inside space-y-4">
            <li>Indonesia - Lancar</li>
            <li>English - Biasa Saja</li>
            <li>Jawa - Biasa</li>
            <li>Sunda - Kurang</li>
          </ul>
        </div>

        <!-- Hobbies & Interests Section -->
        <div class="bg-white p-6 rounded-lg shadow-lg">
          <h2 class="text-4xl font-bold mb-8 text-slate-800">Hobbies & Interests</h2>
          <div class="grid grid-cols-2 md:grid-cols-5 gap-8">
            <!-- Music Hobby -->
            <div class="flex flex-col items-center">
              <img src="https://st3.depositphotos.com/29475518/34432/v/450/depositphotos_344324926-stock-illustration-headphone-music-icon-logo-design.jpg" alt="Music" class="w-16 h-16 mb-4  object-cover">
              <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">Music</span>
            </div>

            <!-- Movie Hobby -->
            <div class="flex flex-col items-center">
              <img src="https://png.pngtree.com/element_our/png/20181227/movie-icon-which-is-designed-for-all-application-purpose-new-png_287896.jpg" alt="Movie" class="w-16 h-16 mb-4 rounded-full object-cover">
              <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">Movie</span>
            </div>

            <!-- Comic Hobby -->
            <div class="flex flex-col items-center">
              <img src="https://static.thenounproject.com/png/7433-200.png" alt="Comic" class="w-14 h-14 mb-6  object-cover">
              <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">Comic</span>
            </div>

            <!-- Gaming Hobby -->
            <div class="flex flex-col items-center">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRv5gBOnaW6kJvBLnZgpftvfLG0Ahg-WFpbt5iNsx-M3he7c01bHSeME-rp47dxSJKthuQ&usqp=CAU" alt="Gaming" class="w-14 h-14 mb-6 object-cover">
              <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">Gaming</span>
            </div>

            <!-- Sleep Hobby -->
            <div class="flex flex-col items-center">
              <img src="https://cdn-icons-png.freepik.com/512/835/835503.png" alt="Sleep" class="w-14 h-14 mb-6 object-cover">
              <span class="bg-slate-800 text-white px-4 py-2 rounded-full transform hover:scale-105 transition duration-300">Sleep</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Footer Section -->
  <footer class="bg-gray-800 text-white py-6">
      <div class="container mx-auto text-center">
        <p>&copy; 2024 Brenayaka Naufal Abdillah. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  methods: {
    handleScroll() {
      const bgHero = document.getElementById('bg-1');
      const scrollPosition = window.scrollY;
      bgHero.style.backgroundPositionY = `${scrollPosition * 0.5}px`; // Mengatur kecepatan scroll background
    }
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.handleScroll);
  }
}

</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Open+Sans:wght@400;600&display=swap');

.parallax-hero {
  background-image: url('/path/to/your/hero-background.jpg'); /* Ganti dengan path gambar Anda */
  background-attachment: fixed; /* Untuk parallax */
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
  height: 100vh; /* Membuat hero section memenuhi viewport */
}

body {
  font-family: 'Open Sans', sans-serif;
}

#Res {
  background-image: url("https://i.pinimg.com/736x/e9/2b/8c/e92b8c9b21501d9517105d7b47a326bb.jpg");
}

#last {
  background-image: url("https://i.pinimg.com/736x/e9/2b/8c/e92b8c9b21501d9517105d7b47a326bb.jpg");
}

h1, h2, h3 {
  font-family: 'Playfair Display', serif;
}
</style>
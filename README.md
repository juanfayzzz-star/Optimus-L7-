<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portofolio</title>
    <style>
       body {
    margin: 0;
    padding: 0;
    font-family: Bold, Arial, sans-serif;
    background: linear-gradient(to bottom, #2A7B7d, #6991c7);
    color: #ffff;
}

.container {
    width: 80%;
    margin: auto;
    padding: 20px;
}

h1, h2, {
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.5);
}

section {
    margin-bottom: 20px;
    padding: 25px;
    background: rgba(0, 0, 0, 0.2);
    border-radius: 20px;
}

a {
    color: #ffb;
    text-decoration: none;
}

a:hover {
    color: #2A7B7d;
}

.hover-element {
  width: 100%;
  height: 100%;
  background: linear-gradient(to bottom, #2A7B7c);
  position: absolute;
  left: -100%; /* Mengatur posisi awal di luar container (di sebelah kiri) */
  transition: left 0.5s ease-in-out; /* Menambahkan transisi untuk animasi yang mulus */
}
    </style>
</head>
<body>
    <div class="container">
  <div class="hover-element"></div>
</div>

           <h1 style="text-align: center;">portofolio</h1>

        <section>
          <h2>web ini dibuat oleh <strong>Ahmad.Juan.Al</strong></h2>
          
            <h2>Proyek pengembangan portofolio </h2>
            
            <p>Deskripsi proyek:
            proyek yang saya kerjakan sekarang adalah request dari seorang viewers dari tiktok.</p>
        </section>
        <section>
            <h2>Tentang</h2>
            <p>Info tentang saya:
              perkenalkan nama saya ahmad juan aldian,saya seorang pelajar kelas 1 SMA.saya sudah terjun kedalam dunia pembuatan website sudah hampir 2 tahunan dan itu pun saya sempat berhenti programing karena fokus sekolah tapi sekarang saya sudah mulai kembali ke dunia programing akibat dorongan dan semangat yang diberikan oleh teman teman dan keluarga saya.</p>
              
                
        </section>
        <section>
          <h2>biodata</h2>
          <p>saya lahir di sandai,kalimantan barat,19 Maret 2010.saya sebenarnya bukan asli suku melayu melainkan saya adalah perpaduan antara suku dayak dan jawa,selama 15 tahun terakhir ini hidup saya hanya terfokus kepada pembelajaran, bukan kepada hal lain,hal itu juga yang membuat saya mendapatkan Rangking 4 waktu kelas 6 Sd.</p>
          
        
             <h2 style="text-align:center";> Copyright 2025 </h2>
          <script>
      
      window.addEventListener("load", () => {
        const hoverEl = document.querySelector(".hover-element");
        setTimeout(() => {
          hoverEl.style.left = "0";
        }, 500);
        setTimeout(() => {
          hoverEl.style.left = "-100%";
        }, 2000);
      });

    
      document.querySelector("h1").addEventListener("click", () => {
        const colors = ["#2A7B7d", "#1abc9c", "#9b59b6", "#e67e22", "#e74c3c"];
        const randomColor = colors[Math.floor(Math.random() * colors.length)];
        document.body.style.background = `linear-gradient(to bottom, ${randomColor}, #6991c7)`;
      });

      // Hover section → tampilkan alert biodata khusus
      document.querySelector("section:last-of-type").addEventListener("mouseenter", () => {
        console.log("Kamu sedang melihat bagian biodata 👀");
      });
    </script>
</body>
</html>
        </section>
    </div>
</body>
</html>

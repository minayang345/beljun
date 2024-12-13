<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  
  <title>Happy Birthday</title>
  <link rel="icon" type="image/x-icon" href="https://malasid.github.io/favicon.png">
  <meta name="description" content="HTML Bucin Malas.id">

  <!-- Preconnects -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  
  <!-- Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Shippori+Antique:wght@400;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">

  <!-- Stylesheets -->
  <link href="https://feeldreams.github.io/heihbd/style.css" rel="stylesheet" type="text/css">

  <!-- Scripts -->
  <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script>
  <script src="https://unpkg.com/typeit@8.7.0/dist/index.umd.js"></script>
  <script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script>
</head>
<body>
  <!-- Ganti Audio di sini -->
  <audio src="https://feeldreams.github.io/djikhlas.mp3" id="linkmp3" class="sembunyi"></audio>

  <div id="bodyblur">
    <img src="https://feeldreams.github.io/wp9.jpg" id="wallpaper" alt="Wallpaper">
    <div id="beneranblur"></div>
  </div>

  <div id="Content">
    <div id="kadoIn">
      <img src="https://feeldreams.github.io/kadoin.png" alt="Kado">
    </div>
    <p id="ket">Klik Kadonya!</p>

    <!-- Stiker untuk Konten -->
    <div class="kumpulanstiker">
      <img src="https://feeldreams.github.io/bunga.gif" class="fotostiker" alt="Bunga">
      <img src="https://feeldreams.github.io/pusn.gif" class="fotostiker" alt="Kucing">
      <img src="https://feeldreams.github.io/pandacoklat.gif" class="fotostiker" alt="Panda">
    </div>

    <p id="halo" class="halo"></p>

    <!-- Pesan dan Tombol -->
    <blockquote id="bq">
      <p id="kalimat">Aku Ada Sesuatu Nih 🤣❤️</p>
      <p id="pesan1">Klik 4 LOVE di Bawah! 😆❤️</p>
      <div id="kolombaru">
        <li id="lv1">🤍</li>
        <li id="lv2">🤍</li>
        <li id="lv3">🤍</li>
        <li id="lv4">🤍</li>
      </div>
      <p id="pesan3">Ciee.. atep 12.12 🤣❤️</p>
      <p id="pesan4">Happy Birthday!</p>
    </blockquote>

    <div id="Tombol">
      <a id="By" href="#">&#128140; Lanjut</a>
    </div>
  </div>

  <script>
    const body = document.querySelector("body");
    const swalst = Swal.mixin({
      timer: 2300,
      allowOutsideClick: false,
      showConfirmButton: false,
      timerProgressBar: true,
      imageHeight: 90,
    });
    const audio = new Audio(document.getElementById("linkmp3").src);
    let fungsiAwal = 0;
    document.getElementById("kadoIn").onclick = function () {
      if (fungsiAwal === 0) {
        audio.play();
        fungsiAwal = 1;
      }
    };
  </script>

  <script src="https://malasid.github.io/html/hbd.js"></script>
</body>
</html>

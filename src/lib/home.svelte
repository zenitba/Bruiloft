<main>
    <section class="card">
      <img src="/Bloemen.png" class="flowers"  />
      <img src="/Bloemen.png" width="250" height="250" class="flowers-right" loading="lazy" />
      <header class="header">Welkom op Onze Bruiloft</header>
      <img src="/Logo.png" width="400" height="200" class="names-image"loading="lazy" />
      <a href="https://app.eventlens.ai/upload/tc3jgn" class="upload-button">Upload Hier Uw Foto's</a>
      <img src="/Koppel.png" width="300" height="300" class="couple" loading="lazy"/>
    </section>
  </main>

  <style>
    .card {
      background-color: #E4DCCE;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 40px 30px rgba(0, 0, 0, 0.1);
      text-align: center;
      position: relative;
      max-width: 400px;
      width: 100%;
      height: auto;
      z-index: 1;
    }
  
    .header {
      font-size: 2.2rem;
      font-weight: bold;
      margin-top: 6%;
    }
  
    .names-image {
      width: 100%;
      height: auto;
      margin-bottom: 7rem;
    }
  
    .upload-button {
      padding: 10px 20px;
      font-size: 1rem;
      border: 1px solid #000;
      background-color: #E4DCCE;
      border-radius: 5px;
      cursor: pointer;
      text-align: center;
      margin-top: 1rem;
      top: 69%;
      left: 32%;
      position: absolute;
      margin: auto;
      text-decoration: none;
      color: #000;
      z-index: 1;
    }
  
    .flowers {
      position: absolute;
      top: -10%;
      left: -18%;
      width: 250px;
      height: auto;
      transform: scale(1, 1) rotate(184deg);
      z-index: -2;
    }
  
    .flowers-right {
      position: absolute;
      bottom: -9%;
      right: -18%;
      width: 250px;
      height: auto;
      transform: scaleX(1);
      z-index: 1;
    }
  
    .couple {
      position: absolute;
      bottom: -1px;
      left: -70px;
      width: 300px;
      height: auto;
      z-index: 1;
    }
  
    @media (max-width: 768px) {
      .card {
        padding: 20px;
      }
  
      .header {
        font-size: 1.9rem;
      }
  
      .names-image {
        max-width: 90%;
      }
  
      .flowers,
      .flowers-right {
        max-width: 180px;
      }
  
      .couple {
        max-width: 190px;
      }
  
      .upload-button {
        font-size: 0.9rem;
        padding: 6px 9px;
      }
    }
  </style>
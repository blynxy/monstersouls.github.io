<script>
    import Counter from "./lib/Counter.svelte";
  </script>
  
  <main>
    <div class="header">
      <!-- Menu Navigation -->
      <div class="max-w-lg mx-auto">
        <ul class="w-full flex justify-center text-white">
          <li class="p-1">
            <a href="#description">
              <button class="nav-btn"
                >About</button
              >
            </a>
          </li>
          <li class="p-1">
            <a href="#steam">
              <button class="nav-btn"
                >Get Game!</button
              >
            </a>
          </li>
        </ul>
      </div>
    </div>
      <!-- LOGO -->
      <div class="parallax-header">
        <div class="parallax__group">
          <div class="parallax__layer back-1"></div>
          <div class="parallax__layer back-2"></div>
          <div class="parallax__layer back-3"></div>
          <div class="parallax__layer back-4"></div>
          <div class="parallax__layer back-5"></div>
        </div>
        
      </div>
  
      
      <div class="page-content bg-teal-400">
        <div class="max-w-lg mx-auto">
          <div class="logo-hero">
            <img
              src="/images/library_logo_transparent.png"
              alt="Montster Souls Logo"
            />
          </div>
        </div>
  
      <div class="video-hero drop-shadow">
        <div class="video mx-auto p-6">
          <div>
            <iframe
              class="drop-shadow"
              src="https://www.youtube.com/embed/ISjJu8B44NE?si=iPeF1-QkX2WDGPdz"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              referrerpolicy="strict-origin-when-cross-origin"
              allowfullscreen
            ></iframe>
          </div>
        </div>
      </div>
  
      <!-- Description Here -->
      <div class="max-w-2xl mx-auto pt-6">
        <div
          class="grid grid-cols-1 bg-slate-900/75 drop-shadow backdrop-blur rounded"
        >
          <div class=" space-y-7s text-white p-3">
            <a id="description">
              <h2 class="text-2xl text-center pt-6">Game Summary</h2>
            </a>
              <p class="pt-6 pb-2">
                <img
                  class="char-left
                   object-cover h-64 float-left pr-3 mt-3 img-left"
                  src="/images/characters/hero2.png"
                  alt="Hero"
                />
                <span class="img-left-container"></span>
                Guide a virgin adventurer through his first fights and help him learn both about himself and how to use the powers he didn't realize he had. Experience an involved story that slowly reveals more about the world about you as you journey through multiple visually appealing and varied locations, from forests to caves to castles.
              </p>
            <p class="pb-2">
              Monster Souls has challenging gameplay that requires strategic thinking beyond simply hitting the attack buttons. Defend yourself from monsters that want to defeat and dominate you-in that order... or surrender to them and let them have their way. Gain the power of monsters through intimate contact, and learn how to use their own forms and abilities against them for your victory!
            </p>
            <p>
              Gain a pair of companions to help you along your way. Develop their abilities to help you survive the trials ahead. You can even romance them, or instead spend your time with as many men as you can find.
            </p>
            <a id="characters">
              <h2 class="text-2xl text-center pt-6">Characters</h2>
            </a>
            <div
              class="bg-slate-200/10 rounded p-3 min-h-60 drop-shadow mt-3 mb-3"
            >
              <img
                class="char-right object-cover h-48 float-right pr-3"
                src="/images/characters/ash.png"
                alt="Ash"
                style="transform: scaleX(-1);"
              />
              <h1 class="text-lg pb-6">Ash</h1>
              <p class="text-amber-400">
                A quiet warlock's apprentice, he wields two daggers and dark magic. At first reticent about accepting help with his mission, he quickly comes to show interest in the Hero due to his unique powers. Can you win his heart, or will he be brooding alone?
              </p>
            </div>
  
            <div
              class="bg-slate-200/10 rounded p-3 min-h-60 drop-shadow mt-3 mb-3"
            >
              <img
                class="char-left object-cover h-48 float-left pr-3"
                src="/images/characters/lyric.png"
                alt="Lyric"
              />
              <h1 class="text-lg pb-6">Lyric</h1>
              <p class="text-amber-400">
                An archer with magical bardic powers, allowing him to heal and empower his allies. When Hero comes to his rescue, he vows to aid him in his journey... but the truth of his origins is shrouded in mystery. Will you help him to open up, or will his secrets spell doom for his (love) life?
              </p>
            </div>
  
            <!-- <div
              class="bg-slate-200/10 rounded p-3 min-h-60 drop-shadow mt-3 mb-3"
            >
              <img
                class="object-cover h-48 float-right pr-3"
                src="/images/characters/caspian.png"
                alt="Caspian"
                style="transform: scaleX(-1);"
              />
              <h1 class="text-lg pb-6">Caspian</h1>
              <p class="text-amber-400">
                Oh Caspian. He sure loves fishing up trouble! You'll catch him on
                the prowl around the docks and in extra fishy backroom places, if
                you know what I mean. ;D
              </p>
            </div> -->
          </div>
        </div>
      </div>
  
      <!-- Steam Store Page here -->
      <div class="max-w-2xl mx-auto">
        <div class="mt-6">
          <a id="steam"></a>
          <iframe
            title="Steam Page"
            class="content-center"
            src="https://store.steampowered.com/widget/2432930/"
            frameborder="0"
            width="100%"
            height="300"
            style="max-width: 100%; max-height: 267px;"
          ></iframe>
        </div>
      </div>
    </div>
  
    <!-- footer -->
    <div class="w-full bg-slate-800 p-3 text-white">
      <div class="max-w-2xl min-h-40 mx-auto">
        <div class="flex flex-cols-2">
          <div class="flex-1">
            <h2>Links</h2>
            <ul>
              <li>
                <a href="https://www.patreon.com/monstersouls">
                  <i class="fa-solid fa-patreon">Patreon</i>
                </a>
              </li>
              <!-- <li>
                <i class="fa-solid fa-discord">Discord</i>
              </li> -->
              <li><a href="https://store.steampowered.com/app/2432930/Monster_Souls/">
                <i class="fa-solid fa-steam">Steam</i>
              </a>
              </li>
              <li>
                <a href="https://twitter.com/monster_souls">
                  <i class="fa-solid fa-twitter">Twitter</i>
                </a>
              </li>
            </ul>
          </div>
  
          <div class="flex-1">Contact Us!</div>
        </div>
      </div>
    </div>
  </main>
  
  <style>
  .parallax-header {
    height: 100vh;
    overflow-x: hidden;
    overflow-y: auto;
    perspective: 300px;
  }
  .parallax__group {
    position: relative;
    height: 100vh;
    width: 100vw;
    transform-style: preserve-3d;
  }
  .parallax__layer {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
  }
  
  .back-1 {
    transform: translateZ(-400px) scale(2.5);
    height: 100px;
    background: #f23413;
    z-index: 1;
  }
  .back-2 {
    transform: translateZ(-300px) scale(2);
    height: 100px;
    background: #3da124;
    z-index: 2;
  }
  .back-3 {
    transform: translateZ(-200px) scale(2);
    height: 100px;
    background: #471ac4;
    z-index: 3;
  }
  .back-4 {
    transform: translateZ(-100px) scale(1.5);
    height: 100px;
    background: #d3c1c2;
    z-index: 4;
  }
  .back-5 {
    transform: translateZ(0);
    height: 100px;
    background: #1399f2;
    z-index: 5;
  }
  
  
  
  
  
  
  
  
  
  :root {
    --img-left: -160px;
  
  }
    .static-bg-top {
      position: fixed;
      min-height: 40vh;
      width: 100%;
      z-index: -100;
      float: left;
    }
    @media (max-height: 900px) {
      .static-bg-top {
        height: 100vh;
      }
    }
    .page-content {
      width: 100%;
      height: 100%;
      background: #FBEEBA;
      /* background: no-repeat center url("/images/mantrap--thirsty.jpg"); */
      background-size: cover;
      font-family: comicFont;
    }
    .header {
      min-height: 40vh;
      background: no-repeat url("/images/faerie-realm.jpg");
      background-position: 75%;
      background-size: cover;
      background-attachment: fixed;
    }
    .video-hero {
      margin: 0px auto;
      background: center url("/images/library_hero.png");
      background-size: cover;
    }
    .video {
      max-width: 680px;
    }
    .video > div {
      position: relative;
      padding-bottom: 60%;
      height: 0px;
    }
  
    .video iframe {
      position: absolute;
      top: 0px;
      left: 0px;
      width: 100%;
      height: 100%;
    }
  
    .fa-solid {
      font-family: "Font Awesome", sans-serif !important;
    }
  
    .title-font {
      font-family: titleFont;
    }
  
    .nav-btn {
      background: url('/images/ui/paint_strokes_dark_1.png');
      background-size: 100% 100% ;
      min-width: 120px;
      height: 1.5em;
      font-size: 1.5em;
      margin-right: .5em;
      padding: 0 1em 0 .5em;
      font-weight: 600;
      text-shadow: 3px 3px #000000;
    }
    a:hover {
      color: #d1c19a;
    }
    .logo-hero {
      filter: drop-shadow(10px 10px 10px);
    }
  
    .char-right {
      filter: drop-shadow(6px 6px 6px #0000009d);
      display: inline-flex;
      position: absolute;
      right: -150px;
    }
    .char-left {
      filter: drop-shadow(-6px 6px 6px #0000009d);
      display: inline-flex;
      position: absolute;
      left: -150px;
    }
  
  
    @font-face {
      font-family: titleFont;
      src: url("/fonts/ACasionPro-Bold.otf");
    }
    @font-face {
      font-family: comicFont;
      src: url("/fonts/Laffayette_Comic_Pro.ttf");
    }
  </style>
  
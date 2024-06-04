<script>
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <div class="static-bg-top min-h-2xl"></div>
  <div class="header">
    <!-- LOGO -->
    <div class="max-w-lg mx-auto">
      <div class="logo-hero">
        <img
          src="/images/library_logo_transparent.png"
          alt="Montster Souls Logo"
        />
      </div>
    </div>

    <!-- Menu Navigation -->
    <div class="max-w-lg mx-auto">
      <ul class="w-full flex justify-center text-amber-700">
        <li class="p-1">
          <a href="#description">
            <button class="rounded-lg bg-cyan-400/80 backdrop-blur p-1"
              >About</button
            >
          </a>
        </li>
        <li class="p-1">
          <a href="#characters">
            <button class="rounded-lg bg-cyan-400/80 backdrop-blur p-1"
              >The Bois</button
            >
          </a>
        </li>
        <li class="p-1">
          <a href="#steam">
            <button class="rounded-lg bg-cyan-400/80 backdrop-blur p-1"
              >Get Game!</button
            >
          </a>
        </li>
      </ul>
    </div>
  </div>

  <div class="page-content bg-teal-400">
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
                class="object-cover h-32 float-left pr-3 mt-3"
                src="/images/characters/hero2.png"
                alt="Hero"
              />
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
              class="object-cover h-48 float-right pr-3"
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
              class="object-cover h-48 float-left pr-3"
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
    background: #bdc990;
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

  @font-face {
    font-family: titleFont;
    src: url("/fonts/ACasionPro-Bold.otf");
  }
  @font-face {
    font-family: comicFont;
    src: url("/fonts/Laffayette_Comic_Pro.ttf");
  }
</style>

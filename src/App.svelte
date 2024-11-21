<script>
  import Counter from "./lib/Counter.svelte";

    let year = new Date().getFullYear();
</script>

<main>

  <!-- <div class="navbar text-center">
    <ul>
      <li class=""><a href="#InputHeroGames">InputHero Games</a></li>
      <li class=""><a href="#steam">Buy Game!</a></li>
    </ul>
  </div> -->
  <div class="header-image">
  </div>
  <!-- 
  <div class="parallax-header">
    <div class="parallax__group">
        <div class="parallax__layer back-0" data-speed="95"></div> 
        <div class="parallax__layer back-1" data-speed="89"></div>
      <div class="parallax__layer back-2" data-speed="69"></div>
      <div class="parallax__layer back-3" data-speed="49"></div>
      <div class="parallax__layer back-4" data-speed="40"></div>
      <div class="parallax__layer back-5" data-speed="35"></div>
      <div class="parallax__layer back-6" data-speed="30"></div>
      <div class="parallax__layer back-7" data-speed="20"></div> 
    </div>
  </div>
  -->
  <!-- <div class="page-top-image"></div> -->
    <!-- Steam Store Page here -->
  <div class="w-full steam-embed">
    <div class="max-w-2xl mx-auto steam-embed">
      <div class="pt-6">
        <a id="steam"><span></span></a>
        <iframe
        title="Steam Page"
        class="content-center"
        src="https://store.steampowered.com/widget/2432930/"
        frameborder="0"
        width="100%"
        height="220"
        style="max-width: 100%; max-height: 220px; z-index: 10;"
        ></iframe>
      </div>
    </div>
  </div>
  <div class="page-content-top-image w-full"></div>

  <div class="page-content pt-8">
    
  
      <!-- Description Here -->
      <div class="max-w-2xl mx-auto">
        <div
          class="grid grid-cols-1 bg-slate-900/75 drop-shadow backdrop-blur rounded-lg mb-6"
        >
          <div class=" space-y-7s text-white p-3">
            <a id="description">
              <h2 class="text-2xl text-center pt-6">Game Summary</h2>
            </a>
              <p class="pt-6 pb-2">
                
                
                <span class="char-left-box h-64">
                  <img
                    class="char-left object-cover"
                    src="/images/characters/hero_portrait.png"
                    alt="Hero"
                  />
                </span>
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
            <h1 class="text-lg pb-6">Ash</h1>
            <p class="text-amber-400">
                <img
                  class="char-right object-cover p-3"
                  src="/images/characters/ash_portrait.png"
                  alt="Ash"
                  style="transform: scaleX(-1);"
                />
                A quiet warlock's apprentice, he wields two daggers and dark magic. At first reticent about accepting help with his mission, he quickly comes to show interest in the Hero due to his unique powers. Can you win his heart, or will he be brooding alone?
              </p>
            </div>
  
            <div
              class="bg-slate-200/10 rounded p-3 min-h-60 drop-shadow mt-3 mb-3"
            >
            <a href="#lyric">
              
              </a>
              <h1 class="text-lg pb-6">Lyric</h1>
              <p class="text-amber-400">
                <img
                class="char-right object-cover p-3"
                src="/images/characters/lyric_portrait.png"
                alt="Ash"
                style="transform: scaleX(-1);"
              />
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
      <div class="page-content-bottom-image w-full"></div>

      <div class="video-hero drop-shadow p-6">
        <div class="video mx-auto p-6">
          <div>
            <iframe
              class="drop-shadow rounded-lg"
              src="https://www.youtube.com/embed/1VjXhh7XDTM?si=yJCmA2DdmebZT_vH"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              referrerpolicy="strict-origin-when-cross-origin"
              allowfullscreen
            ></iframe>
          </div>
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
                <strong>Patreon</strong>
              </a>
            </li>
            <!-- <li>
              <i class="fa-solid fa-discord">Discord</i>
            </li> -->
            <li><a href="https://store.steampowered.com/app/2432930/Monster_Souls/">
              <strong>Steam</strong>
            </a>
            </li>
            <li>
              <a href="https://twitter.com/monster_souls">
                <strong>Twitter</strong>
              </a>
            </li>
          </ul>
        </div>

        <div class="flex-1">&copy; {year} InputHero</div>
      </div>
    </div>
  </div>
    
</main>
<style>
.navbar {
  position: absolute;
  width: 100%;
  height: 3em;
  z-index: 100;
  color: white;
  display: inline;
}
.navbar li {
  display: inline;
  background: url('/images/ui/paint_strokes_dark_1.png');
  background-size: 100% 100% ;
  min-width: 120px;
  height: 3em;
  font-size: 1.5em;
  margin-right: .5em;
  padding: 0 1em 0 .5em;
  font-weight: 600;
  text-shadow: 0px 0px 10px #ffffff;
}
.header-image {
  height: 400px;
  width: 100%;
  background: no-repeat center url("../images/monster_souls_banner2.jpg") #a8480c;
  background-size:auto 100%;
  z-index: 10;
}
@media(max-width: 360px){
  .header-image {
    height: 150px;
    /* background:  fit url("../images/monster_souls_banner.jpg") #a8480c; */

  }
}
@media(min-width: 361px ) and ( max-width: 1000px){
  .header-image {
    height: 200px;
  }
}
.parallax-header {
  height: 80vh;
  overflow-x: hidden;
  overflow-y: auto;
  perspective: 1px;
  scroll-behavior: smooth;
  background-color: #44a4fa;
}
.parallax__group {
  position: absolute;
  transform-style: preserve-3d;
  top:0;right:0;left:0;bottom:0;
  /* transform: translateY(50%); */
}
.parallax__layer {
  position: absolute;
  height: 80vh;
  top:0;right:0;left:0;bottom:0;
}
.back-0 {
  /* transform: translateZ(-9px); */
  background: no-repeat url('/images/parallax/parallax0.jpg');
  background-position: bottom;
  background-size: inherit;
  z-index: -11;
}
.back-1 {
  /* transform: translateZ(-7px); */
  background: no-repeat url('/images/parallax/parallax1alt.png');
  background-position: bottom;
  background-size: inherit;
  /* height: 300px; */
  z-index: -10;
}
.back-2 {
  /* transform: translateZ(-6px); */
  background: no-repeat url('/images/parallax/parallax2alt.png');
  background-position: bottom;
  background-size: inherit;
  z-index: -9;
}
.back-3 {
  /* transform: translateZ(-5px); */
  background: no-repeat url('/images/parallax/parallax3alt.png');
  background-position: bottom;
  background-size: inherit;
  z-index: -8;
}
.back-4 {
  /* transform: translateZ(-4px); */
  background: no-repeat url('/images/parallax/parallax4alt.png');
  background-position: bottom;
  background-size: inherit;
  z-index: -7;
}
.back-5 {
  /* transform: translateZ(-4px); */
  background: no-repeat url('/images/parallax/parallax5alt.png');
  background-position: bottom;
  background-size: inherit;
  z-index: -6;
}
.back-6 {
  /* transform: translateZ(-2px); */
  background: no-repeat url('/images/parallax/parallax6alt.png');
  background-position: bottom;
  background-size: inherit;
  z-index: -4;
  top:0;right:0;left:0;bottom:0;
}
.back-7 {
  /* transform: translateZ(-1px); */
  background: no-repeat url('/images/parallax/parallax7alt.png');
  background-position: bottom;
  z-index: -3;
}
.page-top-image {
  /* transform: translateZ(-1px); */
  height: 200px;
  background: no-repeat url('/images/parallax/meon.png');
  background-position: bottom;
  background-size: inherit;
  position: absolute;
  z-index: 1;
  top:0;right:0;left:0;bottom:0;

}
.page-content-top-image {
  height: 429px;
  position: absolute;
  background: repeat-x url('/images/parallax/cavetop.png');
  filter: drop-shadow(-6px 6px 6px #0000009d);

}
.page-content-bottom-image {
  position: absolute;
  height: 200px;
  translate: 0 -100%;
  background: repeat-x center url('/images/parallax/cavebottom.png');
  filter: drop-shadow(-6px 6px 6px #0000009d);
  z-index:-1;
}

.char-right {
  border-radius: 50%;
  filter: drop-shadow(6px 6px 6px #0000009d);
  display: inline-flex;
  float: right;
}
.char-left {
  border-radius: 50%;
  filter: drop-shadow(-6px 6px 6px #0000009d);
  display: inline-flex;
  float: left;
}


@media (max-height: 1000px) {
  .back-0 {
    /* background: no-repeat url('/images/parallax/parallax0_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-1 {
    /* background: no-repeat url('/images/parallax/parallax1_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-2 {
    /* background: no-repeat url('/images/parallax/parallax2_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-3 {
    /* background: no-repeat url('/images/parallax/parallax3_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-4 {
    /* background: no-repeat url('/images/parallax/parallax4_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-5 {
    /* background: no-repeat url('/images/parallax/parallax5_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-6 {
    /* background: no-repeat url('/images/parallax/parallax6_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .back-7 {
    /* background: no-repeat url('/images/parallax/parallax7_small.jpg'); */
    background-size: auto 100%;
    background-position: top;
  }
  .parallax-header {
    height: 50vh;
  }
  .page-top-image {
    /* background: no-repeat url('/images/parallax/parallax8_small.jpg'); */
    background-size: 100%;
    height: 50vh;
  }

}
.steam-embed {
  background-color: #0a0a0a;
}
.page-content {
  width: 100%;
}
:root {
  background-color: #1f1c25;
  /* background-image: url('/images/test-tile.jpg');
  background-size: 20%;
  background-attachment: fixed; */


}

  @font-face {
    font-family: titleFont;
    src: url("/fonts/ACasionPro-Bold.otf");
  }
  @font-face {
    font-family: comicFont;
    src: url("/fonts/Laffayette_Comic_Pro.ttf");
  }

  .video-hero {
      margin: 0 auto;
      background: no-repeat center url("/images/library_hero2.png");
      background-size: auto 100%;
      background-color: black;
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


  /** LIGHTBOX MARKUP **/

.lightbox {
  /* Default to hidden */
  display: none;

  /* Overlay entire screen */
  position: fixed;
  z-index: 999;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  
  /* A bit of padding around image */
  padding: 1em;

  /* Translucent background */
  background: rgba(0, 0, 0, 0.8);
}

/* Unhide the lightbox when it's the target */
.lightbox:target {
  display: block;
}

.lightbox span {
  /* Full width and height */
  display: block;
  width: 100%;
  height: 100%;

  /* Size and position background image */
  background-position: center;
  background-repeat: no-repeat;
  background-size: contain;
}
</style>

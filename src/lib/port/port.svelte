<script>
  let tye = '/albums/tye.webp'
  let yardart1 = '/albums/talking.webp'
  let grace = '/albums/gracesmiles.webp'
  let shanny = '/albums/shes_not_me_art.webp'
  let tracey = '/albums/tracey.webp'
  let yardart2 = '/albums/yardart.webp'
  let sour = '/albums/sourmagic.webp'
  let magnolia = '/albums/magnolia.webp'
  let flyby = '/albums/flyby.webp'
  let contra = '/albums/no_need.webp'
  

</script>


<section class=" min-h-screen mx-auto shadow-lg bg-white grid grid-cols-1 gap-5">
  <div class="container px-6 py-6 mx-auto">
    <div class="music grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-8 xl:gap-12 mt-8 xl:mt-12">

      <div class="music_bg group" style="background-image:url({tye})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Troubled Heart</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Tye David</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Mastered</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url({ yardart1 })">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Talking in our Sleep (Single)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Yard Art</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Mastered for Streaming and Vinyl</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url({grace})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Just a Dream (EP)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Grace Smiles</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Mixed Tracks 3 and 5, Mastered Tracks 2-5</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url({shanny})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">She's Not Me (Single)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Shanny & The East Men</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Mastered</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url({tracey})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Changes (EP)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Tracey Paul</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Produced, Recorded, Mixed</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url({yardart2})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Seft-Titled (Album)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Yard Art</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Mastered for Streaming and Vinyl</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url({sour})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Forbidden Fruit (Album)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Sour Magic</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Mixed/Mastered Tracks 6 and 8, Mastered Track 7</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>

      <div class="music_bg group" style="background-image:url({magnolia})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Coalescence (Album)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Magnolia Grove</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Written, Produced, Recorded, Mixed</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>

      <div class="music_bg group" style="background-image:url({flyby})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Silver Crane (Album)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Fly By Midnight</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Assistant Engineering on Track 12</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>

      <div class="music_bg group" style="background-image:url({contra})">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">No Need For Words (EP)</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Subcontra</h3>
          <p class="mt-2 text-xs tracking-wider text-white uppercase">Produced, Recorded, Mixed, and Mastered</p>
          <button class="listen_btn "><a href="/">Listen Here</a></button>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
.music {
  @apply grid grid-cols-1 gap-8 mt-8 xl:mt-12 xl:gap-12 md:grid-cols-2 xl:grid-cols-3;
}

.music_bg {
  @apply overflow-hidden bg-cover bg-center rounded-lg h-96;
}

.music_text {
  @apply flex flex-col justify-center w-full h-full px-8 py-4 transition-opacity duration-700 opacity-0 backdrop-blur-sm bg-gray-800/60 group-hover:opacity-100;
}

.listen_btn {
	@apply flex flex-col justify-start text-white mt-14 hover:opacity-80 hover:underline duration-200;
}
</style>

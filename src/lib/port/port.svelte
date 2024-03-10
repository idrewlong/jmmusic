<section class=" min-h-screen mx-auto shadow-lg bg-white grid grid-cols-1 gap-5">
  <div class="container px-6 py-6 mx-auto">
    <div class="music grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 gap-8 xl:gap-12 mt-8 xl:mt-12">
      
      <div class="music_bg group" style="background-image:url('/guitar.webp')">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Album Name</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Artist Name</h3>
          <p class="mt-2 text-sm tracking-wider text-orange-500 uppercase">Mixed and Mastered</p>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url('/pedals.webp')">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Album Name</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Artist Name</h3>
          <p class="mt-2 text-sm tracking-wider text-orange-500 uppercase">Mixed and Mastered</p>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url('/drum_two.webp')">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Album Name</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Artist Name</h3>
          <p class="mt-2 text-sm tracking-wider text-orange-500 uppercase">Mixed and Mastered</p>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url('/compress.webp')">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Album Name</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Artist Name</h3>
          <p class="mt-2 text-sm tracking-wider text-orange-500 uppercase">Mixed and Mastered</p>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url('/amp.webp')">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Album Name</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Artist Name</h3>
          <p class="mt-2 text-sm tracking-wider text-orange-500 uppercase">Mixed and Mastered</p>
        </div>
      </div>
      
      <div class="music_bg group" style="background-image:url('/pedal_2.webp')">
        <div class="music_text">
          <h2 class="mt-4 text-xl font-semibold text-white capitalize">Album Name</h2>
          <h3 class="mt-4 text-md font-semibold text-white capitalize">Artist Name</h3>
          <p class="mt-2 text-sm tracking-wider text-orange-500 uppercase">Mixed and Mastered</p>
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
</style>

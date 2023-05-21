<template>
  <div
    class="text-nord4 rounded-lg border-nord7 absolute mb-5 mr-5 text-center bottom-0 right-0 border-solid border-2 w-60"
  >
    <p>La ketchupas - Asereje</p>
    <audio id="audio" src="/keczup.mp3"></audio>
    <button class="mr-0.5 mb-0.5 rounded-lg border-nord7 border-solid border-2 " onclick="audio.play()">
      <p class="mr-1 ml-1"><Icon name="fa6-regular:circle-play" class="mb-1 mr-0.5" />Play</p>
    </button>
    <button class="mb-1/2 rounded-lg border-nord7 border-solid border-2" onclick="audio.pause(); audio.currentTime = 0;">
      <p class="mr-1 ml-1"><Icon name="fa6-regular:circle-stop" class="mb-1 mr-0.5" />Stop</p>
    </button>
  </div>
</template>
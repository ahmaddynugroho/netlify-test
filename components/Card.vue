<template>
  <div
    class="card bg-repeat-x bg-local bg-top bg-contain m-5 rounded-md px-4 pt-24 pb-16 relative transition duration-150 hover:-translate-y-4 transform"
  >
    <span> {{ original_message }} </span>

    <button
      class="absolute left-0 bottom-0 transition duration-150 transform hover:scale-110"
    >
      <img class="w-16" src="../assets/img/btnreference.png" />
    </button>
    <span class="absolute right-0 bottom-0 font-light m-4">
      - Y E S man
    </span>
  </div>
</template>

<script>
export default {
  props: [
    'messageID',
    'username',
    'region',
    'original_message',
    'translated_english_message',
    'translated_japanese_message',
  ],
}
</script>

<style>
.card {
  background-image: url('../assets/img/card2.png');
  /* bg card 1 */
  /* background-color: #724683; */
  /* bg card 2 */
  background-color: #fd418d;
  /* bg card 3 */
  /* background-color: #6e4080; */
}
/* {
        "translated_japanese_message": "は運動をします、そのようなブラインドが前向",
        "original_message": "Culpa ut nulla cupidatat proident dolore eu enim tempor aliquip anim ad anim.",
        "messageID": 1,
        "translated_english_message": "Mollit nisi elit qui consectetur sint laboris incididunt exercitation esse aliquip quis cupidatat minim.",
        "username": "Y E S man",
        "region": "id"
} */
</style>

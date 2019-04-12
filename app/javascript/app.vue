<template>
  <div id="ping-me">
    <p>{{ message }}</p>
    <input v-model="message">
  </div>
</template>

<script>
  export default {
    data: function() {
      return {
        messages: {},
        // messages: {1: 'IU', 2: 'Tiffany', 3: "Sooyoung", 4:"Julie"},
        // this essentially fills out each of the four text boxes per lists column with these strings
        lists: this.original_lists // essentially rails object that got inherited straight from erb
        // lists: starts out as an array of lists
        // will be dynamically reorderd and updated via our listMoved action
      }
  },
  }

</script>

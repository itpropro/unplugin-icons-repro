<script setup lang="ts">
import Meteor from '~icons/custom-icons/meteor'
// import Ghost from '~icons/custom-icons/ghost'
</script>

<template>
  <div>
    <div i-carbon-campsite text-4xl inline-block />
    <p text-2xl pb-4>
      unplugin-icons
    </p>
    <div pb-2>
      <p>Explicit import:</p>
      <meteor text-yellow-500 mx-auto />
    </div>
    <div>
      <p>Implicit import:</p>
      <ghost mx-auto />
    </div>
  </div>
</template>

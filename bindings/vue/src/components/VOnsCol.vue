<template>
  <ons-col v-on="unrecognizedListeners">
    <slot></slot>
  </ons-col>
</template>

<script>
  /* This file is generated automatically */
  import 'onsenui/esm/elements/ons-col';
  import { deriveEvents } from '../mixins';

  export default {
    name: 'v-ons-col',
    mixins: [deriveEvents]
  };
</script>
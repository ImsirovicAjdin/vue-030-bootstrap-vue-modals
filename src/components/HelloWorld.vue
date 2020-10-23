<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <b-button v-b-modal.modal-1>Launch demo modal</b-button>

    <b-modal id="modal-1" title="BootstrapVue">
      <p class="my-4">Hello from modal!</p>
    </b-modal>
  </div>
</template>

<script>
import { BButton, BModal } from "bootstrap-vue";

export default {
  name: "HelloWorld",
  components: {
    BButton,
    BModal,
  },
  props: {
    msg: String,
  },
};
</script>

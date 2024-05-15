<script lang="ts" setup>
import { mails } from "../data/mail";
import { accounts } from "../data/mail";
</script>
<template>
  <div class="flex">
    <Mail :accounts="accounts" :mails="mails" :nav-collapsed-size="4" />
  </div>
</template>

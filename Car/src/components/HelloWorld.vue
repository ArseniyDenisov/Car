<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      <a href="https://vk.com/im">хуй</a>
      <h1>

        Добро пожаловать
            на интернет-аукцион!
Торги начинаются! Ваша возможность сэкономить

      </h1>
     
    </h3>
  </div>
</template>


<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>




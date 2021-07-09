<template>
  <div v-html="$static.proverb.title" />
</template>
<static-query>
  query{
    proverb(id: "cfd68112cb417ddf24b7fe02c451f3a3"){
      title
    }
  }
</static-query>

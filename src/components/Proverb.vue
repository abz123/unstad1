<template>
  <!--<span v-html="$static.proverb.title" />-->
  <span>{{$static.proverb.title}}</span>
</template>
<static-query>
  query{
    proverb(id: "cfd68112cb417ddf24b7fe02c451f3a3"){
      title
    }
  }
</static-query>

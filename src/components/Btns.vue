<template>
  <div>
      <v-btn 
       class="ma-10" fab width="64"
        height="64" 
        v-for="(btn,index) in btns" 
        :key='index'
        target='_blank' 
         :href='btn.link'>
          <v-icon size="32" :color="btn.color">
              {{btn.icon }}
          </v-icon>
      </v-btn>

  </div>
</template>

<script>
export default {

  data: () => ({
    btns:[
        {
            icon:'mdi-twitter',
            color:'#1C9CEA',
            link:'https://twitter.com/sadafamininiia'
        },
         {
            icon:'mdi-discord',
            color:'#6E85D3',
            link:'https://discord.gg/6gQrAfm7wQ'
        },
         {
            icon:'mdi-linkedin',
            color:'#0077B0',
            link:'https://www.linkedin.com/in/sadafamininia/'
        },
         {
            icon:'mdi-telegram',
            color:'#2962ff',
            link:'https://t.me/computer_channell'
        },
        {
            icon:'mdi-youtube',
            color:'#FF0000',
            link:'https://www.youtube.com/channel/UCImHAgK2R4N8Hq3miFvJfQw'
        },


    ]
  }),
};
</script>

<style>

</style>
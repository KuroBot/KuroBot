const Discord = require('discord.js')
const bot = new Discord.Client()

bot.on('ready', function () {
  console.log("Je suis connecté !")
})

bot.login('NDQyOTc1MjgxODIxNTE1Nzc2.DdNBjw.bGT4QE1uVwSj6rJI6egIIWnHhCs')

bot.on('message', message => {
    if (message.content === 'ping') {
      message.reply('pong !')
    }
  })

  bot.on('guildMemberAdd', member => {
    member.createDM().then(channel => {
      return channel.send('Bienvenue sur mon serveur ' + member.displayName)
    }).catch(console.error)
  })

# Activitat 2: Documentació d'un bot de Discord

Crea un arxiu anomenat `2_discord.md`. Aquest document simularà la documentació d'un bot de Discord fet en JavaScript.

Inclou-hi els elements següents:

- Un títol de nivell 1: **Documentació del Bot de Discord**.
- Una imatge del logotip de Discord. Busca'n una a internet i copia'n la URL. El text alternatiu de la imatge ha de ser **Logotip de Discord**.
- La frase «Pots registrar la teva aplicació al Portal de Desenvolupadors de Discord.», on **Portal de Desenvolupadors de Discord** sigui un enllaç a <https://discord.com/developers/applications>.
- Un paràgraf amb aquest text: «Per fer que el bot respongui, escoltem l'esdeveniment messageCreate i utilitzem el mètode message.reply()». Aplica format de codi a `messageCreate` i `message.reply()`.
- Un bloc de codi multilínia amb el ressaltat de sintaxi activat per a JavaScript, que mostri aquest exemple:

```javascript
client.on('messageCreate', message => {
  if (message.content === 'ping') {
    message.reply('pong!');
  }
});
```


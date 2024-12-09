### Codigo chatbot realizado por Zendesk Answer Bot para automatizar las respuestas a los clientes.

```
<script type="text/javascript">
  window.zESettings = {
    webWidget: {
      answerBot: {
        suppress: false,
        title: {
          '*': 'Chat with us!'
        },
        contactOnlyAfterQuery: true,
        search: {
          labels: ['I would like help.']
        },
        avatar: {
          url: '#exemple',
          name: {
            '*': 'Company logo'
          }
        }
      }
    }
  };
</script>
```
> Puedes encontrar mas información en la [documetación oficial](https://developer.zendesk.com/api-reference/widget/answer-bot-api/) de Zendesk Answer Bot.
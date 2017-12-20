#twitter-bot #dataanalysis

Aqui um breve tutorial para a criação de um bot no twitter ou para coletar dados do mesmo.

1. Instalar o node js. https://nodejs.org/en/
2. Baixar a API chamada 'twit' no site https://www.npmjs.com/
3. Criar uma pasta no seu computador na qual você colocará todo o código da aplicação.
4. Dentro desta pasta no terminal, dê o comando 'npm init'.
5. Ele deve pedir uma série de informações para a criação do json (nome do projeto, versão, descrição e etc), coloque o que achar necessário, o que não for ou você não souber 
o que é dê enter.
6. Ele deve mostar o json criado. Confirme com sim aso você esteja de acordo.
9. Dentro da mesma pasta dê o comando 'npm install twit --save', ele instalar e irá inserir a API como uma dependência no seu código json.
10. Crie um novo arquivo .js onde você deve implementar o bot.
11. Abra o link  https://github.com/ttezel/twit e conforme a descrição você notará que o objeto T criado necessita de
uma série de credenciais, estas serão informações do seu app do twitter.
12. Para criar um twitter app, vá em:  https://apps.twitter.com/. 
13. Complete com os dados em keys and access token' da sua app.
14. Para testar copie o código: 
T.post('statuses/update', { status: 'hello world!' }, function(err, data, response) {
  console.log(data)
})
15. Para testar, digite no terminal 'node nomedoseuarquivo.js'. Caso esteja funcionando o post será feito na sua conta.

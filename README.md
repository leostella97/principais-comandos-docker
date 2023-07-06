# Principais Comandos Docker

## A revolução da programação simplificada, como o Docker pode transformar sua experiência de desenvolvimento e impulsionar seus projetos!

<code>docker run</code>: Esse comando é usado para <b>executar um contêiner</b>. Ele baixa a imagem do contêiner do registro público do Docker, se ela ainda não estiver presente localmente, e inicia a execução. Por exemplo, para executar um contêiner do Ubuntu, você pode usar o comando <code>docker run ubuntu</code>.
<br><br>
<code>docker pull</code>: Esse comando é usado para <b>baixar uma imagem</b> do registro público do Docker para o seu sistema local, sem executá-la. Por exemplo, para baixar a imagem do Ubuntu, você pode usar o comando <code>docker pull ubuntu</code>.
<br><br>
<code>docker images</code>: Esse comando <b>lista todas as imagens</b> de contêineres que você tem armazenadas localmente no seu sistema. Ele exibe informações como o <i>nome da imagem, o ID da imagem e o tamanho</i>.
<br><br>
<code>docker ps</code>: Esse comando <b>lista todos os contêineres em execução</b> no momento. Ele exibe informações como o ID do contêiner, o nome do contêiner e o status de execução.
<br><br>
<code>docker stop</code>: Esse comando é usado para <b>interromper a execução</b> de um contêiner em execução. Você precisa especificar o ID ou o nome do contêiner que deseja parar. Por exemplo, para parar um contêiner com o ID "cont_teste", você pode usar o comando <code>docker stop cont_teste</code>.
<br><br>
<code>docker rm</code>: Esse comando é usado para <b>remover um contêiner que não está em execução</b>. Você precisa especificar o ID ou o nome do contêiner que deseja remover. Por exemplo, para remover um contêiner com o ID "cont_teste", você pode usar o comando <code>docker rm cont_teste</code>.
<br><br>
<code>docker rmi</code>: Esse comando é usado para <b>remover uma imagem de contêiner do seu sistema local</b>. Você precisa especificar o ID ou o nome da imagem que deseja remover. Por exemplo, para remover uma imagem com o ID "cont_teste", você pode usar o comando docker rmi cont_teste.
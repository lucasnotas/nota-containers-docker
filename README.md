# nota-containers-docker
Notas: Abiente virtua ....

<h1>Criando container</h1>
<p>Baixa imagem (iso) do Ubuntu</p>

  	docker pull ubuntu
<br/>
<p>Cria e já entra no terminal do container</p>

	docker run -it --name meu_ubuntu ubuntu bash
<br/>
<h1>Manipulando container</h1>
<p>Listar Container ativos</p>

	docker ps
<br/>
<p>Lita todos(ativos e parados)</p>

 	docker ps -a
</br>
<h1>Comandos</h1>
<p>PARANDO um Conationer</p>

 	docker stop meu_ubuntu
</br>
<p>INICIANDO um Conationer</p>

 	docker start meu_ubuntu
</br>
<p>ENTRA em um container que ja esta rodando</p>

 	docker exec -it meu_ubuntu bash
</br>
<p>PAUSANDO desativa temporariamente</p>

 	docker pause meu_ubuntu
</br>
<p>PLAY DESPUASAR</p>

 	docker unpause meu_ubuntu
</br>
<p>DELETAR (stop primeiro)</p>

 	docker rm meu_ubuntu
</br>
<p>DELETAR ISO (opcional)</p>

 	docker rmi ubuntu
</br>

# Arquivio para testes e aprendizados da Alura - Curso GIT & GITHUB

>Status : Em desenvolvimento

Exemplo do que por no readme:
- Para rodar esse projeto na máquina, por favor digite :
lol
```
node app.js
```

## Anotações/Explicações de codigos do git e github

	cd = para entrar dentro de uma pasta. EX: cd desctop
	ls = com esse comando veremos o nome dos arquivos dentro dessa pasta.
	git pull = é uma forma de fazer a atualização. Puxa tudo que está lá para atualizar aqui.
	git status = para ver o que tem de diferente nesse projeto.
	git commit index.html -m "linkando o app.js com o html" = Faz o commit especifico do arquivo index apenas.
	git push origin main = Empurrar todos os commits, posso ter feito mais de um,para o repositório origem.
	git commit . -m "adicionando um console log" = faz commit de todo o projeto.
	git restore --source a0c893b = fazer a gente voltar para um determinado momento da aplicação. Esse comando pode realizar
		retornos em apenas uma pagina do commit colacando o seu nome, ou todo o commit colocando . depois do hash
	git checkout -b nomeBranche =   cria uma branch (ramificação) diferente.
	git switch nomeRamificação =  voltar para a branch especificada.
	git push origin RepositorioEscolhido = manda o codigo para determinada origem, repositorio.
	git branch = mostra as branches que estão disponíveis nesse projeto e em qual branch eu estou.
	git merge RepositorioQueQueroJuntarNoMain =  juntar a branch main com a branch que quero.

	git clone:
		git clone = É usado para selecionar um repositório existente e criar um
		 	clone ou uma cópia dele em um repositório local. 
		git clone https://nome_do_projeto_que_deseja_clonar = Para clonar projetos, seus ou de terceiros,
		 	da web na sua maquina local. 
		git clone <repositorio> <meu-projeto-clone> = com esse comando vc clona o repositório para uma pasta específica.
		git clone -branch new_feature <repositorio> = Você também pode configurar o git clone e clonar o repositório
			a partir de uma branch específica, diferente da original. 		

	git log :
		git log = conseguirmos visualizar todo o histórico de alterações.
		git log --oneline  = mostra todos os commits que fizemos nesse repositório de uma forma bem simples e resumida.
		git log -p = vemos mais como as alterações do commit
		git log --author="user_name" = Também podemos pesquisar as informações do autor daquele commit com o comando.
		git log --since=1.month.ago --until=1.day.ago = E pesquisar informações por data
			No comando acima, estamos buscando as informações do commit desde um mês 
			atrás até um dia atrás.
			Você também pode formatar a visualização das informações de commit com o comando:
		git log --pretty="format:%h %s" = Este traz o hash seguido da mensagem de commit.
					/formata a visualização da data dos dados
 

### Jargões :

	diff do seu commit: alterações realizadas via seu commmit, para que o outro desenvolvedor veja o que foi alterado.
	hash : sequência de caracteres em hexa que identifica esse commit como sendo único.
	main: que é o nosso projeto principal, um projeto que buscamos que não tenha erros e falhas.
	branches - considere "branches" como ramificações da nossa aplicação 

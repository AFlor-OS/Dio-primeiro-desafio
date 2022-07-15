**GIT e GITHUB**



**Navegação via Command Line e interface de instalação:**

**Comandos básicos para um bom desempenho no terminal:**

​	**-cd** -> change direct -> vai “entrar” em uma pasta por ter sido direcionado para ela 

​	**-cd ..** -> volta uma camada no repositório 

​	**-ls** -> lista os diretórios encontrados na pasta 

​	**-mkdir** -> cria uma pasta -> mkdir __(nome)____

​	**-rm -rf** -> remove uma pasta/arquivo. 

​	**-clear** -> limpa o terminal. (Control + L)

​	- **tecla TAB** -> auto-completa 

​	-**ls -a** -> mostra arquivos ocultos 

​	**- touch** -> cria arquivo -> touch ___(nome do arquivo)___.(tipo de arquivo).

​	**- mv** -> mover arquivo -> ex: $ mv strogonoff.md ./receitas/ -> moveu o arquivo strogonoff para a pasta receitas 



**Entendendo como o git funciona por debaixo dos panos:**

**Tópicos fundamentais:**

​	**-> SHA1:**

​		significa “Secure hash algorithm”, e é um, conjunto de funções hash criptográficas projetadas pela NSA (agência de segurança nacional dos EUA) -> a encriptação gera conjunto de caracteres identificados de 40 dígitos (único, com função de identificação, também podendo ser definido como uma forma curta de identificar o arquivo) 

**Objetos internos do git:**

​	**->BLOBS**(tipo de objeto): Um objeto que contem meta dados (contem um SHA1).

​	**->TREES**: armazenam blobs, e apontam para commits ou outras arvores, ou seja, contem toda a estrutura de identificação de um arquivo

​	**->COMMITS**: objeto q junta tudo, apontado para uma tree, um parente, um autor, uma mensagem e um timestamp -> o SHA1 desse comia e2 o hash de toda essa informação 

**O Git é um sistema distribuído(pois seu repositório hosteado em uma nuvem, e la se encontra aversão mais atualizada do seu código, onde diversas pessoas podem contribuir para sua atualização) seguro (pois é muito difícil modificar o commit).**



**Chave SSH e token:**

​	Chave SSH:

​		maneira segura e incriminada de criar uma conexão entre duas maquinas (o computador e o servidor do GitHub, por exemplo)

**Primeiros comandos com o Git**

​	**git init** - iniciar repositório do git

​	**git add** - mover arquivos e dar inicio ao versionamento 

​	**git commi**t - criar primeiro commit

​	**git status** - verificar o status do repositório local

​	**git remot**e -v : lista os repositórios remotos que eu possuo
# inicializando  git local

1* primeiro confira se o git está instalado:

```bash
git --version
```
2* agora confira os seus documentos

```bash
cd Documents; 
ls
```
3* agora configure 

```bash
git config --global user.name (seu nome)
 git config --global user.email (seu e-mail)
```
4* crie uma pasta cd
```bash
 mkdir  *notas(ou outro nome)
 ls{aqui mostra o que tem dentro da pasta}
 cd *notas/
 ls{aqui mostra o que tem dentro da pasta}
```
5* inicialize o git
```bash
git init
 ```
 6* abra com o visual studio code
 ```bash
 code .
```
7* escreva suas anotações, criando um arquivo com o nome de readme.md ,na pasta NOTAS.

8* aqui estão alguns comandos:
  - Git Branch

Esse comando é a ferramenta de administração de ramificações de uso geral. Permite criar ambientes de desenvolvimento isolados em um único repositório

   - Git checkout

Além de verificar commits(descrições) antigos e revisões de arquivos antigos, o git checkout também é a forma de navegar pelas ramificações existentes. Combinado com os comandos básicos do Git, é a maneira de trabalhar em determinada linha de desenvolvimento.

   - Git add

Move as alterações do diretório de trabalho para a área de staging(um ambiente de praparação). Assim, você tem a oportunidade de preparar um instantâneo antes de realizar o commit ao histórico oficial.

   - Git commit

Faz um commit do instantâneo preparado no histórico do projeto. Combinado com git add, esse processo define o fluxo de trabalho básico para todos os usuários do Git.

   - git fetch

A busca faz o download a partir da ramificação de outro repositório, junto com todos os commits e arquivos associados. Mas, não tenta integrar nada em o repositório local. Assim, você tem a oportunidade de inspecionar as alterações antes de fazer o merge no projeto

   - git pull

É a versão automatizada do git fetch. Faz o download de ramificação de um repositório remoto e faz a mesclagem imediata na ramificação atual. É o equivalente Git do svn update

   - Git push

É o oposto de buscar (com algumas ressalvas). Permite que você mova uma ramificação local para outro repositório, o que é um modo conveniente de publicar as contribuições. É semelhante ao svn commit, mas envia uma série de commits em vez de um único conjunto de alterações.

   - git status

Exibe o estado do diretório de trabalho e o instantâneo preparado. Utilize essa opção em conjunto com os comandos git add e o git commit para ver com precisão o que vai ser incluído no próximo instantâneo.








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
  git status -exibe as condições do diretório de trabalho e da área de staging.

git add <filename ou.> -promover alterações pendentes no diretório ativo para a área git staging.

git restore --staged <filename ou.> -restaurar algum arquivo ou o projeto por completo.

git branch <branchname> -permite criar, listar, renomear e excluir ramificações.

git checkout <branchname> -permite navegar entre ramificações criadas pelo git branch.

git checkout -b <branchname> -O objetivo dele é fazer a pessoa programadora mudar de branch.

git commit -m "<description> -é usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do Git.

git push -é usado para enviar o conteúdo do repositório local para um repositório remoto.

git branch -D <branchname> -é um ponteiro para as alterações feitas nos arquivos do projeto.

gif fetch -é um comando básico usado para baixar conteúdos de um repositório remoto.

git pull - é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.







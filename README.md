# Revisão de Git
Inicializando Repositorio git
```bash
git init
```
  Para visualizar os repositórios remotos, utilize o comando:

```bash
git remote -v
```
Saída:

```bash
origin  https://github.com/usuario/repositorio.git (fetch)
origin  https://github.com/usuario/repositorio.git (push)
```
Adicionando e Commitando Alterações
Adicione as alterações ao staged area com o comando:
```bash
git add nome_do_arquivo
```
ou para adicionar todas as alterações:
```bash
git add .
```
Em seguida, efetue o commit das alterações utilizando:
```bash
git commit -m "Mensagem do commit"
```

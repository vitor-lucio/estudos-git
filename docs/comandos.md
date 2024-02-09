# Comandos

### Configurações gerais
Lista todas as configurações definidas.
```
git config --list
```
Definir o nome da branch principal nos próximos repositórios criados.
```
git config --global init.defaultBranch <nome da branch>
```
### Configurações de usuário
Definir o usuário e e-mail que serão exibidos no histórico de commits do git.
```
git config --global user.name="<Nome do Colaborador>"
```
```
git config --global user.email="<email do colaborador>"
```
Visualizar o usuário e e-mail que estão definidos para histórico de commits do git.
```
git config --global user.name
```
```
git config --global user.email
```
### Repositório local
Transforma o diretório em um projeto git local.
```
git init
```
### Adicionando mudanças
Verifica o status atual da branch local com base em commits, untracked files e diferenças com relação a branch remota.
```
git status
```
Adiciona um arquivo/diretório na lista de arquivos rastreados pelo git na branch local.
```
git add <nome do arquivo/diretório>
```
Para adicionar todos os untracked files no diretório raiz.
```
git add .
```


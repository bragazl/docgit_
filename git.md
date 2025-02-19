# Comandos git

## init

*init* inicializa um novo repositório local

Exemplo:

```bash
$git init
```
## add

*add* adiciona arquivos para um commit

Exemplo:

```bash
$git add arquivo
```

## commit

*commit* relata alterações feitas nos arquivos ou pastas adicionadas 

Exemplo:

```bash
$git commit -m "bla bla bla"
```

## status

*status* mostra o estado atual do repositório

Exemplo:

```bash
$git status
```

## touch

*touch* serve para criar arquivos

Exemplo:

```bash
$touch cachorro
```

## mkdir

*mkdir* cria pastas

Exemplo:

```bash
$mkdir teste
```

## branch

*branch* lista, cria ou exclui branches

Exemplo:

### para listar
```bash
$git branch
```
### para criar
```bash
$git branch tst
```
### para remover
```bash
$git branch -d tst
```

## rm
Exemplo:

*rm* remove arquivos do diretório
```bash
$rm -r teste
```

## log
Exemplo:

*log* exibe o histórico de commits
```bash
$git log
```
## clone
Exemplo:

*clone* clona um repositório remoto
```bash
$git clone https://github.com/teste/testetestado.git
```

## pull & push

*pull* serve para **puxar** modificações
```bash
$git pull
```

*push* serve para **subir** alterações
```bash
$git push
```

## merge
Exemplo:

*merge* mescla alterações de branches diferentes
```bash
$git merge nomebranch
```
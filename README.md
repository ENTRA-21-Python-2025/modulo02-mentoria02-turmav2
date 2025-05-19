# Comandos Git Básicos

## git clone
- Clona um repositório remoto para sua máquina local
- Exemplo: `git clone https://github.com/usuario/repositorio.git`

## git fetch
- Atualiza as referências do repositório local com as do repositório remoto
- Não faz merge das alterações, apenas atualiza as referências

## git pull
- Combina `git fetch` e `git merge`
- Atualiza seu branch local com as alterações do repositório remoto
- Exemplo: `git pull origin main`

## git add .
- Adiciona todas as alterações do diretório atual ao stage
- Prepara os arquivos para serem commitados
- Exemplo: `git add .`

## git commit -m
- Cria um commit com as alterações que estão no stage
- O parâmetro -m permite adicionar uma mensagem descritiva
- Exemplo: `git commit -m "Adiciona nova funcionalidade"`

## git push
- Envia suas alterações locais para o repositório remoto
- Exemplo: `git push origin main`

## git create branch
- Cria uma nova branch no repositório
- Exemplo: `git branch nome-da-branch`
- Para criar e mudar para a nova branch: `git checkout -b nome-da-branch` 
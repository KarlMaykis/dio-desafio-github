# Comandos Básicos Essenciais:


- **git init** -> *para criar o diretório .git*

- **git status** -> *Verifica a situação de pendências para inclusão de arquivos.*

- **touch** -> *cria arquivo no diretório corrente.*

- **git add ""** -> *adiciona o arquivo selecionado dentro das aspas.*

- **git add . ou *** -> **adiciona todos os arquivos pendentes.*

- **git commit -m ""** -> *cria versão do projeto com mensagem indicando o que foi feito para melhor organizar(boa prática).*
- **git config --global user.email "you@example.com"** -> *registrar para fazer commit.*

- **git config --global user.name "Your Name"** -> *registrar para fazer commit.*

- **git config --global --unset "exemplo: user.email"** -> *retira o registro da config especificada.*

- **git config --list** -> *visualiza todas as configs definidas.*

- **git remote add origin ""** -> *define com a url o destino do projeto.*

- **git remote -v** -> *mostra lista de repositórios remotos definidos*

- **git push --set-upstream origin master** -> *define qual a branch do destino, nesse caso definiu como "Master"*

- **git restore --staged nome_do_arquivo** -> *Para remover o arquivo que foi colocado na "staged"*

- **git push origin master** -> *envia repositório local para o remoto*

- **git config --global core.mergeoptions --no-edit** -> *Define para resolver conflitos de “merge” manualmente.*



# Dinâmica e Estrutura:

## Status dos arquivos ou diretórios podem ser: 

- **Untracked**; **unmodified; modified e staged;**
- **Untracked** - *Não rastreado, está no diretório (working directory), o git enxerga mas não registra alterações (snapshot).*
- **Unmodified** - *Não modificado, quando o objeto já foi preparado ("staged" pelo "add") e feito o registro da sua versão (commit).*
- **Modified** - *Modificado, objeto foi alterado mas ainda não preparado (staged) para próximo commit.*
- **Staged** - *Preparado para próximo commit, quando "add" muda para estado "Unmodified".*
# Aprendendo um pouco mais sobre Git e GitHub

GIT INIT = inicializando repositório no formato (.git/).

GIT STATUS = reporta status de como o repositório se encontra naquele momento.

GIT ADD . = adiciona modificações para (untracked) para ser criado um commit.

GIT COMMIT = cria uma imagem atual do repositótio local.

GIT LOG --DECORATE = reporta informações sobre logs de  modificação e/ou criação.

GIT SHORTLOG = lista em ordem os autores e as criações de commit respectivamente.

GIT SHORTLOG -sn = lista os commits de cada autor.

GIT DIFF = mostra as mudanças, antes do commit.

GIT CHECKOUT (+ nome arquivo) = retorna para um momento antes, as modificações.

GIT RESET HEAD = voltar para um momento antes, mesmo após fazer o GIT ADD.

GIT REMOTE = retorna se o repositório local esta ligado ao remoto.

GIT CLONE = permite clonar repositórios remotos.

GIT BRANCH = lista as (branches) do repositório.

GIT CHECKOUT -b (+ nome) = cria uma nova branch.

GIT BRANCH -D (+ nome branch) = deleta a branch selecionada.

GIT PUSH = envia as atualizações de  código para o remoto.

GIT LOG --GRAPH = mostra a  árvore de branches e cada commit relacionado.

GIT MERGE = faz a união entre as branches criadas e a MAIN.

GIT IGNORE = adição de parte do repositório para ser ignorado.

GIT TAG = adicionando anotação de versões maiores.
usar (git tag -a (nº versão) -m ("mensagem")).

Reconfigurar tecla de comando com ALIAS = GIT CONFIG --GLOBAL ALIAS.(novo nome função) QUAL FUNÇÃO MUDAR.
EX: git config --global alias.s status (trocando o nome da função git status).

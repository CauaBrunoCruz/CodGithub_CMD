# CodGithub_CMD
Codigos de Github e Git para CMD

📌 Configuração inicial (apenas na primeira vez)

(git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com")
Define seu nome e e-mail para os commits.

📌 Criar ou clonar repositório

(git init)
Inicia um novo repositório Git na pasta atual.

(git clone https://github.com/usuario/repositorio.git)
Baixa (clona) um repositório remoto para sua máquina.

📌 Status e histórico

(git status)
Mostra o status atual dos arquivos (modificados, novos, etc).

(git log)
Lista o histórico de commits.

📌 Adicionar e salvar alterações

(git add nome_do_arquivo)
Adiciona um arquivo específico para o próximo commit.

(git add .)
Adiciona todos os arquivos modificados.

(git commit -m "Mensagem do commit")
Registra as mudanças no repositório.

📌 Enviar e receber do repositório remoto

(git push origin main)
Envia as alterações para a branch main no repositório remoto.

(git pull origin main)
Baixa e mescla as alterações mais recentes da branch main.

📌 Branches (ramificações)

(git branch)
Lista as branches existentes.

(git branch nome_da_branch)
Cria uma nova branch.

(git checkout nome_da_branch)
Troca para outra branch.

(git merge nome_da_branch)
Mescla a branch indicada na branch atual.
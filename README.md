1. Criar Projeto
/criar_projeto [nome_do_projeto] [descrição] [data_de_entrega]
# Exemplo:
# /criar_projeto "Website Institucional" "Desenvolver o site institucional da empresa" 31-12-2024

# 2. Adicionar Membros ao Projeto
/adicionar_membro [nome_do_membro] [email] [função_no_projeto]
# Exemplo:
# /adicionar_membro "João Silva" joao@email.com "Desenvolvedor"
/adicionar_membro "Maria Oliveira" maria@email.com "Designer"

# 3. Criar Tarefas e Atribuir Responsáveis
/criar_tarefa [nome_da_tarefa] [descrição] [responsável] [data_de_entrega]
# Exemplo:
# /criar_tarefa "Design da Homepage" "Criar o design inicial da página principal" "Maria Oliveira" 15-11-2024
/criar_tarefa "Desenvolvimento do Backend" "Criar a estrutura do backend para o site" "João Silva" 30-11-2024

# 4. Ativar Notificações
/ativar_notificações [frequência] [tipo_de_notificação]
# Exemplo:
# /ativar_notificações diária status_das_tarefas

# 5. Atualizar o Status de uma Tarefa
/atualizar_status [nome_da_tarefa] [novo_status] [comentário]
# Exemplo:
# /atualizar_status "Design da Homepage" "Em Progresso" "Primeiras versões do design estão em revisão"

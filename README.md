# Automação de Engajamento no LinkedIn - Resposta a Comentários e Gestão de Conexões
[![Built with n8n](https://img.shields.io/badge/Powered%20by-n8n-213355?style=flat-square)](https://n8n.io/)

##  Contexto do Projeto
O cliente enfrentava desafios com **gestão manual de centenas de comentários diários** em posts promocionais. A solução precisava:
- Automatizar respostas imediatas
- Enviar materiais para conexões
- Gerenciar pedidos de conexão
- Verificar aceitação de convites
- Operar dentro dos limites da API do LinkedIn
##  Funcionalidades Técnicas
-  Paginação automática de comentários (100+)
-  Verificação de status de conexão
-  Delays randômicos (15-20s) entre ações
-  2 fluxos paralelos: comentários novos vs respondidos
-  Limites configuráveis de visualização de perfis
## Fluxo Principal
![Diagrama da Automação](<img width="1479" height="539" alt="Captura de tela 2025-07-29 140802" src="https://github.com/user-attachments/assets/60de197f-4269-4b69-8b70-4e73f948a5f0" />
)
## Configuração (Variáveis Obrigatórias)
| Variável | Descrição | Exemplo |
|----------|-----------|---------|
| `URL da Postagem` | Link do post alvo | `https://linkedin.com/feed/update/...` |
| `account_id` | ID da conta Unipile | `FiLocNRQR1ObX4KQ2gNbWA` |
| `Chave API` | Token de acesso Unipile | `sk_live_...` |
| `Mensagem inbox` | Conteúdo enviado | "Opa, beleza? Segue acesso..." |
## Resultados e Impacto
-  Redução de 95% no tempo de gestão de comentários
-  Conversão automática de leads após aceite de conexão
-  Capacidade de operação 24/7 via agendamento
## Pré-requisitos de Instalação
- Conta Enterprise LinkedIn
- Assinatura Unipile (Plano API)
- Instância n8n (Cloud ou Self-hosted)

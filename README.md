# 🚀 Status Page

**Monitoramento inteligente de disponibilidade para aplicações**

---

## 🏢 Sobre o projeto

 Solução alternativa open source para monitoramento. Ele valida continuamente o estado de saúde (`/health`) de todas as APIs, web apps e sites da companhia, fornecendo visibilidade total e alertas em tempo real.

## 📝 Open Source
Link referente referente a documentação do produto [Kener](https://github.com/rajnandan1/kener) | [Uptime Kume](https://github.com/louislam/uptime-kuma)

## 🚀 Principais características:

✅ Checagem automática de todos os endpoints `/health`

📊 UI moderna (Status Page) para exibir o estado atual, histórico diário e por tipo de projeto

🛠️ Gerenciamento de manutenções programadas

🚨 Registro e notificação de incidentes

🔔 Webhooks configuráveis para alertas automatizados

⏱️ Tempo exato em que serviços ficaram fora do ar

## 🚦 Funcionalidades

✅ **Monitoramento em tempo real**  
> Varredura contínua dos endpoints `/health` de todas as aplicações e infraestrutura.
> Identificação imediata de indisponibilidade

🛠️ **Manutenção programada**  
> Defina janelas de manutenção
> Status Page exibe que o serviço está em manutenção ao invés de "fora do ar"

🚨 **Incidentes**  
> Criação manual ou automática de incidentes
> Tempo e minuto preciso do início e fim do problema
> Registro do motivo e ações tomadas


🔔 **Webhooks**  
- Disparo de POST para sistemas externos (Slack, Teams, Email, etc.) em caso de incidentes ou recuperação


## Execução do Projeto
### **🐳Docker**

1. Executar comando na **raiz** do projeto:
> *docker-compose up -d*

2. logs de execução:
> *docker-compose logs*

3. Parar e remover container:
> *docker-compose down*

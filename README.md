# Desafio: Implementação de Práticas DevOps em um Ambiente Empresarial Fictício

## 1. Diagnóstico Cultural (C de CALMS)

### Identificação do Processo
**Processo Identificado:** Entrega de Código e Deploy.

### Descrição do Processo Atual
- **Entrega de Código:** Os desenvolvedores preparam um pacote de implantação e o enviam à equipe de operações.
- **Deploy:** Deploy manual em ambientes de produção, sem procedimentos padronizados ou automação.
- **Testes:** Testes manuais realizados pela equipe de operações depois do deploy.
- **Monitoramento:** Controle manual dos logs do servidor após o deploy.

### Pontos de Atrito e Oportunidades de Melhoria
- **Falta de Padronização:** A falta de padronização de processos resulta em inconsistências.
- **Demora para Deploy:** Leva cerca de 2 dias para entregar o valor.
- **Testes Ineficientes:** Testes manuais são demorados e podem conter erros humanos.
- **Monitoramento Reativo:** O monitoramento manual detecta problemas somente após a ocorrência.

## 2. Automação (A de CALMS)

### Solução Proposta de Automação
**Ferramentas Sugeridas:**
- **CI/CD:** Jenkins ou GitLab CI para automação de builds.
- **Infraestrutura de Código (IaC):** Terraform ou Ansible, para padronizar e automatizar a configuração da infraestrutura.
- **Testes Automatizados:** Selenium ou JUnit para realizar testes de regressão e integração.
- **Monitoramento Automatizado:** Prometheus e Grafana para monitoração contínua e alertas em tempo real.

### Plano de Implementação da Automação
1. **Configuração do CI/CD:**
   - Configurar Jenkins ou GitLab CI para a configuração de build e deploy automáticos.
   - Criar pipelines para testes automatizados.
2. **Padronização com IaC:**
   - Aplicar a tecnologia Terraform ou Ansible para planejar e gerenciar a infraestrutura.
3. **Automatização de Testes:**
   - Usar Selenium e JUnit nos pipelines de CI/CD para testes automatizados.
4. **Monitoramento Contínuo:**
   - Configurar o Prometheus para a coleta de dados.
   - Utilizar Grafana para design de dashboards e alertas em tempo real.

## 3. Mensuração e Compartilhamento de Conhecimento (M e S de CALMS)

### Métricas Relevantes
- **Tempo de Deploy:** Verificar a diminuição do tempo de deploy.
- **Taxa de Sucesso do Deploy:** Aumentar a taxa de sucesso do Deploy em 95% ou superior.
- **Número de Incidentes Pós-Deploy:** Reduzir o número de incidentes após o deploy.
- **MTTR:** Diminuir o tempo médio de recuperação de incidentes.

### Plano para Disseminação de Conhecimento
1. **Documentação:** Criar uma documentação detalhada para os novos processos automatizados.
2. **Workshops:** Realizar workshops para capacitar as equipes de desenvolvimento e operação nas novas ferramentas e procedimentos.
3. **Comunicação Contínua:** Realizar reuniões regulares para compartilhar feedback e melhorias constantes.

## 4. Três Maneiras

### Primeira Maneira (Acelerar o Fluxo)
- **Automação do Processo:** Eliminar etapas manuais e diminuir o tempo de entrega.
- **Pipelines CI/CD:** Pipelines preparados para build, teste e deploy contínuos.

### Segunda Maneira (Ampliar o Feedback)
- **Feedback Constante:** Coleta de métricas e logs em tempo real, com Prometheus e Grafana.
- **Feedback Automático:** Avisos automáticos em caso de falhas ou degradação de desempenho.

### Terceira Maneira (Experimentar e Aprender)
- **Ambiente de Testes:** Criação de ambientes de testes automatizados para assegurar uma experiência segura.
- **Cultura de Aprendizado:** Incentivar retrospectivas regulares para analisar erros e identificar oportunidades de melhoria.

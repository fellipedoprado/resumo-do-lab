# Resumo de Lições Aprendidas sobre Computação em Nuvem

## 1. O que é Computação em Nuvem
- **Definição**: Entrega de recursos computacionais sob demanda (servidores, armazenamento, redes, software) via internet, com pagamento conforme o uso.
- **Características-chave**:
  - Escalabilidade elástica.
  - Acesso global e autoatendimento.
  - Modelos de serviço: IaaS, PaaS, SaaS.
  - Modelos de implantação: pública, privada, híbrida, multicloud.

## 2. Responsabilidade Compartilhada
- **Definição**: Divisão de responsabilidades entre provedor e cliente.
  - **Provedor**: Gerencia infraestrutura física, rede e virtualização.
  - **Cliente**: Responsável por dados, configurações de segurança, atualizações de SO e controle de acesso.
  - **Variação por modelo**: Em SaaS, o provedor assume mais responsabilidades; em IaaS, o cliente tem maior controle.

## 3. Modelos de Nuvem
- **Pública** (AWS, Azure, GCP):
  - Recursos compartilhados, custos operacionais baixos, escalabilidade imediata.
- **Privada** (on-premise ou hospedada):
  - Controle total, segurança reforçada, ideal para dados sensíveis.
- **Híbrida**:
  - Combina nuvem pública e privada, flexibilidade para migrações graduais.
- **Multicloud**:
  - Reduz dependência de um único provedor e otimiza custos/performance.

## 4. Custo de Capital (CapEx) vs. Custo Operacional (OpEx)
- **CapEx**: Investimento em infraestrutura local (hardware, data centers).
- **OpEx** (Nuvem):
  - Pagamento por uso, sem custos fixos elevados.
  - Redução de desperdício (escala conforme demanda).

## 5. Benefícios da Alta Disponibilidade e Escalabilidade
- **Alta disponibilidade**:
  - Redundância geográfica e balanceamento de carga minimizam tempo de inatividade.
  - Exemplo: Sistemas com SLA de 99,99% (menos de 1 hora de downtime/ano).
- **Escalabilidade**:
  - Vertical (aumento de recursos) e horizontal (adição de instâncias).
  - Autoescalagem que se adapta a picos de tráfego automaticamente.

## 6. Benefícios da Confiabilidade e Previsibilidade
- **Confiabilidade**:
  - SLAs garantem desempenho e disponibilidade.
  - Arquiteturas tolerantes a falhas (ex: zonas de disponibilidade).
- **Previsibilidade**:
  - Custos estimáveis com modelos de preço reservado (ex: instâncias reservadas AWS).
  - Ferramentas de monitoramento (Azure Monitor) preveem gastos e uso.

## 7. Benefícios da Segurança e Governança
- **Segurança**:
  - Certificações de compliance (ISO, GDPR) garantidas pelo provedor.
  - Ferramentas nativas: criptografia, firewalls, IAM.
- **Governança**:
  - Políticas centralizadas para acesso e conformidade.
  - Facilita a auditoria com logs e relatórios.

## 8. Benefícios da Capacidade de Gerenciamento
- **Centralização**:
  - Interfaces unificadas (Azure Portal) para gerenciar múltiplos serviços.
- **Automação**:
  - DevOps via CI/CD, IaC (Terraform, CloudFormation).
  - Redução de erros manuais e agilidade em implantações.
- **Monitoramento**:
  - Insights em tempo real (ex: Azure Advisor) para otimizar performance e custos.

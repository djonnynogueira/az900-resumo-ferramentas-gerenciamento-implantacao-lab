# Este repositório contém o resumo das lições aprendidas sobre ferramentas de gerenciamento e implantação na nuvem Azure, incluindo Azure DevOps e Azure Resource Manager.

## Conceitos Abordados

### Fundamentos de Ferramentas de Implantação

- **Implantação (Deployment)**: Processo de colocar aplicações e recursos em produção na nuvem.
- **Infraestrutura como Código (IaC)**: Abordagem para gerenciar infraestrutura através de código e configurações.
- **Automação**: Uso de ferramentas para automatizar o processo de implantação e gerenciamento.
- **DevOps**: Prática que integra desenvolvimento e operações para melhorar a qualidade e velocidade de entrega.
- **Pipeline de CI/CD**: Integração e Deploy Contínuo para automatizar testes e implantação.

### Azure DevOps

- **O que é**: Plataforma da Microsoft para gerenciar o ciclo de vida completo do desenvolvimento de software.
- **Componentes Principais**:
  - **Azure Repos**: Repositório de controle de versão (Git ou TFVC).
  - **Azure Pipelines**: Serviço de CI/CD para automação de build e release.
  - **Azure Boards**: Gerenciamento de trabalho e rastreamento de projetos (Scrum, Kanban).
  - **Azure Test Plans**: Ferramentas para testes de software.
  - **Azure Artifacts**: Gerenciamento de pacotes e dependências.
- **Benefícios**:
  - Automatiza o processo de build, teste e implantação.
  - Melhora a velocidade e confiabilidade das releases.
  - Facilita colaboração entre equipes de desenvolvimento e operação.
  - Integra-se perfeitamente com serviços do Azure.

### Azure Resource Manager (ARM)

- **O que é**: Camada de gerenciamento do Azure que permite criar, atualizar e deletar recursos.
- **Características Principais**:
  - **Modelos ARM**: Arquivos JSON que definem a infraestrutura desejada (IaC).
  - **Grupos de Recursos**: Contéineres lógicos para organizar recursos relacionados.
  - **Controle de Acesso**: RBAC integrado para controlar quem pode provisionar recursos.
  - **Validação**: Valida templates antes da implantação.
- **Vantagens**:
  - Reproduzibilidade de infraestrutura.
  - Versionamento de configurações.
  - Implantação idempotente.
  - Auditoria de alterações na infraestrutura.

### Fluxo de Trabalho de Implantação

1. **Planejamento**: Definir requisitos e arquitetura da solução.
2. **Desenvolvimento**: Escrever código e templates ARM.
3. **Versionamento**: Armazenar código em repositório (Azure Repos ou GitHub).
4. **Build**: Compilar e empacotar a aplicação.
5. **Teste**: Executar testes automáticos.
6. **Implantação**: Deploy automático em ambientes (dev, test, prod).
7. **Monitoramento**: Acompanhar saúde da aplicação em produção.

### Ferramentas Complementares

- **Terraform**: Ferramenta IaC de código aberto para Azure e outras clouds.
- **Ansible**: Ferramenta de automação para configuração de recursos.
- **Docker**: Contenerizão para empacotar aplicações.
- **Kubernetes**: Orquestração de contêners em escala.

## Competências Adquiridas

- Capacidade de configurar e usar Azure Pipelines para CI/CD.
- Habilidade de criar e gerenciar templates ARM para infraestrutura como código.
- Entendimento de boas práticas em automação de implantação.
- Conhecimento de fluxos de trabalho DevOps no Azure.
- Capacidade de integrar repositórios de código com pipelines de deployment.
- Compreensão de estratégias de teste automático em pipelines.
- Habilidade de monitorar e validar deploys em produção.

## Conclusão

As ferramentas de gerenciamento e implantação no Azure, especialmente Azure DevOps e Azure Resource Manager, são essenciais para operacionalizar aplicações na nuvem de forma segura, rápida e confiável. A integração de CI/CD, infraestrutura como código e automação permite que equipes entreguem softwares de qualidade continuamente, reduzindo riscos e acelerando time-to-market. Compreender e dominar essas ferramentas é fundamental para qualquer profissional que trabalha com desenvolvimento e operação em ambientes de nuvem.

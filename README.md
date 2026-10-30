# Lucas Ferreira

Sou profissional de tecnologia com 22 anos de carreira, combinando gestão de projetos, liderança de equipes e atuação técnica em desenvolvimento e qualidade de software.

Minha experiência inclui projetos nos setores bancário, público e em multinacionais. Gerenciei uma equipe de 60 profissionais em contrato da CAIXA, liderei iniciativas de qualidade e automação e participei da evolução de processos de desenvolvimento em grandes organizações.

Hoje, como fundador da IQLabs, desenvolvo produtos que conectam inteligência artificial, engenharia de software e necessidades de negócio.

## O que estou construindo

### Dió — IA Cético

Plataforma de investigação e produção de conteúdo com agentes especializados, pesquisa de fontes, revisão adversarial, auditoria de fidelidade e aprovação humana. Orquestração própria com NestJS, pg-boss e PostgreSQL, integração de modelos via OpenRouter e rastreabilidade de execuções, tokens e custos.

### IQMock

Solução de virtualização de serviços para apoiar o desenvolvimento e os testes de sistemas, reduzindo a dependência de integrações e ambientes externos.

## Contribuições em projetos open source

### CLOC — suporte a stored procedures SQL em arquivos `.scp`

Adicionei ao CLOC o reconhecimento de arquivos `.scp` como SQL Stored Procedure, com documentação e teste de regressão. A melhoria permite incluir esse código de banco de dados na contagem de linhas de código e comentários, evitando que ele fique fora dos levantamentos por falta de reconhecimento da extensão.

**Aplicação prática:** inventários de software e análises de tamanho mais completos em sistemas que utilizam esse formato.

[Ver contribuição no CLOC](https://github.com/ldbferreira/cloc/tree/feature/add-scp-stored-procedure)

### n8n + Langfuse — confiabilidade na observabilidade de agentes de IA

Implementei correções no nó de integração para preservar os metadados de consumo de tokens entre diferentes cópias dos módulos do LangChain e aguardar o envio dos eventos ao Langfuse antes do encerramento de cada execução. O tratamento contempla sucesso e erro, com testes de regressão.

As correções tratam situações em que uma chamada ao modelo era realizada e cobrada pelo provedor, mas seus registros ou dados de consumo não apareciam corretamente no Langfuse.

**Aplicação prática:** rastreabilidade mais consistente das execuções e melhor visibilidade do consumo de IA para apoiar o acompanhamento de custos e o diagnóstico de falhas.

[Ver contribuição na integração n8n–Langfuse](https://github.com/ldbferreira/n8n-nodes-ai-agent-langfuse/tree/fix/langfuse-cross-module-usage-metadata)

## Áreas de atuação

- Gestão de projetos de tecnologia e liderança de equipes.
- Desenvolvimento de produtos digitais e arquitetura de soluções.
- IA aplicada, sistemas multiagentes e integração de LLMs.
- Qualidade de software, automação de testes e virtualização de serviços.

## Tecnologias e ferramentas

### Inteligência artificial e sistemas de agentes

- **Modelos e integrações:** GPT, Claude e Gemini; integração por APIs e OpenRouter; experiência prática com Qwen em appliance próprio.
- **Agentes e automação:** sistemas multiagentes, orquestração de etapas especializadas, LangChain, n8n, MCP e workflows persistentes com pg-boss.
- **Engenharia de prompts e contexto:** instruções por tarefa, seleção de modelos, contratos de saída em JSON e validação de respostas.
- **Observabilidade e FinOps de IA:** Langfuse, rastreamento de chamadas, análise de tokens e latência, estimativas e reconciliação de custos, limites de orçamento e alertas.
- **Arquitetura de recuperação de conhecimento:** RAG, embeddings e Pinecone.
- **Avaliação e governança:** revisão adversarial, auditoria de fidelidade, validações determinísticas, rastreabilidade de evidências e aprovação humana em etapas críticas.

### Qualidade e engenharia de testes

- **Estratégia de qualidade:** testes baseados em risco, regressão, integração, UAT, quality gates e integração dos testes ao ciclo de desenvolvimento.
- **Automação de testes:** Selenium, Playwright, Tricentis Tosca, Rational Functional Tester, Rational Test Workbench e JUnit.
- **APIs e qualidade de código:** Parasoft SOAtest, Jtest e C/C++test; testes de serviços e integrações.
- **Performance:** JMeter e k6; planejamento e execução de testes de carga e estresse.
- **Virtualização de serviços e dados de teste:** Parasoft Virtualize, Broadcom/CA DevTest, Service Virtualization, Test Data Management e IQMock; simuladores de transações e redução da dependência de ambientes externos.
- **Segurança de aplicações:** Fortify e práticas de AppSec com SAST, DAST e MAST.
- **Sistemas corporativos:** qualidade e automação em SAP S/4HANA e Salesforce, além de sistemas bancários e governamentais críticos.

### Engenharia, infraestrutura e entrega

- **Linguagens e frameworks:** Python, Java, TypeScript, JavaScript, Spring Boot, NestJS, Next.js e React.
- **Arquitetura e dados:** APIs, microsserviços, PostgreSQL, Prisma e processamento assíncrono.
- **Infraestrutura e operação:** AWS, Docker, Docker Compose e Kubernetes.
- **Entrega e colaboração:** CI/CD, GitHub Actions, Azure DevOps e Jira.

## Certificações obtidas

### Agilidade e liderança

- **A-CSM — Advanced Certified ScrumMaster®** — Scrum Alliance.
- **ACPC — Agile Coach Professional** — CertiProf.
- **SFC — Scrum Fundamentals** — SCRUMstudy.

### Qualidade e testes de software

- **CTFL** — ISTQB / BSTQB.
- **CTFL-AT** — ISTQB / BSTQB.
- **CTAL-TA** — ISTQB / BSTQB.
- **CTAL-TM** — ISTQB / BSTQB.

### Virtualização de serviços e dados de teste

- **Virtualize Essentials** — Parasoft.
- **Service Virtualization e TDM — Pre-sales Specialist** — Broadcom (CA Technologies).

## Contato

[LinkedIn](https://www.linkedin.com/in/lucasdbferreira/)


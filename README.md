# Lucas Ferreira

Sou profissional de tecnologia com 22 anos de carreira, combinando gestão de projetos, liderança de equipes e atuação técnica em desenvolvimento e qualidade de software.

Minha experiência inclui projetos nos setores bancário, público e em multinacionais. Gerenciei uma equipe de 60 profissionais em contrato da CAIXA, liderei iniciativas de qualidade e automação e participei da evolução de processos de desenvolvimento em grandes organizações.

Hoje, como fundador da IQLabs, desenvolvo produtos que conectam inteligência artificial, engenharia de software e necessidades de negócio.

## O que estou construindo

### Dió — IA Cético

Plataforma de IA generativa com orquestração de agentes, recuperação de conhecimento e observabilidade.

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

**Engenharia e infraestrutura:** Python · Java · Spring Boot · Docker · AWS · Azure DevOps

**Inteligência artificial:** LangChain · Langfuse · RAG · MCP

**Qualidade de software:** Playwright · Parasoft · Service Virtualization · Test Data Management

## Certificação obtida

**Advanced Certified ScrumMaster® (A-CSM)** — Scrum Alliance

## Contato

[LinkedIn](https://www.linkedin.com/in/lucasdbferreira/)


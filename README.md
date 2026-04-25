# IA aplicada a Testes de Software: Engenharia de prompts e análise prática com NotebookLM

Este projeto foi desenvolvido com o objetivo de explorar, na prática, como a IA pode apoiar (e limitar) o trabalho de um QA.

## Sobre o projeto

Este repositório documenta um estudo prático utilizando NotebookLM como ferramenta de aprendizado ativo, com foco em:
- Engenharia de prompts
- Geração de testes com IA
- Análise crítica de cobertura
- Aplicação de boas práticas de QA

## 1. Contexto e objetivos

Este projeto foi desenvolvido como parte de um estudo prático sobre a aplicação de Inteligência Artificial (IA) em testes de software, utilizando o NotebookLM como ferramenta de apoio ao aprendizado.

O objetivo principal foi construir um caderno temático estruturado, combinando fundamentos de Quality Assurance (QA), engenharia de prompts e pensamento crítico, com foco em:

- Compreender conceitos fundamentais de testes de software
- Explorar o uso da IA na geração e análise de testes
- Identificar limitações reais da IA no contexto de QA
- Aplicar técnicas de teste em cenários práticos
- Desenvolver habilidades de engenharia de prompts
- Consolidar o aprendizado em um miniguia reutilizável

O projeto não se limita ao uso da IA como ferramenta de geração, mas enfatiza a análise crítica dos resultados e o papel do QA humano na validação e tomada de decisão.

---

## 2. Curadoria de fontes

As seguintes fontes foram utilizadas como base teórica no NotebookLM:

- Artificial Intelligence in Software Testing - Impact, Problems, Challenges and Prospect  
- Harnessing the Power of Large Language Models for Software Testing Education: A Focus on ISTQB Syllabus  
- AI Testing (CT-AI) Syllabus Version 1.0  
- ISTQB Advanced Level Syllabus - Test Analyst (2019)  
- ISTQB Foundation Level Syllabus v4.0.1  

Essas fontes foram selecionadas por sua relevância acadêmica e alinhamento com padrões reconhecidos da indústria (ISTQB), garantindo consistência conceitual ao estudo.

---

## 3. Engenharia de Prompts e Interações com IA

Durante o desenvolvimento do projeto, foram utilizados diferentes tipos de prompts com objetivos específicos:

- Geração de casos de teste  
- Expansão de cobertura  
- Análise crítica  
- Comparação entre abordagens  
- Refinamento de resultados  

A seguir, são apresentados exemplos reais de evolução de prompts e aprendizado obtido.

---

### Exemplo 1 — Geração inicial

**Prompt:**
"Gere casos de teste funcionais para um sistema de login com validação de e-mail e senha"

**Resultado:**
- Casos básicos com foco em cenários positivos e negativos
- Uso de técnicas como Particionamento de equivalência e Análise de valor limite

**Problemas identificados:**
- Ausência de testes não funcionais
- Dados de teste genéricos
- Falta de critérios claros de validação

---

### Exemplo 2 — Refinamento estrutural

**Prompt:**
"Gere casos de teste detalhados com pré-condições, passos e resultados esperados"

**Melhorias obtidas:**
- Estrutura mais próxima de casos reais
- Inclusão de pré-condições e passos

**Limitações:**
- Ainda focado em testes funcionais
- Ausência de pós-condições

---

### Exemplo 3 — Análise crítica

**Prompt:**
"Analise os casos de teste e identifique falhas e lacunas"

**Principais achados:**
- Falta de pós-condições
- Dados vagos
- Falta de rastreabilidade

**Lacunas identificadas:**
- Segurança
- Performance
- Usabilidade

---

### Exemplo 4 — Refinamento avançado

**Prompt:**
"Refine os testes incluindo segurança, edge cases e cobertura ampliada"

**Resultado:**
- Inclusão de testes de SQL Injection e XSS
- Testes de sessão e timeout
- Cenários de carga e acessibilidade

**Insight:**
A qualidade dos testes evolui diretamente com o nível de detalhe do prompt.

---

## 4. Evolução dos testes com IA

A evolução dos testes ao longo das interações evidencia um padrão claro:

| Etapa | Característica |
|------|----------------|
| Inicial | Geração rápida, porém superficial |
| Estruturada | Melhor organização, mas ainda limitada |
| Analisada | Identificação de falhas relevantes |
| Refinada | Cobertura mais completa e alinhada a boas práticas |

Esse processo reforça que a IA atua melhor como ferramenta iterativa, não como solução final.

---

## 5. Limitações da IA na prática

Durante o uso, foram identificadas limitações recorrentes:

- Tendência a respostas genéricas
- Falta de contexto de negócio
- Baixa cobertura de testes não funcionais (sem direcionamento)
- Dependência de prompts bem estruturados
- Dificuldade em definir oráculos de teste
- Necessidade constante de validação humana

Essas limitações reforçam a importância do papel do QA na interpretação e validação dos resultados.

---

## 6. IA vs QA Humano

| Aspecto | IA | QA Experiente |
|--------|----|---------------|
| Velocidade | Alta | Moderada |
| Volume | Alto | Limitado |
| Contexto de negócio | Limitado | Elevado |
| Priorização | Fraca | Baseada em risco |
| Testes não funcionais | Limitado (sem prompt) | Forte |
| Pensamento crítico | Limitado | Essencial |

**Conclusão:**
A IA é eficiente para geração e escala, enquanto o QA humano é essencial para análise, priorização e validação.

---

## 7. Quando usar IA vs Quando evitar

### Quando usar IA:
- Geração inicial de casos de teste
- Exploração de cenários
- Otimização de testes de regressão
- Geração de dados de teste
- Identificação de padrões

### Quando evitar depender da IA:
- Definição de critérios de aceite
- Avaliação de usabilidade
- Decisões baseadas em contexto de negócio
- Análise de requisitos ambíguos
- Validação final dos testes

---

## 8. Miniguia de estudo

### 8.1 Resumo estruturado

**Fundamentos de QA:**
- Testes identificam defeitos, não garantem ausência
- Testes exaustivos são inviáveis
- Teste antecipado reduz custo
- Testes devem ser priorizados por risco

**Técnicas de teste:**
- Particionamento de equivalência
- Análise de valor limite
- Tabela de decisão
- Transição de estado
- Teste exploratório

**IA em testes:**
- Geração automática de casos
- Otimização de regressão
- Geração de dados sintéticos
- Limitações em contexto e validação

---

### 8.2 Glossário

- Análise de valor limite: Técnica focada nos limites de entrada  
- Particionamento de equivalência: Divisão de dados em classes equivalentes  
- Teste exploratório: Teste baseado em aprendizado contínuo  
- Oráculo de teste: Fonte que define o resultado esperado  
- Rastreabilidade: Relação entre requisitos e testes  
- Teste funcional: Valida comportamento do sistema  
- Teste não funcional: Avalia atributos como performance e segurança  

---

### 8.3 Prompts reutilizáveis

**Geração de testes:**
"Gere casos de teste funcionais e não funcionais com base nos seguintes requisitos..."

**Análise de cobertura:**
"Analise os casos de teste e identifique lacunas de cobertura com base na ISO 25010"

**Refinamento:**
"Refine os casos incluindo edge cases, segurança e cenários de falha"

**Comparação:**
"Compare os testes gerados com uma abordagem manual de QA experiente"

**Avaliação de risco:**
"Priorize os casos de teste com base em risco de negócio e impacto"

---

## 9. Resultado final do projeto

Ao final do processo iterativo com apoio da IA, foi possível consolidar uma abordagem mais completa de testes para o sistema de login, considerando:

- Casos de teste funcionais estruturados (com pré-condições, passos e resultados esperados)
- Inclusão de cenários de segurança (SQL Injection, XSS, bloqueio de conta)
- Aplicação de Análise de valor limite (incluindo limites superiores)
- Testes de sessão e timeout
- Cenários de performance (carga de usuários simultâneos)
- Verificações de usabilidade e acessibilidade

Além disso, foram aplicadas boas práticas como:
- Identificação de lacunas de cobertura
- Refinamento iterativo dos testes
- Consideração de atributos de qualidade baseados na ISO 25010

O resultado final não é apenas um conjunto de testes, mas uma abordagem estruturada que combina:
- geração assistida por IA
- validação crítica humana
- melhoria contínua baseada em análise

---

## 10. Conclusão

Este projeto demonstrou que a Inteligência Artificial pode acelerar significativamente a geração e expansão de testes, mas não substitui o papel do QA.

Os principais aprendizados foram:

- IA é uma ferramenta de apoio, não uma solução completa
- Prompts bem estruturados são essenciais para resultados relevantes
- Pensamento crítico é indispensável no processo de teste
- A qualidade dos testes depende da capacidade de análise humana

A combinação entre IA e QA humano permite alcançar maior eficiência, mantendo a qualidade e a confiabilidade do software.

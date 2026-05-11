# AGENT MOBILE FIREBASE

Arquitetura profissional para desenvolvimento mobile orientado por IA utilizando:

- Expo
- React Native
- TypeScript
- NativeWind
- shadcn/ui
- Zod
- Firebase

Com foco em:

- controle de contexto
- qualidade de código
- segurança
- acessibilidade
- produtividade
- escalabilidade
- vibecoding profissional

---

# OBJETIVO

Esse projeto implementa uma arquitetura baseada em agentes especialistas e memória persistente para impedir que a IA:

- perca contexto
- gere código inconsistente
- troque arquitetura aleatoriamente
- quebre padrões
- produza spaghetti code
- exponha vulnerabilidades
- degrade UX

A arquitetura transforma o fluxo de vibecoding em um processo:

- previsível
- modular
- escalável
- organizado
- reutilizável

---

# PROBLEMA DO VIBECODING TRADICIONAL

Sem arquitetura, a IA normalmente:

- esquece decisões anteriores
- muda stack no meio do projeto
- cria componentes inconsistentes
- duplica código
- implementa múltiplas features simultaneamente
- mistura lógica de negócio com UI
- quebra acessibilidade
- ignora segurança
- gera código difícil de manter

O resultado é:

- retrabalho
- perda de produtividade
- baixa escalabilidade
- perda de contexto
- degradação do projeto

---

# SOLUÇÃO

Este projeto utiliza:

- agentes especialistas
- documentação modular
- memória persistente
- fluxo controlado
- tasks pequenas
- arquitetura guiada

A IA passa a trabalhar como um:

- arquiteto
- tech lead
- mobile engineer
- AppSec engineer
- reviewer
- squad técnico

---

# ESTRUTURA DO PROJETO

```txt
project/
│
├── .agents/
├── docs/
├── memory/
├── tasks/
├── .workflow/
└── src/
```

---

# AGENTES ESPECIALISTAS

## orchestrator.md

Responsável por:

- coordenar desenvolvimento
- dividir tarefas
- manter contexto
- impedir desorganização

---

## mobile-architect.md

Define:

- arquitetura
- organização
- separação de responsabilidades
- escalabilidade

---

## expo-specialist.md

Especialista em:

- Expo
- React Native
- navegação
- performance mobile

---

## firebase-agent.md

Responsável por:

- Firebase Auth
- Firestore
- Security Rules
- segurança backend

---

## security-agent.md

Responsável por:

- sanitização
- segurança
- proteção de sessão
- hardening
- revisão AppSec

---

## accessibility-agent.md

Responsável por:

- acessibilidade
- screen readers
- contrastes
- touch targets
- UX inclusiva

---

## uiux-agent.md

Responsável por:

- experiência do usuário
- design moderno
- fluidez
- microinterações
- feedback visual

---

## reviewer-agent.md

Responsável por:

- revisão técnica
- detectar problemas
- impedir regressões
- validar qualidade

---

## task-generator.md

Responsável por:

- quebrar funcionalidades
- criar tasks pequenas
- reduzir perda de contexto

---

# MEMÓRIA PERSISTENTE

A pasta memory/ mantém o contexto vivo do projeto.

---

## decisions.md

Guarda decisões permanentes:

- stack
- arquitetura
- bibliotecas
- padrões

Impede a IA de mudar arquitetura aleatoriamente.

---

## bugs.md

Guarda:

- bugs encontrados
- causa raiz
- solução
- prevenção

Impede regressões.

---

## improvements.md

Guarda:

- melhorias futuras
- otimizações
- refatorações planejadas

Mantém backlog técnico organizado.

---

## learnings.md

Guarda:

- aprendizados do projeto
- padrões que funcionaram
- experiências acumuladas

Transforma a IA em uma arquitetura evolutiva.

---

# CONTROLE DE CONTEXTO

O maior problema do vibecoding é excesso de contexto.

A solução:

- tasks pequenas
- fases controladas
- contexto modular
- leitura seletiva

---

# WORKFLOW

A pasta .workflow controla a execução da IA.

---

## current-phase.md

Define a fase atual do projeto.

Impede implementação fora do escopo.

---

## current-task.md

Define a task atual.

Mantém foco absoluto.

---

## execution-rules.md

Define regras obrigatórias:

- segurança
- arquitetura
- UX
- acessibilidade
- padrões

---

## done-checklist.md

Checklist obrigatório antes de finalizar qualquer implementação.

---

## context-loading.md

Define quais arquivos a IA deve ler.

Evita contexto excessivo.

---

# DOCUMENTAÇÃO

## prd.md

Define:

- produto
- funcionalidades
- stack
- objetivos

---

## architecture.md

Define:

- arquitetura
- fluxo de dados
- organização estrutural

---

## design-system.md

Define:

- identidade visual
- componentes
- UX
- consistência visual

---

## animation-guidelines.md

Define:

- padrões de animação
- performance
- fluidez
- microinterações

---

## rules.md

Define regras obrigatórias do projeto.

---

# STACK PADRÃO

## Mobile

- Expo
- React Native
- TypeScript

---

## UI

- NativeWind
- shadcn/ui

---

## Forms

- React Hook Form
- Zod

---

## Backend

- Firebase

---

## Segurança

- SecureStore
- Sanitização
- Firebase Rules

---

## Animações

- Reanimated
- Moti

---

# BENEFÍCIOS

## CONTEXTO

A IA mantém:

- arquitetura
- padrões
- decisões
- consistência

---

## QUALIDADE

A arquitetura reduz:

- código duplicado
- spaghetti code
- regressões
- má organização

---

## SEGURANÇA

Impede:

- exposição de secrets
- armazenamento inseguro
- falhas de autenticação
- vulnerabilidades comuns

---

## PRODUTIVIDADE

Permite:

- desenvolvimento rápido
- menos retrabalho
- menos refatorações
- fluxo previsível

---

## ESCALABILIDADE

O projeto cresce de forma:

- modular
- organizada
- sustentável

---

# COMO INICIAR O DESENVOLVIMENTO

# PASSO 1 — DEFINIR O PRD

Preencher:

```txt
docs/prd.md
```

Definir:

- objetivo do app
- funcionalidades
- stack
- regras

---

# PASSO 2 — DEFINIR ARQUITETURA

Preencher:

```txt
docs/architecture.md
```

Definir:

- feature-first
- services
- navegação
- providers
- autenticação

---

# PASSO 3 — CONFIGURAR DESIGN SYSTEM

Preencher:

```txt
docs/design-system.md
```

Definir:

- cores
- tipografia
- UX
- componentes
- padrões visuais

---

# PASSO 4 — DEFINIR FASE ATUAL

Editar:

```txt
.workflow/current-phase.md
```

Exemplo:

```md
FASE 1 — Setup inicial Expo
```

---

# PASSO 5 — CRIAR TASK

Criar:

```txt
tasks/task-001.md
```

Exemplo:

```md
Objetivo:
Configurar NativeWind.

Escopo:
- instalação
- configuração
- aliases

Não fazer:
- auth
- firebase
```

---

# PASSO 6 — CHAMAR A IA

Prompt recomendado:

```txt
Leia:
- .workflow/*
- docs/*
- memory/*
- task atual

Analise a task primeiro.
Não implemente ainda.
```

---

# PASSO 7 — IMPLEMENTAR

Depois:

```txt
Implemente SOMENTE a task atual.
Não saia do escopo.
Siga:
- architecture.md
- rules.md
- design-system.md
```

---

# PASSO 8 — REVIEW

Após implementação:

```txt
Revise:
- segurança
- acessibilidade
- performance
- arquitetura
- UX
```

---

# PASSO 9 — ATUALIZAR MEMÓRIA

Após concluir:

Atualizar:
- decisions.md
- bugs.md
- learnings.md
- improvements.md

Sempre que necessário.

---

# REGRA MAIS IMPORTANTE

NUNCA FAÇA:

```txt
Crie meu app inteiro
```

SEMPRE FAÇA:

```txt
Implemente SOMENTE:
- tela login
- schema login
- auth service

Sem Firebase ainda.
```

---

# RESULTADO FINAL

Essa arquitetura transforma vibecoding em:

- desenvolvimento profissional
- arquitetura escalável
- contexto persistente
- engenharia orientada por IA
- fluxo previsível
- alta produtividade

Com qualidade próxima de times profissionais.
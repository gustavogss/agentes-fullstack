# IMPROVEMENTS

---

# IMPROVEMENT-001

## Título

Implementar skeleton loading global.

---

## Tipo

UX

---

## Prioridade

MÉDIA

---

## Contexto

Atualmente algumas telas usam apenas spinner.

---

## Objetivo

Melhorar percepção de performance.

---

## Sugestão técnica

Criar:
- SkeletonCard
- SkeletonList
- SkeletonProfile

---

## Impacto

- UX melhor
- Sensação premium
- Menos abandono

---

## Dependências

- Design system finalizado

---

## Status

BACKLOG

---

# IMPROVEMENT-002

## Título

Adicionar rate limiting nas Firebase Functions.

---

## Tipo

SEGURANÇA

---

## Prioridade

ALTA

---

## Contexto

Auth endpoints podem sofrer abuso.

---

## Objetivo

Reduzir brute force e spam.

---

## Sugestão técnica

Implementar:
- IP throttling
- cooldown
- bloqueio temporário

---

## Status

BACKLOG

---

# IMPROVEMENT-003

## Título

Migrar listas pesadas para FlashList.

---

## Tipo

PERFORMANCE

---

## Prioridade

MÉDIA

---

## Contexto

FlatList pode degradar performance em listas grandes.

---

## Objetivo

Melhorar FPS e memória.

---

## Sugestão técnica

Usar:
- FlashList
- memoização
- virtualization

---

## Status

BACKLOG

---

# IMPROVEMENT-004

## Título

Adicionar suporte offline parcial.

---

## Tipo

ARQUITETURA

---

## Prioridade

BAIXA

---

## Objetivo

Melhorar experiência sem internet.

---

## Sugestão técnica

- cache local
- sincronização posterior
- retry queue

---

## Status

IDEIA

---

# IMPROVEMENT-005

## Título

Melhorar acessibilidade dos formulários.

---

## Tipo

ACESSIBILIDADE

---

## Prioridade

MÉDIA

---

## Contexto

Alguns inputs precisam de labels mais descritivas.

---

## Objetivo

Melhorar screen reader.

---

## Status

BACKLOG
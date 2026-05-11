# PERFORMANCE-001

## Problema

FlatList renderizando toda lista novamente.

---

## Causa

Funções inline dentro do renderItem.

---

## Solução

Usar useCallback.

---

## Prevenção

Nunca usar:
- funções inline
- objetos inline
- arrays inline

em listas grandes.
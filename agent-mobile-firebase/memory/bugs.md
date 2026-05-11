# BUG MEMORY

---

# BUG-001

## Título

Loop infinito no auth listener.

---

## Data

2026-05-11

---

## Contexto

O app entrava em re-render infinito ao escutar mudanças do Firebase Auth.

---

## Causa raiz

O listener estava sendo registrado múltiplas vezes dentro do componente.

---

## Solução aplicada

Mover listener para hook global de sessão.

---

## Arquivos afetados

- auth-provider.tsx
- use-auth.ts

---

## Prevenção

- Nunca registrar listeners dentro da UI
- Sempre limpar subscriptions
- Centralizar auth listeners

---

## Status

RESOLVIDO

---

# BUG-002

## Título

Token salvo inseguramente no AsyncStorage.

---

## Contexto

Sessão estava sendo persistida usando AsyncStorage.

---

## Risco

Exposição de token.

---

## Solução aplicada

Migrado para Expo SecureStore.

---

## Arquivos afetados

- auth-storage.ts

---

## Prevenção

Nunca usar AsyncStorage para:
- JWT
- refresh token
- session token

Sempre usar SecureStore.

---

## Status

RESOLVIDO

---

# BUG-003

## Título

Input aceitava caracteres inválidos.

---

## Contexto

Campo nome permitia caracteres inesperados.

---

## Solução aplicada

Implementado schema Zod + sanitização.

---

## Arquivos afetados

- user.schema.ts
- sanitize.ts

---

## Prevenção

Todo input deve:
- usar Zod
- usar sanitização
- validar frontend
- validar backend

---

## Status

RESOLVIDO
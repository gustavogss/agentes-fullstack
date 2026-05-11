# ARCHITECTURE DECISIONS

---

# DECISION-001

## Título

Frontend mobile será Expo.

---

## Status

APROVADO

---

## Motivo

- Desenvolvimento rápido
- Melhor DX
- OTA updates
- Ecossistema maduro
- Compatibilidade React Native

---

## Impacto

Toda implementação mobile deve:
- usar Expo APIs
- evitar libs incompatíveis
- respeitar Expo Router

---

# DECISION-002

## Título

TypeScript obrigatório.

---

## Status

APROVADO

---

## Regras

- Nunca usar any
- Sempre tipar retorno
- Sempre tipar props
- Sempre tipar services

---

# DECISION-003

## Título

Firebase será o backend principal.

---

## Status

APROVADO

---

## Regras

- Firebase Auth
- Firestore
- Security Rules obrigatórias
- Nunca acessar Firebase direto da UI
- Services obrigatórios

---

# DECISION-004

## Título

NativeWind será o sistema de estilização.

---

## Status

APROVADO

---

## Regras

- Evitar StyleSheet desnecessário
- Classes reutilizáveis
- UI consistente
- Respeitar design-system.md

---

# DECISION-005

## Título

Zod obrigatório em todos formulários.

---

## Status

APROVADO

---

## Regras

Todo input deve:
- validar
- sanitizar
- tratar erros

---

# DECISION-006

## Título

Tokens devem usar SecureStore.

---

## Status

APROVADO

---

## Proibido

- AsyncStorage para tokens
- Persistência insegura

---

# DECISION-007

## Título

Arquitetura feature-first.

---

## Estrutura

src/
├── features/
├── components/
├── services/
├── hooks/
├── schemas/

---

## Motivo

- Escalabilidade
- Organização
- Reutilização

---

# DECISION-008

## Título

Tela nunca acessa Firebase diretamente.

---

## Regras

UI → Hooks → Services → Firebase

---

## Motivo

- Segurança
- Testabilidade
- Escalabilidade
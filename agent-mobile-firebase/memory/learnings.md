# LEARNINGS

---

# LEARNING-001

## Título

Services desacoplados reduziram retrabalho.

---

## Contexto

Inicialmente algumas telas acessavam Firebase diretamente.

---

## Aprendizado

Separar:
UI → Hooks → Services → Firebase

melhorou:
- manutenção
- testes
- reutilização
- segurança

---

## Impacto

Arquitetura mais escalável.

---

## Aplicar futuramente

Sempre usar service layer.

---

# LEARNING-002

## Título

Zod reduziu bugs de formulário.

---

## Contexto

Inputs sem validação causavam inconsistências.

---

## Aprendizado

Schemas centralizados:
- reduziram erros
- melhoraram UX
- simplificaram tipagem

---

## Aplicar futuramente

Todo formulário deve usar:
- Zod
- React Hook Form
- sanitização

---

# LEARNING-003

## Título

Skeleton loading melhorou percepção de performance.

---

## Contexto

Usuários percebiam carregamentos como lentos.

---

## Aprendizado

Skeletons geram sensação de fluidez maior que spinners.

---

## Impacto

Melhor experiência visual.

---

## Aplicar futuramente

Priorizar skeletons em:
- listas
- cards
- dashboards

---

# LEARNING-004

## Título

Componentes grandes dificultam manutenção.

---

## Contexto

Tela onboarding ficou difícil de manter.

---

## Aprendizado

Componentes acima de 200~300 linhas:
- aumentam complexidade
- dificultam debugging
- aumentam regressões

---

## Aplicar futuramente

Dividir:
- sections
- hooks
- subcomponents

---

# LEARNING-005

## Título

NativeWind acelerou desenvolvimento UI.

---

## Contexto

Uso excessivo de StyleSheet aumentava boilerplate.

---

## Aprendizado

NativeWind:
- aumentou produtividade
- reduziu repetição
- melhorou consistência visual

---

## Aplicar futuramente

Priorizar NativeWind na UI padrão.
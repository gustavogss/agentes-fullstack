# ANIMATION GUIDELINES

# OBJETIVO

As animações devem:
- melhorar UX
- dar feedback visual
- aumentar fluidez
- melhorar percepção de performance

Nunca devem:
- atrapalhar navegação
- deixar o app lento
- exagerar visualmente

---

# PRINCÍPIOS

## PRIORIDADE

- Fluidez
- Performance
- Naturalidade
- Simplicidade

---

# REGRAS GERAIS

- Toda animação deve ter propósito
- Evitar excesso de animações simultâneas
- Nunca bloquear interação
- Nunca atrasar navegação
- Priorizar 60fps
- Preferir animações leves

---

# DURAÇÕES

## Microinterações

100ms → 180ms

---

## Navegação

200ms → 300ms

---

## Modais

250ms → 350ms

---

## Feedback visual

120ms → 200ms

---

# EASING

## Preferido

ease-out

---

## Evitar

- bounce exagerado
- elastic excessivo
- animações lentas

---

# ANIMAÇÕES PERMITIDAS

## Fade

Usar para:
- entrada de conteúdo
- loading
- estados vazios

---

## Slide

Usar para:
- navegação
- bottom sheets
- drawers

---

## Scale leve

Usar para:
- toque em botões
- feedback tátil
- cards interativos

---

## Skeleton loading

Obrigatório em:
- listas
- cards
- carregamento inicial

---

# MICROINTERAÇÕES

## Botões

Ao pressionar:
- scale leve
- feedback instantâneo

Nunca:
- animação lenta
- delay perceptível

---

## Inputs

- foco suave
- transição de borda
- feedback de erro

---

## Cards

- hover suave
- press feedback
- sem exagero

---

# LOADING STATES

## Obrigatório

Toda ação async deve ter:
- loading visual
- botão desabilitado
- feedback claro

---

# TRANSIÇÕES DE TELA

## Regras

- suaves
- rápidas
- sem travamentos

---

# PERFORMANCE

## OBRIGATÓRIO

- usar reanimated quando necessário
- evitar re-render desnecessário
- evitar animações pesadas
- evitar blur excessivo
- evitar shadow pesada

---

# PROIBIDO

- animações longas
- animações desnecessárias
- múltiplos efeitos simultâneos
- partículas
- efeitos exagerados
- excesso de spring
- animações que atrapalham acessibilidade

---

# ACESSIBILIDADE

## Respeitar

- reduce motion
- usuários sensíveis a movimento
- navegação previsível

---

# UX

## A sensação deve ser:

- rápida
- moderna
- fluida
- premium
- natural

Nunca:
- chamativa demais
- infantil
- cansativa
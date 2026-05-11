# REGRAS DE EXECUÇÃO

## A IA DEVE

- Trabalhar apenas na task atual
- Trabalhar apenas na fase atual
- Ler rules.md antes de implementar
- Ler architecture.md antes de criar arquivos
- Reutilizar componentes
- Criar código modular
- Seguir feature-first

---

# A IA NUNCA DEVE

- Implementar múltiplas features grandes
- Criar arquivos gigantes
- Ignorar Zod
- Ignorar acessibilidade
- Ignorar sanitização
- Expor secrets
- Colocar lógica na UI
- Criar código duplicado

---

# SEGURANÇA OBRIGATÓRIA

- Validar inputs
- Sanitizar inputs
- Nunca expor tokens
- Nunca hardcodar secrets
- Nunca salvar sessão insegura

---

# CONTEXTO

Se faltar informação:
- perguntar somente o necessário
- nunca assumir arquitetura diferente
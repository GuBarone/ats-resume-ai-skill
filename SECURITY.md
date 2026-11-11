# 🛡️ Política de Segurança

A segurança e a privacidade dos usuários desta Skill são prioridades absolutas. Como este projeto não consiste em um software executável, mas sim em uma engenharia de prompt (System Prompt) para LLMs, o escopo de segurança foca primariamente na proteção de dados pessoais e na mitigação de comportamentos indesejados da Inteligência Artificial.

## 📌 Escopo de Segurança

Consideramos como incidentes de segurança válidos para reporte neste repositório:

- **Vazamento Involuntário de Dados:** O prompt induz ou obriga o usuário a fornecer dados sensíveis (CPF, RG, endereço exato) que não deveriam ser solicitados.
- **Falhas de Output (Prompt Injection):** O prompt pode ser facilmente subvertido para gerar conteúdos maliciosos, ofensivos ou fora do escopo profissional de recrutamento.
- **Violações de Privacidade:** O comportamento da IA fere as diretrizes estipuladas no arquivo `AVISO_LEGAL_LGPD.md`.

_Nota: Não nos responsabilizamos pela forma como empresas terceiras (OpenAI, Google, Anthropic) processam ou armazenam os dados inseridos em seus respectivos chats._

## 🚨 Como relatar uma vulnerabilidade ou problema de privacidade

Se você encontrar um problema que se enquadre no escopo acima, **NÃO abra uma Issue pública** imediatamente, pois isso pode expor a falha antes que possamos mitigá-la na instrução principal.

1. Envie um e-mail diretamente para o mantenedor do projeto ou utilize as mensagens diretas via [LinkedIn](URL_DO_SEU_LINKEDIN).
2. Inclua no relato:
   - Qual LLM você estava utilizando (Gemini, ChatGPT, Claude, etc.).
   - O comportamento exato que a IA apresentou.
   - O trecho do prompt que você acredita estar causando a falha (se souber).
3. Tentaremos responder e aplicar as correções no arquivo `SKILL.md` o mais rápido possível, geralmente dentro de 48 horas.

## ✅ Versões Suportadas

Apenas a versão mais recente presente na branch `main` do arquivo `SKILL.md` recebe suporte e atualizações de segurança.

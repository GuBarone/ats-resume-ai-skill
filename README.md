# 🚀 ATS & AI Resume Optimizer Skill

Uma skill universal de prompt (instrução de sistema) projetada para transformar LLMs (Gemini, ChatGPT, Claude) em especialistas de recrutamento. O foco principal é criar do zero, reescrever e otimizar currículos para contornar os filtros de **Applicant Tracking Systems (ATS)** e algoritmos de triagem por Inteligência Artificial.

## 🎯 Por que usar esta Skill?

Empresas modernas utilizam softwares de triagem que leem currículos em busca de palavras-chave, estruturas lineares e padrões específicos. Um currículo visualmente bonito, mas mal estruturado em texto, é frequentemente descartado antes de chegar a um humano. Esta skill garante que o seu currículo "fale a língua" dos robôs de recrutamento e gera um arquivo pronto para envio.

## 🛠️ Como Utilizar

1. Copie o conteúdo do arquivo [`SKILL.md`](SKILL.md).
2. Cole na seção de configuração da sua IA preferida:
   - **Gemini:** Crie uma nova "Habilidade" (a partir de 17/11, as Habilidades substituem os antigos "Gems" e as instruções personalizadas).
   - **ChatGPT:** Cole na seção "Custom Instructions" ou crie um GPT personalizado.
   - **Claude:** Utilize a funcionalidade de "Projects" para adicionar o prompt de sistema.
3. Inicie a conversa. Você tem duas opções:
   - **Opção A (Atualização):** Envie seu currículo atual em anexo (PDF ou texto) e peça para a IA otimizá-lo.
   - **Opção B (Criação do Zero):** Apenas diga "Quero criar meu currículo". A skill ativará o **Modo Questionário**, fazendo perguntas pontuais sobre sua carreira, idiomas e tecnologias para montar o documento perfeito do zero.

## ✨ Funcionalidades Principais

- **Integração de Memória:** Puxa o histórico de ferramentas e área de atuação salvos no perfil da IA.
- **Modo Questionário:** Guia o usuário caso faltem informações cruciais (idiomas, hard skills).
- **Exportação em `.docx`:** A IA é instruída a gerar um arquivo Word pronto para download, facilitando edições futuras e garantindo a melhor compatibilidade com leitores ATS.

## 🗂️ Estrutura do Repositório

- [`SKILL.md`](SKILL.md): O código-fonte do prompt para ser injetado na IA.
- [`docs/BOAS_PRATICAS_ATS.md`](docs/BOAS_PRATICAS_ATS.md): Documentação técnica de como os parsers funcionam e as regras aplicadas.
- [`docs/AVISO_LEGAL_LGPD.md`](docs/AVISO_LEGAL_LGPD.md): Termos de uso, privacidade e proteção de dados sensíveis.

## ⚖️ Licença e Contribuições

Sinta-se à vontade para abrir _issues_ ou enviar _pull requests_ com sugestões. Este projeto está sob a licença [INSERIR NOME DA LICENÇA AQUI, ex: GNU GPLv3], protegendo os direitos de uso e garantindo que permaneça open-source.

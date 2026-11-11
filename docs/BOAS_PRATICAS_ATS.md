# ⚙️ Boas Práticas ATS: Os Bastidores da Skill

A `SKILL.md` deste repositório foi construída com base em regras estritas de parsing (análise sintática) que os Applicant Tracking Systems utilizam. Aqui detalhamos o porquê de cada instrução contida na skill.

### 1. Formato de Arquivo: Por que exigimos o `.docx`?

Embora o PDF seja ótimo para manter a formatação visual, ele pode ser o pior inimigo de sistemas ATS antigos. Dependendo de como o PDF é exportado, o texto pode ser lido como uma imagem ou ter as quebras de linha corrompidas. O formato `.docx` (Microsoft Word) é estruturado nativamente em texto puro sob o capô (XML), garantindo 100% de taxa de acerto na leitura do robô. A skill exige a exportação em `.docx` por esse motivo.

### 2. Ausência de Tabelas e Colunas (Estrutura Linear)

**O problema:** Parsers de ATS leem documentos da esquerda para a direita, linha por linha. Se o seu currículo tem duas colunas (ex: contatos na esquerda, experiência na direita), o robô vai misturar o telefone com o nome da empresa, gerando um perfil ilegível.
**A solução:** A skill formata o currículo de forma 100% linear, garantindo que o algoritmo entenda a hierarquia dos dados.

### 3. Título do Objetivo

Algoritmos de IA cruzam a requisição da vaga (Job Description) com o topo do seu currículo. A skill insere o nome exato do cargo desejado logo no início para garantir o "match" inicial de indexação.

### 4. Palavras-Chave (Keywords)

Sistemas de triagem utilizam processamento de linguagem natural (NLP) para contar a frequência e o contexto de termos técnicos. A skill puxa do seu perfil as ferramentas que você usa e as injeta organicamente na seção de "Resumo de Qualificações".

### 5. Verbos de Ação

IAs são treinadas para identificar o impacto que você causou, não apenas suas obrigações. A skill reescreve experiências inserindo verbos de ação proativos ("Desenvolveu", "Otimizou") voltados a resultados.

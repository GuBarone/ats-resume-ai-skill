# ⚙️ Boas Práticas ATS: Os Bastidores da Skill

A `SKILL.md` deste repositório foi construída com base em regras estritas de parsing (análise sintática) de Applicant Tracking Systems, além de focar na eficiência de consumo de _tokens_ das LLMs. Aqui detalhamos o porquê de cada instrução contida na skill.

### 1. Pesquisa Web Integrada (LinkedIn)

O mercado de tecnologia e negócios muda rapidamente. A skill instrui a IA a fazer uma varredura nas vagas recém-publicadas no LinkedIn utilizando o cargo pretendido pelo usuário. Isso garante que o currículo não use palavras-chave genéricas, mas sim os termos exatos que os recrutadores estão configurando em seus filtros ATS naquele exato momento.

### 2. Design Minimalista e Economia de Tokens

A instrução exige a criação de um documento em página única, preto e branco e sem formatação excessiva (como tabelas coloridas ou gráficos de habilidades). Há dois motivos para isso:

- **Parseabilidade (ATS):** Robôs não leem design. Elementos gráficos, caixas de texto flutuantes ou barras de progresso frequentemente corrompem a extração de dados.
- **Eficiência da LLM:** IAs consomem _tokens_ para gerar respostas. Obrigar a IA a tentar desenhar um currículo visualmente complexo utilizando código desperdiça o limite de processamento e aumenta a chance de alucinações. O layout limpo mantém a IA focada na qualidade do conteúdo.

### 3. Formato de Arquivo: Por que exigimos o `.docx`?

Embora o PDF seja ótimo para manter a formatação visual, ele pode ser o pior inimigo de sistemas ATS antigos (que muitas vezes leem a página como imagem). O formato `.docx` (Microsoft Word) é estruturado nativamente em texto puro sob o capô (XML), garantindo altíssima taxa de acerto na leitura do robô.

### 4. Título do Objetivo

Algoritmos de IA cruzam a requisição da vaga (Job Description) com o topo do seu currículo. A skill exige o nome exato do cargo desejado (sem tentar "adivinhar" o que o usuário quer) logo no início para garantir o "match" inicial de indexação.

### 5. Verbos de Ação e Resultados

IAs são treinadas para identificar o impacto que você causou, não apenas suas obrigações. A skill reescreve experiências inserindo verbos de ação proativos ("Desenvolveu", "Otimizou") voltados a resultados.

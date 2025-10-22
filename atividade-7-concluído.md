# Atividade 7 - Coleta de Dados de Usuários

**Equipe:** Cayque Cicarelli, Arthur Veloso, Yuri Bykoff  
**Projeto:** Detecção de Deepfakes utilizando EfficientNet-B0 para Conscientização Digital

---

## 1. Que dados coletar?

### 1.1. Dados sobre o usuário
- **Demográficos:** idade, gênero, profissão, escolaridade, localização.
- **Idiomas e jargões:** familiaridade com termos como "deepfake", "IA", "manipulação digital", linguagem técnica vs. simplificada.

**Justificativa:**  
Permite adaptar a interface e o conteúdo educativo ao perfil real dos usuários (estudantes, jornalistas, professores, influencers).

---

### 1.2. Relação com tecnologia
- **Nível de alfabetismo digital:** familiaridade com computadores, smartphones, upload de arquivos, navegação web.
- **Produtos e ferramentas já utilizadas:** redes sociais, apps de verificação, plataformas educacionais.
- **Tecnologia disponível:** dispositivos (mobile/desktop), sistema operacional, velocidade de internet.

**Justificativa:**  
Define o grau de complexidade apropriado da interface e funcionalidades (interface simples para leigos, recursos avançados para especialistas).

---

### 1.3. Conhecimento do domínio
- **Compreensão sobre deepfakes:** o que sabe, se já teve contato, nível de especialização (leigo, intermediário, especialista).
- **Experiência com verificação de conteúdo:** métodos atuais, ferramentas conhecidas, práticas de checagem.

**Justificativa:**  
Define se a interface e conteúdo devem ser mais explicativos (para iniciantes como Gabriel, 16 anos) ou mais diretos (para profissionais como jornalistas).

---

### 1.4. Dados sobre as tarefas
- **Objetivos principais:** Por que precisa verificar deepfakes? Decisões que tomará com o resultado?
- **Tarefas primárias:** upload de mídia, visualização de resultado, compartilhamento, busca por conteúdo educativo.
- **Tarefas secundárias:** ajustes de configuração, download de relatório, comparação de análises.
- **Frequência de uso:** diária, semanal, esporádica.
- **Gravidade dos erros:** consequências de falso positivo ou falso negativo (especialmente crítico para jornalistas).

**Justificativa:**  
Permite projetar interface centrada nas tarefas reais, priorizando funcionalidades essenciais e reduzindo riscos de erro.

---

### 1.5. Motivações e valores
- **Motivações:** proteção contra desinformação, segurança da própria imagem, educação, responsabilidade profissional, curiosidade.
- **Valores esperados:** transparência dos resultados, privacidade de dados, velocidade vs. precisão, simplicidade vs. recursos avançados.
- **Benefícios desejados:** empoderamento digital, confiabilidade, facilidade de uso, conhecimento sobre o tema.

**Justificativa:**  
Define requisitos motivacionais e fatores de engajamento, garantindo que a plataforma atenda expectativas e promova uso contínuo.

---

## 2. De quem coletar?

### Usuários finais:
- **Estudantes** (jornalismo, comunicação, ensino médio) → precisam aprender e verificar conteúdo
- **Jornalistas e criadores de conteúdo** → necessitam autenticar mídia antes de publicar/compartilhar
- **Professores e educadores** → buscam material didático confiável sobre deepfakes
- **Influencers digitais** → querem proteger sua imagem e reputação online

### Stakeholders:
- **Orientadores do projeto** → definem requisitos técnicos e acadêmicos
- **Veículos de comunicação** → potenciais usuários corporativos, fornecem casos de uso reais
- **Organizações educacionais** → podem adotar a plataforma, influenciam requisitos pedagógicos

### Especialistas no domínio:
- **Pesquisadores em IA/visão computacional** → validam precisão técnica e limitações dos algoritmos
- **Jornalistas investigativos e fact-checkers** → conhecem necessidades práticas de verificação
- **Educadores em mídia digital** → orientam sobre comunicação eficaz de conceitos técnicos

### Indiretamente afetados:
- **Público geral** → beneficiado pela redução de desinformação
- **Criadores de conteúdo legítimo** → impactados por falsos positivos (precisão é crítica)
- **Vítimas de deepfakes maliciosos** → interesse na eficácia do sistema

**Justificativa:**  
Coletar dados desses grupos garante que o sistema atenda necessidades de uso, objetivos organizacionais e responsabilidade social.

---

## 3. Aspectos Éticos

### O projeto deverá considerar aspectos éticos?

**Sim.** O projeto envolve coleta de dados pessoais (através de entrevistas, questionários e grupos focais) e desenvolvimento de tecnologia que impacta percepção pública sobre autenticidade de conteúdo.

### Justificativa baseada nos princípios da aula:

**1. Princípio da Autonomia:**
- Respeitar capacidade de decisão informada dos participantes
- Aplicação: consentimento livre e esclarecido, direito de recusa e desistência, transparência sobre uso dos dados

**2. Princípio da Não-Maleficência:**
- Não causar dano intencional, evitar riscos previsíveis
- Riscos identificados: desconforto emocional ao discutir desinformação, risco de privacidade, constrangimento
- Medidas: ambiente seguro, linguagem neutra, anonimização de dados, segurança digital

**3. Princípio da Beneficência:**
- Maximizar benefícios (empoderamento digital, redução de desinformação, proteção de reputação)
- Minimizar riscos (tempo investido, desconforto mínimo)
- Equilíbrio: benefícios coletivos superam riscos individuais mínimos

**4. Princípio da Justiça e Equidade:**
- Garantir diversidade de participantes (idades, profissões, níveis de alfabetização digital)
- Evitar exclusão de grupos vulneráveis
- Atenção especial: menores de idade (autorização dos responsáveis), pessoas com baixa alfabetização digital

### Procedimentos éticos aplicados:
- Termo de Consentimento Livre e Esclarecido (TCLE)
- Garantia de confidencialidade e anonimato
- Permissão para gravação (quando aplicável)
- Armazenamento seguro e conformidade com LGPD
- Direito de desistir a qualquer momento sem prejuízo

---

## 4. Ferramentas de Coleta de Dados

### 4.1. Entrevista Semiestruturada

**Objetivo:**  
Coletar informações aprofundadas sobre experiências, percepções e expectativas dos usuários em relação à detecção de deepfakes, compreendendo contextos individuais e motivações.

**Como aplicar:**
- Selecionar 4-6 participantes representativos das personas
- Aplicar individualmente, presencial ou remoto (Google Meet)
- Duração: 30-45 minutos
- Roteiro com perguntas abertas e fechadas sobre:
  - Perfil e contexto de uso
  - Conhecimento sobre deepfakes e experiências passadas
  - Práticas atuais de verificação de conteúdo
  - Expectativas e funcionalidades desejadas
  - Preocupações com confiança, segurança e privacidade
- Gravar com permissão, transcrever e anonimizar dados
- Garantir consentimento e respeito aos princípios éticos

**Instrumento:**  
[Roteiro de Entrevista](https://github.com/user-attachments/files/23057406/entrevista.pdf)


---

### 4.2. Questionário Online

**Objetivo:**  
Coletar dados quantitativos em larga escala sobre perfil demográfico, hábitos de consumo de conteúdo, conhecimento sobre deepfakes e expectativas em relação à plataforma.

**Como aplicar:**
- Elaborar formulário no Google Forms com:
  - Perguntas demográficas (idade, profissão, escolaridade)
  - Relação com tecnologia (frequência de uso, ferramentas conhecidas)
  - Conhecimento sobre deepfakes (já viu, já foi enganado, preocupações)
  - Práticas de verificação (métodos atuais, frequência de compartilhamento)
  - Expectativas (funcionalidades desejadas, dispositivo preferido, interesse educativo)
  - Perguntas abertas para sugestões
- Divulgar em redes sociais, grupos de WhatsApp, e-mails, parcerias com professores/influencers
- Período de coleta: 7-14 dias
- Meta: mínimo 30-50 respostas
- Análise estatística: percentuais, correlações, gráficos visuais

**Instrumento:**  
[Questionário Google Forms](https://forms.gle/gQsknX6wk1ZSyFX76)

---

### 4.3. Grupo Focal

**Objetivo:**  
Obter múltiplos pontos de vista através de discussão coletiva, identificando consensos, divergências e gerando ideias colaborativas sobre a plataforma de detecção de deepfakes.

**Como aplicar:**
- Reunir 6-10 participantes com perfis variados
- Duração: 90 minutos
- Moderador conduz discussão em ambiente confortável (presencial ou remoto)
- Estrutura:
  - Abertura e quebra-gelo (10 min)
  - Exploração de experiências com deepfakes (20 min)
  - Práticas atuais de verificação (15 min)
  - Apresentação do conceito da plataforma (10 min)
  - Avaliação da interface e funcionalidades (25 min)
  - Brainstorming de sugestões (15 min)
  - Encerramento (10 min)
- Gravar com permissão, transcrever e anonimizar
- Analisar padrões recorrentes, consensos e divergências

**Instrumento:**  
[Roteiro de Grupo Focal](https://github.com/user-attachments/files/23057441/grupo-focal.pdf)



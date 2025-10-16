# **Entrega 5 - Análise de Tarefas (22/09)**

**Análise de Tarefas**

Para esta entrega, modelamos três funcionalidades centrais da plataforma de detecção de deepfakes, utilizando diferentes técnicas de análise de tarefas. Cada funcionalidade foi analisada por um membro da equipe, considerando as necessidades identificadas nas personas e cenários desenvolvidos anteriormente.

---

## **1) HTA (Hierarchical Task Analysis)**
**Funcionalidade: Upload e Análise de Imagem para Detecção de Deepfake**
**(Autor: Cayque)**

### Descrição da Funcionalidade:
Esta funcionalidade permite que usuários façam upload de um arquivo de imagem para verificar se ela contém deepfakes. O sistema processa a imagem utilizando algoritmos de IA (EfficientNet-B0) e retorna um resultado com indicadores de confiabilidade, atendendo especialmente à persona Rafael Oliveira (jornalista) que precisa verificar conteúdo antes da publicação.

### Diagrama HTA:
![HTA](https://github.com/user-attachments/assets/f193a62f-0fd5-4376-b3d3-6ac2f60ff0ad)

---

## **2) GOMS (Goals, Operators, Methods, Selection Rules)**
**Funcionalidade: Navegação na Seção Educativa sobre Deepfakes**
**(Autor: Arthur)**

### Descrição da Funcionalidade:
Esta funcionalidade permite aos usuários explorar conteúdo educativo sobre deepfakes, incluindo artigos, vídeos explicativos e exemplos práticos. Atende especialmente à persona Ana Paula Mendes (professora) que busca material didático para suas aulas sobre ética digital.

### Modelo GOMS:

**GOAL:** Encontrar e consumir conteúdo educativo sobre deepfakes

**METHOD 1:** Busca por categoria temática
- **OPERATOR:** Clicar em "Seção Educativa" no menu principal
- **OPERATOR:** Selecionar categoria desejada (ex: "O que são Deepfakes")
- **OPERATOR:** Navegar pelos itens da categoria
- **OPERATOR:** Clicar no conteúdo de interesse
- **OPERATOR:** Ler/assistir o conteúdo completo
- **OPERATOR:** Avaliar utilidade do material (opcional)

**METHOD 2:** Busca por palavra-chave
- **OPERATOR:** Clicar na barra de pesquisa da seção educativa
- **OPERATOR:** Digitar termo de busca
- **OPERATOR:** Pressionar Enter ou clicar em "Buscar"
- **OPERATOR:** Analisar resultados apresentados
- **OPERATOR:** Clicar no item mais relevante
- **OPERATOR:** Consumir o conteúdo
- **OPERATOR:** Refinar busca se necessário

**METHOD 3:** Exploração guiada por trilha de aprendizagem
- **OPERATOR:** Clicar em "Trilhas de Aprendizagem"
- **OPERATOR:** Escolher nível (Iniciante/Intermediário/Avançado)
- **OPERATOR:** Selecionar trilha temática
- **OPERATOR:** Seguir sequência sugerida de conteúdos
- **OPERATOR:** Marcar progresso em cada etapa
- **OPERATOR:** Continuar até completar trilha

**SELECTION RULES:**
- **Rule 1:** Se o usuário tem objetivo específico de aprendizagem → usar METHOD 3
- **Rule 2:** Se o usuário busca informação pontual → usar METHOD 2  
- **Rule 3:** Se o usuário quer explorar amplamente o tema → usar METHOD 1
- **Rule 4:** Se o usuário é professor preparando aula → combinar METHOD 1 + METHOD 3

---

## **3) CTT (ConcurTaskTrees)**
**Funcionalidade: Visualização e Interpretação de Resultados de Análise**
**(Autor: Yuri)**

### Descrição da Funcionalidade:
Esta funcionalidade permite que usuários visualizem e compreendam os resultados da análise de deepfake de uma imagem enviada. O sistema apresenta os resultados de forma clara e intuitiva, com explicações detalhadas para diferentes níveis de usuário. Atende especialmente às personas que precisam de informações confiáveis e compreensíveis sobre a autenticidade das imagens analisadas.

### Diagrama CTT:

```
Visualizar e Interpretar Resultados
├── Aguardar Processamento
│   ├── Observar Barra de Progresso
│   └── Receber Notificação de Conclusão
│
├── Analisar Resultado Principal
│   ├── Ler Pontuação Geral
│   ├── Interpretar Classificação
│   └── Compreender Veredito
│
├── Explorar Detalhes Técnicos
│   ├── Examinar Indicadores Visuais [ ]
│   ├── Analisar Gráficos de Confiança [ ]
│   ├── Ler Explicação Técnica [ ]
│   └── Ver Regiões Suspeitas [ ]
│
├── Obter Explicações → "Saiba Mais"
│   ├── Ler Explicação Simplificada
│   ├── Ver Exemplos Comparativos [ ]
│   └── Acessar Glossário [ ]
│
└── Ações Pós-Análise
    ├── Salvar Resultado [ ]
    ├── Baixar Relatório PDF [ ] → Escolher Formato
    ├── Compartilhar Link [ ]
    └── Analisar Nova Imagem [ ]

```

### Legenda CTT:
- **[]** = Tarefa opcional
- **()** = Tarefa elementar (ação do usuário)
- **||| ** = Tarefa concorrente (pode ser executada simultaneamente)
- **>>** = Tarefa com habilitação (uma habilita a outra)
- **Sem símbolo** = Tarefa abstrata (composta por subtarefas)

### Cenário de Execução:
1. **Aguardo:** Usuário observa o progresso do processamento da imagem enviada
2. **Análise paralela:** Simultaneamente examina o resultado principal (pontuação e veredicto) e pode explorar detalhes técnicos opcionais
3. **Aprofundamento:** Se necessário, acessa explicações adicionais para compreender melhor o resultado
4. **Ações finais:** Realiza ações conforme sua necessidade (salvar, baixar relatório, compartilhar ou analisar nova imagem)


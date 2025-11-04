# **Entrega 5 - Análise de Tarefas (22/09)**

### **1) HTA (Hierarchical Task Analysis):**
**Autor:** Cayque

**Funcionalidade:** <br>
Upload e Análise de Imagem para Detecção de Deepfake.

**Descrição da Funcionalidade:** <br>
Esta funcionalidade permite que usuários façam upload de um arquivo de imagem para verificar se ela contém deepfakes. O sistema processa a imagem utilizando algoritmos de IA (EfficientNet-B0) e retorna um resultado com indicadores de confiabilidade.

**Diagrama:** <br>
![HTA_VerificarIMG](https://github.com/user-attachments/assets/991fa6de-849f-45e7-827b-540bbf60bb77)

**Tabela:**
| Objetivos/Operações | Problemas/Recomendações |
|:--------------------|:------------------------|
| 0. Verificar se a imagem é um deepfake 1>2>3>4>5 | **Input:** Relatório detalhado contendo a informação se a imagem enviada é ou não deepfake. <br> **Feedback:** relatório gerado, possibilitando a avaliação do resultado por parte do usuário. <br> **Plano:** Preparar arquivo de imagem e depois acessar sistema de upload e depois realizar upload do arquivo e depois executar análise e depois visualizar e interpretar resultado. <br> |
| 1. Preparar arquivo de imagem 1>2+3 | Plano: Localizar arquivo no dispositivo e depois verificar formato compatível (JPG; PNG) e confirmar tamanho do arquivo (máx. 10MB)|
| 1.1. Localizar arquivo no dispositivo | |
| 1.2 Verificar formato compatível (JPG; PNG) | |
| 1.3 Confirmar tamanho do arquivo (máx. 10MB) | |
| 2. Acessar sistema de upload 1>2 | Plano: Navegar para seção "Detector" e depois clicar em "Analisar Imagem" |
| 2.1. Navegar para seção "Detector" | |
| 2.2. Clicar em "Analisar Imagem" | |
| 3. Realizar upload do arquivo 1/2>3>4 | Plano: Clicar em "Selecionar arquivo" ou arrastar um arquivo e depois confirmar seleção e depois visualizar prévia da imagem selecionada |
| 3.1 Clicar em "Selecionar arquivo" | |
| 3.2. Arrastar um arquivo | |
| 3.3. Confirmar seleção | |
| 3.4. Visualizar prévia da imagem selecionada | Recomendação: Alerta sobre imagem carregada com sucesso |
| 4. Executar análise 1>2+3 | Plano: Clicar em "Iniciar Análise" e depois acompanhar barra de progresso e aguardar processamento completo |
| 4.1. Clicar em "Iniciar Análise" | |
| 4.2. Acompanhar barra de progresso | |
| 4.3. Aguardar processamento completo | |
| 5. Visualizar e interpretar resultado 1+2+3 | Plano: Analisar pontuação de autenticidade (0% - 100%) e Examinar indicadores visuais da imagem e baixar relatório |
| 5.1. Analisar pontuação de autenticidade (0% - 100%) | |
| 5.2 Examinar indicadores visuais da imagem | |
| 5.3. Baixar relatório | Ação: relatório disponível para download enquanto a página web estiver aberta. |

---

### **1) HTA (Hierarchical Task Analysis):**
**Autor:** Arthur

**Funcionalidade:** <br>
Compartilhar análises deepfakes

**Descrição da Funcionalidade:** <br>
Esta funcionalidade permite que usuários compartilhem resultados de análises de imagens (possivelmente deepfakes) através de diferentes canais de comunicação.

**Diagrama:** <br>
![HTA_ARTHUR (3)](https://github.com/user-attachments/assets/ca073265-465b-4d01-ac3a-8745a6e3b8ea)

**Tabela:**
| Objetivos/Operações | Problemas/Recomendações |
|:--------------------|:------------------------|
|0. Permitir compartilhar análises de imagens possivelmente deepfakes. 1>2>3>4|**Input:** Análise de imagem realizada por meio da plataforma e geração de gráficos correspondentes gerados.<br> **Feedback:** Compartilhar a análise por aplicativos de mensagem, redes sociais ou e-mail.<br> **Plano:** Selecionar resultado a ser compartilhado e depois selecionar o canal de compartilhamento e depois configurar canal de compartilhamento e depois enviar compartilhamento. <br>|
|1. Selecionar resultado a ser compartilhado. 1>2|**Plano:** Visualizar resultado da análise por meio da interface e depois pressionar o botão de compartilhar análise.|
|1.1. Visualizar resultado da análise por meio da interface.| |
|1.2. Pressionar o botão de compartilhar análise.| |
|2. Selecionar o canal de compartilhamento. 1/2/3|**Plano:** Selecionar um icon de alguma rede social (instagram, facebook, X) ou selecionar um icon de algum aplicativo de mensagens (whatsapp, telegram) ou selecionar um icon de alguma plataforma de email (outlook, gmail).|
|2.1. Selecionar um icon de alguma rede social (instagram, facebook, X).| |
|2.2. Selecionar um icon de algum aplicativo de mensagens (whatsapp, telegram).| |
|2.3. Selecionar um icon de alguma plataforma de email (outlook, gmail).| |
|3. Configurar canal de compartilhamento. 1/2/3|**Plano:** Configurar envio no formato de redes sociais ou configurar envio para aplicativos de mensagem ou configurar envio para email.|
|3.1. Configurar envio no formato de redes sociais. 1+2|**Plano:** Inserir link gerado pela plataforma e adicionar comentário opcional.|
|3.1.1. Inserir link gerado pela plataforma.| |
|3.1.2. Adicionar comentário opcional.| |
|3.2. Configurar envio para aplicativos de mensagem. 1>2+3|**Plano:** Selecionar contato ou grupo e depois inserir link gerado pela plataforma e adicionar texto opcional.
Ação: O compartilhamento é habilitado somente para dispositivos móveis.|
|3.2.1. Selecionar contato ou grupo.|**Ação:** O contato deve estar salvo na lista telefônica no aparelho móvel.|
|3.2.2. Inserir link gerado pela plataforma.| |
|3.2.3. Adicionar texto opcional.| |
|3.3. Configurar envio para email. 1+2+3|**Plano:** Inserir destinatário(s) e adicionar mensagem ao email e inserir link da plataforma.|
|3.3.1. Inserir destinatário(s).| |
|3.3.2. Adicionar mensagem ao email.| |
|3.3.3. Inserir link da plataforma.| |
|4. Enviar compartilhamento.| |
---

### **1) HTA (Hierarchical Task Analysis):**
**Autor:** Yuri

**Funcionalidade:** <br>
Apresentar informações sobre deepfakes.

**Descrição da Funcionalidade:** <br>
Apresenta o processo de aprendizado sobre deepfakes, guiando o usuário desde o acesso à página educativa até a compreensão do conteúdo e do vídeo explicativo.

**Diagrama:** <br>
![HTA (2)](https://github.com/user-attachments/assets/4b62efbf-e709-4284-9ded-26287cf73b6c)

**Tabela:**
| Objetivos/Operações | Problemas/Recomendações |
|:--------------------|:------------------------|
|0. Aprender mais sobre deepfakes. 1>2+3|**Input**: Acesso a plataforma web.<br> **Feedback:** Engajamento sobre tema de deepfakes.<br> **Plano:** Acessar a página edutativa e depois ler o conteúdo introdutório e assistir ao vídeo explicando sobre deepfakes. <br>|
|1. Acessar a página educativa. 1>2|**Plano:** Localizar o menu principal e depois selecionar o botão "Educação".|
|1.1. Localizar o menu principal.| |
|1.2. Selecionar o botão "Educação".| |
|2. Ler o conteúdo introdutório. 1+2+3+4|**Plano:** Ler a definição de deepfake apresentada e visualizar exemplos ilustrativos e compreender a diferença entre imagens reais e manipuladas e ler sobre o impacto social dos deepfakes.|
|2.1. Ler a definição de deepfake apresentada.| |
|2.2. Visualizar exemplos ilustrativos.| |
|2.3. Compreender a diferença entre imagens reais e manipuladas.| |
|2.4. Ler sobre o impacto social dos deepfakes.| |
|3. Assistir ao vídeo explicativo sobre deepfakes.| |

---

## **2) GOMS (Goals, Operators, Methods, Selection Rules)**
**Funcionalidade: Upload e Análise de Imagem para Detecção de Deepfake.** <br>
**(Autor: Cayque)**

### Descrição da Funcionalidade:
Esta funcionalidade permite que usuários façam upload de um arquivo de imagem para verificar se ela contém deepfakes. O sistema processa a imagem utilizando algoritmos de IA (EfficientNet-B0) e retorna um resultado com indicadores de confiabilidade.

### Modelo GOMS:

```
GOAL 0: Verificar se a imagem é um deepfake

    GOAL 1: Preparar arquivo de imagem
        OP. 1.1: Localizar arquivo no dispositivo
        OP. 1.2: Verificar formato compatível (JPG, PNG)
        OP. 1.3: Confirmar tamanho do arquivo (máx. 10MB)
        OP. 1.4: Verificar se arquivo está pronto para upload

    GOAL 2: Acessar sistema de upload
        OP. 2.1: Navegar para seção "Detector"
        OP. 2.2: Clicar em "Analisar Imagem"
        OP. 2.3: Verificar acesso à interface de upload

    GOAL 3: Realizar upload do arquivo
        METHOD 3.A: Upload por seleção manual
          (SEL. RULE: usuário prefere seleção por interface ou não conhece arrastar)
          OP. 3.A.1: Clicar em "Selecionar arquivo"
          OP. 3.A.2: Confirmar seleção
          OP. 3.A.3: Visualizar prévia da imagem selecionada
          OP. 3.A.4: Verificar que imagem foi carregada corretamente

        **METHOD 3.B:** Upload por arrastar arquivo
          (SEL. RULE: usuário conhece funcionalidade de arrastar e prefere este método)
          OP. 3.B.1: Arrastar um arquivo para área de upload
          OP. 3.B.2: Visualizar prévia da imagem selecionada
          OP. 3.B.3: Verificar que imagem foi carregada corretamente

      GOAL 4: Executar análise <br>
        OP. 4.1: Clicar em "Iniciar Análise"
        OP. 4.2: Acompanhar barra de progresso
        OP. 4.3: Aguardar processamento completo
        OP. 4.4: Verificar conclusão da análise

    GOAL 5: Visualizar e interpretar resultado <br>
        OP. 5.1: Analisar pontuação de autenticidade (0% - 100%)
        OP. 5.2: Examinar indicadores visuais da imagem
        OP. 5.3: Baixar relatório
        OP. 5.4: Verificar compreensão do resultado obtido
```
---
## **2) GOMS (Goals, Operators, Methods, Selection Rules)**
**Funcionalidade: Compartilhar análises deepfakes.** <br>
**(Autor: Arthur)**

### Descrição da Funcionalidade:
Esta funcionalidade permite que usuários compartilhem resultados de análises de imagens (possivelmente deepfakes) através de diferentes canais de comunicação.

### Modelo GOMS:

```
GOAL 0: Permitir compartilhar análises de imagens possivelmente deepfakes

  GOAL 1: Selecionar resultado a ser compartilhado
      OP. 1.1: Visualizar resultado da análise por meio da interface
      OP. 1.2: Pressionar o botão de compartilhar análise
      OP. 1.3: Verificar icones de apps para compartilhamento

  GOAL 2: Selecionar o canal de compartilhamento
    METHOD 2.A: Compartilhar em rede social
      (SEL. RULE: usuário deseja compartilhar publicamente ou com amigos em redes sociais)
          OP. 2.A.1: Selecionar um ícone de alguma rede social (instagram, facebook, X)
          OP. 2.A.2: Verificar redirecionamento para plataforma

    METHOD 2.B: Compartilhar via aplicativo de mensagem
          (SEL. RULE: usuário prefere mensageiro instantâneo)
          OP. 2.B.1: Selecionar um ícone de algum aplicativo de mensagens (whatsapp, telegram)
          OP. 2.B.2: Verificar abertura do aplicativo

    METHOD 2.C: Compartilhar via email
      (SEL. RULE: usuário deseja compartilhamento formal ou com múltiplos destinatários)
          OP. 2.C.1: Selecionar um ícone de alguma plataforma de email (outlook, gmail)
          OP. 2.C.2: Verificar abertura do cliente de email

  GOAL 3: Configurar canal de compartilhamento
    METHOD 3.A: Configurar envio para redes sociais
      (SEL. RULE: canal selecionado foi rede social)
      OP. 3.A.1: Inserir link gerado pela plataforma
      OP. 3.A.2: Adicionar comentário opcional
      OP. 3.A.3: Verificar configuração do compartilhamento

    METHOD 3.B: Configurar envio para aplicativo de mensagem.
      (SEL. RULE: canal selecionado foi aplicativo de mensagem)
      OP. 3.B.1: Selecionar contato ou grupo
      OP. 3.B.2: Inserir link gerado pela plataforma
      OP. 3.B.3: Adicionar texto opcional
      OP. 3.B.4: Verificar seleção do destinatário

    METHOD 3.C: Configurar envio para email
      (SEL. RULE: canal selecionado foi email)
      OP. 3.C.1: Inserir destinatário(s)
      OP. 3.C.2: Adicionar mensagem ao email
      OP. 3.C.3: Inserir link da plataforma
      OP. 3.C.4: Verificar configuração do email

  OP. 4: Enviar compartilhamento
```
---
## **2) GOMS (Goals, Operators, Methods, Selection Rules)**
**Funcionalidade: Apresentar informações sobre deepfakes.** <br>
**(Autor: Yuri)**

### Descrição da Funcionalidade:
Apresenta o processo de aprendizado sobre deepfakes, guiando o usuário desde o acesso à página educativa até a compreensão do conteúdo e do vídeo explicativo.

### Modelo GOMS:

```
GOAL 0: Aprender mais sobre deepfakes

  GOAL 1: Acessar a página educativa
      OP. 1.1: Localizar o menu principal
      OP. 1.2: Selecionar o botão "Educação"
      OP. 1.3: Verificar carregamento da página educativa

  GOAL 2: Ler o conteúdo introdutório
    METHOD 2.A: Leitura da definição de deepfake
      (SEL. RULE: usuário deseja compreender conceito básico primeiro)
      OP. 2.A.1: Ler a definição de deepfake apresentada
      OP. 2.A.2: Verificar compreensão do conceito

    METHOD 2.B: Visualização de exemplos ilustrativos
      (SEL. RULE: usuário prefere aprendizado visual)
      OP. 2.B.1: Visualizar exemplos ilustrativos
      OP. 2.B.2: Verificar compreensão dos exemplos

    METHOD 2.C: Compreensão de diferenças entre imagens
      (SEL. RULE: usuário deseja entender critérios de identificação)
      OP. 2.C.1: Compreender a diferença entre imagens reais e manipuladas
      OP. 2.C.2: Verificar entendimento das características distintivas

    METHOD 2.D: Leitura sobre impacto social
      (SEL. RULE: usuário deseja contexto mais amplo sobre deepfakes)
      OP. 2.D.1: Ler sobre o impacto social dos deepfakes
      OP. 2.D.2: Verificar compreensão das implicações sociais

  OP. 3: Assistir ao vídeo explicativo sobre deepfakes
```

---

## **3) CTT (ConcurTaskTrees)**
**Funcionalidade: Upload e Análise de Imagem para Detecção de Deepfake.** <br>
**(Autor: Cayque)**

### Descrição da Funcionalidade:
Esta funcionalidade permite que usuários façam upload de um arquivo de imagem para verificar se ela contém deepfakes. O sistema processa a imagem utilizando algoritmos de IA (EfficientNet-B0) e retorna um resultado com indicadores de confiabilidade.

### Diagrama CTT:
![CTTUploadImagem](https://github.com/user-attachments/assets/3aee57e9-545b-4141-b216-9dfeb4e728e6)

---
## **3) CTT (ConcurTaskTrees)**
**Funcionalidade: Compartilhar análises deepfakes.** <br>
**(Autor: Arthur)**

### Descrição da Funcionalidade:
Esta funcionalidade permite que usuários compartilhem resultados de análises de imagens (possivelmente deepfakes) através de diferentes canais de comunicação.

### Diagrama CTT:

```
Permitir compartilhar análises de imagens possivelmente deepfakes
|
[>> (ativação sequencial)
|
+-- Selecionar resultado a ser compartilhado (abstrata)
|   |
|   [] (escolha)
|   |
|   +-- Visualizar resultado da análise (interativa)
|   +-- Pressionar botão de compartilhar (interativa)
|
+-- Selecionar canal de compartilhamento (abstrata)
|   |
|   [] (escolha)
|   |
|   +-- Compartilhar em rede social (abstrata)
|   |   |
|   |   [] (escolha)
|   |   |
|   |   +-- Selecionar rede social visual (interativa)
|   |   |   (Instagram, Facebook, X)
|   |   |
|   |   +-- Selecionar aplicativo de mensagem (interativa)
|   |       (WhatsApp, Telegram)
|   |
|   +-- Compartilhar via email (abstrata)
|       |
|       +-- Selecionar plataforma de email (interativa)
|           (Outlook, Gmail)
|
+-- Configurar canal de compartilhamento (abstrata)
|   |
|   [] (escolha baseada no canal)
|   |
|   +-- Configurar envio para redes sociais (abstrata)
|   |   |
|   |   [>> (ativação sequencial)
|   |   |
|   |   +-- Inserir link gerado (interativa)
|   |   +-- Adicionar comentário opcional (interativa)
|   |
|   +-- Configurar envio para mensageiros (abstrata)
|   |   |
|   |   [>> (ativação sequencial)
|   |   |
|   |   +-- Selecionar destinatário (abstrata)
|   |   |   |
|   |   |   [] (escolha)
|   |   |   |
|   |   |   +-- Selecionar contato ou grupo (interativa)
|   |   |   +-- Adicionar texto opcional (interativa)
|   |   |
|   |   +-- Inserir link gerado (interativa)
|   |
|   +-- Configurar envio para email (abstrata)
|       |
|       [>> (ativação sequencial)
|       |
|       +-- Inserir destinatário(s) (interativa)
|       +-- Inserir link da plataforma (interativa)
|       +-- Adicionar mensagem ao email (interativa)
|
+-- Enviar compartilhamento (interativa)
```

---
## **3) CTT (ConcurTaskTrees)**
**Funcionalidade: Apresentar informações sobre deepfakes.** <br>
**(Autor: Yuri)**

### Descrição da Funcionalidade:
Apresenta o processo de aprendizado sobre deepfakes, guiando o usuário desde o acesso à página educativa até a compreensão do conteúdo e do vídeo explicativo.

### Diagrama CTT:

```
Aprender mais sobre deepfakes
|
[>> (ativação sequencial)
|
+-- Acessar a página educativa (abstrata)
|   |
|   [>> (ativação sequencial)
|   |
|   +-- Localizar menu principal (usuário)
|   +-- Selecionar botão "Educação" (interativa)
|   +-- Aguardar carregamento (sistema)
|
+-- Ler conteúdo introdutório (abstrata)
|   |
|   |=| (tarefas independentes - ordem livre)
|   |
|   +-- Ler definição de deepfake (usuário)
|   +-- Visualizar exemplos ilustrativos (usuário)
|   +-- Compreender diferença entre imagens reais e manipuladas (usuário)
|   +-- Ler sobre impacto social dos deepfakes (usuário)
|
+-- Assistir ao vídeo explicativo sobre deepfakes (abstrata)
    |
    [>> (ativação sequencial)
    |
    +-- Localizar vídeo explicativo (usuário)
    +-- Iniciar reprodução (interativa)
    +-- Assistir conteúdo do vídeo (usuário)
    ||| (concorrente com)
    +-- Reproduzir vídeo (sistema)
```

---

### Legenda CTT:
- **[>>]** = Ativação sequencial (T1 >> T2)
- **[]** = Escolha/alternativa (T1 [] T2)
- **|||** = Tarefas concorrentes (T1 ||| T2)
- **|=|** = Tarefas independentes (T1 |=| T2)
- **[>]** = Desativação (T1 [> T2)
- **|>** = Suspensão/retomada (T1 |> T2)

### Tipos de Tarefas:

- **(usuário)** = Tarefa do usuário (fora do sistema)
- **(sistema)** = Tarefa do sistema
- **(interativa)** = Tarefa interativa (diálogo usuário-sistema)
- **(abstrata)** = Tarefa abstrata (composição de tarefas)

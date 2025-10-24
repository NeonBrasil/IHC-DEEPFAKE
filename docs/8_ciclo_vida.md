## **ATIVIDADE 8 - CICLO DE VIDA DE ENGENHARIA DE USABILIDADE**

## **1. Características da Plataforma**

| Característica | Descrição |
| :---- | :---- |
| **Descrição do Software** | Plataforma web para detectar deepfakes em fotos. O usuário faz upload de uma imagem e o sistema analisa se ela foi manipulada ou não. A plataforma tem uma interface simples feita em React, um backend em Python para processar as requisições, modelos de IA treinados para identificar deepfakes, e um banco de dados para guardar o histórico de análises. |
| **Descrição do Hardware** | Funciona em qualquer navegador moderno (Chrome, Firefox, Safari) tanto no celular quanto no computador. Precisa de internet para enviar as fotos e receber os resultados. O processamento pesado acontece em servidores na nuvem com GPU para rodar os modelos de IA mais rápido. |
| **LISTA DE Capacidades da Plataforma** | → **Detecção automática de deepfakes** - Usa algoritmos de inteligência artificial para identificar se uma foto foi manipulada, analisando coisas como inconsistências no rosto e marcas de edição.<br>→ **Interface responsiva** - Funciona bem tanto no celular quanto no computador, se adaptando ao tamanho da tela.<br>→ **Upload simples** - O usuário só precisa arrastar a foto ou clicar para fazer upload. O sistema mostra uma barra de progresso enquanto analisa.<br>→ **Conteúdo educativo** - Tem uma área com artigos e vídeos explicando o que são deepfakes, como funcionam e quais os riscos.<br>→ **Resultados visuais** - Mostra um relatório com a análise da foto, indicando se é real ou fake, com porcentagem de confiança e destacando áreas suspeitas. |
| **LISTA DE Restrições da Plataforma** | → **Limite de tamanho de arquivo** - Aceita apenas fotos de até 10MB nos formatos JPG e PNG. Arquivos maiores podem travar o sistema ou demorar muito para processar.<br>→ **Precisa de internet** - Sem conexão à internet não dá para usar a plataforma. Se a internet for muito lenta, o upload pode demorar bastante.<br>→ **Algoritmo não é 100% preciso** - Deepfakes muito bem feitos podem passar despercebidos. Pode acontecer de dar falso positivo (dizer que é fake quando é real) ou falso negativo.<br>→ **Privacidade** - Algumas pessoas podem ter medo de enviar fotos pessoais para um site. É preciso deixar claro como os dados são protegidos.<br>→ **Custo de servidor** - Processar muitas fotos ao mesmo tempo precisa de servidores potentes, o que custa caro. Em horários de pico pode demorar mais. |

## **2. Princípios Gerais do Projeto**

| Nome | Descrição | Link |
| :---- | :---- | :---- |
| **Descrição do Contexto** | O projeto foi feito para ajudar a combater fake news e desinformação. Ele permite que qualquer pessoa (jornalistas, professores, público em geral) consiga verificar se uma foto é real ou manipulada antes de compartilhar nas redes sociais. |  |
| **Lei Geral de Proteção de Dados (LGPD) - Lei n.º 13.709/2018** | É a lei brasileira que protege os dados pessoais das pessoas. Como o sistema lida com fotos que podem ter rostos de pessoas, é obrigatório seguir essa lei. Ela garante que os dados sejam usados de forma segura e que o usuário tenha controle sobre suas informações. | [https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| **Lei n.º 10.098/2000 - Lei da Acessibilidade** | Lei que garante que pessoas com deficiência possam usar produtos e serviços. É importante para o projeto porque a plataforma precisa ser acessível para todos, incluindo quem usa leitor de tela, tem dificuldade visual ou usa apenas o teclado para navegar. | [https://www.planalto.gov.br/ccivil_03/leis/l10098.htm](https://www.planalto.gov.br/ccivil_03/leis/l10098.htm) |
| **ABNT NBR ISO 9241 - Ergonomia da interação humano-sistema** | Norma internacional que dá diretrizes para criar sistemas fáceis de usar. A parte 11 fala especificamente sobre usabilidade (se o sistema é eficaz, eficiente e satisfatório). Seguir essa norma ajuda a garantir que a interface seja intuitiva e atenda o que os usuários precisam. | [https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf](https://www.inf.ufsc.br/~edla.ramos/ine5624/_Walter/Normas/Parte%2011/iso9241-11F2.pdf) |

## **3. Metas de Usabilidade**

### **3.1 Qualitativo**

O sistema precisa ser fácil de usar mesmo para quem não entende muito de tecnologia. Qualquer pessoa deve conseguir fazer upload de uma foto e entender o resultado da análise rapidamente. A plataforma tem que passar confiança, mostrando de forma clara como funciona a análise e como os dados são protegidos (seguindo a LGPD). Além de detectar deepfakes, o sistema deve educar os usuários sobre o que são essas tecnologias e por que elas são perigosas, ajudando as pessoas a ficarem mais atentas.

### **3.2 Quantitativo**

| Metas | Porcentagem | Justificativa |
| :---- | :---- | :---- |
| **Facilidade de aprendizado** | 25% | O usuário tem que conseguir usar o sistema sem ajuda. O processo é simples: faz upload da foto, espera a análise e vê o resultado. Pode ter uns tooltips explicando cada parte. |
| **Eficiência de uso** | 20% | A análise precisa ser rápida. O ideal é que uma foto seja analisada em menos de 30 segundos. Tem que mostrar uma barra de progresso para o usuário saber que está funcionando. |
| **Confiabilidade dos resultados** | 25% | O algoritmo precisa ser preciso, com pelo menos 85% de acerto. É importante mostrar a porcentagem de confiança e avisar que não é 100% perfeito. Se não for confiável, ninguém vai usar. |
| **Satisfação do usuário** | 15% | A interface tem que ser bonita e fácil de entender. O resultado deve ser claro, mostrando se é fake ou real, e se possível destacando as partes suspeitas da foto. Linguagem simples é essencial. |
| **Prevenção e recuperação de erros** | 10% | O sistema deve avisar antes se o arquivo está errado (formato não suportado, muito pesado, etc). As mensagens de erro precisam ser claras e dizer o que fazer para corrigir. |
| **Acessibilidade** | 5% | Seguir as diretrizes WCAG 2.1 para que pessoas com deficiência consigam usar. Cores com bom contraste, funcionar com leitor de tela, poder navegar só pelo teclado. |
| **Total** | **100%** |  |

# Caderno Temático: Fundamentos de Mecânica Clássica

## 🎯 Contexto e Objetivos
Este caderno temático foi desenvolvido como um ambiente de estudo focado nos pilares da **Física Geral**, com ênfase em **Mecânica Clássica**. O objetivo principal deste material é consolidar o entendimento sobre como os corpos se movem, as forças que influenciam esses movimentos e as leis fundamentais que regem o universo macroscópico.

Através do uso da inteligência artificial (via NotebookLM) aliada a fontes acadêmicas de prestígio, busca-se construir uma base sólida para a resolução de problemas conceituais e matemáticos, preparando o estudante tanto para exames acadêmicos quanto para a aplicação prática desses conceitos em engenharia e ciências aplicadas.

---

## 📚 Curadoria de Fontes
Para alimentar este caderno e garantir o rigor científico dos resumos e respostas, foram selecionadas as seguintes fontes abertas (textos, videoaulas e materiais de suporte):

* **Ambiente de IA:** [NotebookLM - Caderno de Mecânica Clássica](https://notebooklm.google.com/notebook/400294cf-6b90-4d16-ab6a-38f549c922e0)
* **Fonte 1 (Introdução):** [Toda Matéria - Física Geral](https://www.todamateria.com.br/fisica/)
* **Fonte 2 (Aprofundamento):** [Toda Matéria - Mecânica](https://www.todamateria.com.br/fisica/mecanica/)
* **Fonte 3 (Internacional/Avançado):** [MIT OpenCourseWare - Classical Mechanics (Fall 2016)](https://ocw.mit.edu/courses/8-01sc-classical-mechanics-fall-2016/)
* **Fonte 4 (Nacional/Acadêmico):** [eAulas USP - Curso de Física / Mecânica](https://eaulas.usp.br/portal/course.action;jsessionid=8CAB3DB7305623BAE5FE88A23256459A?course=17173)

---

## 🛠️ Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documentamos o processo de refinamento das perguntas feitas à IA para extrair as respostas mais precisas a partir das fontes fornecidas.

### Teste de Prompt 1: Conceitual
* **Prompt Inicial:** *"Me explica as leis de Newton."*
* **Resultado:** A IA trouxe uma resposta genérica e muito escolar, focando apenas nos enunciados diretos.
* **Refinamento (Prompt Estratégico):** *"Com base nos cursos do MIT e da USP fornecidos nas fontes, explique a diferença prática entre a Primeira e a Segunda Lei de Newton, detalhando o conceito de referencial inercial. Inclua um exemplo cotidiano para cada uma."*
* **A "Cicatriz" / Resposta Extraída:** A IA conseguiu isolar que a Primeira Lei define as condições para um referencial ser inercial, enquanto a Segunda rege a dinâmica sob forças resultantes não nulas.

### Teste de Prompt 2: Resolução de Problemas e Fórmulas
* **Prompt Inicial:** *"Como calcula a energia mecânica?"*
* **Dificuldade Encontrada (Cicatriz):** A IA misturou conceitos de termodinâmica e relatividade na primeira tentativa, saindo do escopo de Mecânica Clássica elementar.
* **Solução (Troubleshooting):** Foi necessário delimitar o escopo explicitamente no prompt e exigir a separação matemática.
* **Refinamento:** *"Restringindo-se estritamente ao escopo de Mecânica Clássica (fontes Toda Matéria e USP), demonstre como a variação da Energia Cinética se relaciona com o Trabalho de uma força resultante. Apresente as fórmulas textualmente."*

---

## 📖 Miniguia de Estudo

### 1. Resumos Estruturados do Assunto

#### **A. Cinemática: A Descrição do Movimento**
* **Conceito-Chave:** Estuda o movimento dos corpos sem se preocupar com as causas (forças).
* **Movimento Uniforme (MU):** Velocidade constante, aceleração nula. A posição varia de forma linear com o tempo ($S = S_0 + vt$).
* **Movimento Uniformemente Variado (MUV):** Aceleração constante. A velocidade varia linearmente e a posição de forma quadrática ($S = S_0 + v_0t + \frac{at^2}{2}$). A equação de Torricelli ($v^2 = v_0^2 + 2a\Delta S$) é fundamental quando o tempo não é fornecido.

#### **B. Dinâmica: As Causas do Movimento**
* **1ª Lei de Newton (Inércia):** Um corpo tende a manter seu estado de repouso ou de movimento retilíneo uniforme, a menos que uma força externa atue sobre ele.
* **2ª Lei de Newton (Princípio Fundamental):** A força resultante aplicada a um corpo é igual ao produto de sua massa pela aceleração adquirida ($\vec{F} = m\vec{a}$).
* **3ª Lei de Newton (Ação e Reação):** Para toda força de ação, existe uma força de reação de mesma intensidade, mesma direção e sentido oposto, atuando em corpos diferentes.

#### **C. Energia e Trabalho**
* **Trabalho ($W$):** Energia transferida por uma força ao longo de um deslocamento ($W = F \cdot d \cdot \cos\theta$).
* **Energia Cinética ($E_c$):** Energia associada ao movimento ($\frac{mv^2}{2}$).
* **Energia Potencial Gravitacional ($E_p$):** Energia armazenada devido à posição em um campo gravitacional ($mgh$).
* **Conservação da Energia Mecânica:** Em sistemas conservativos (sem atrito), a soma da energia cinética e potencial permanece constante ($E_{m1} = E_{m2}$).

---

### 2. Glossário de Conceitos Aprendidos

* **Referencial Inercial:** Sistema de coordenadas em que as leis de Newton são válidas sem a necessidade de introduzir forças fictícias (forças de inércia).
* **Massa:** Medida quantitativa da inércia de um corpo; a resistência que o corpo oferece a qualquer variação em seu estado de movimento.
* **Força Resultante:** A soma vetorial de todas as forças individuais que atuam sobre um mesmo objeto.
* **Sistema Conservativo:** Sistema físico onde atuam apenas forças conservativas (como a gravidade), permitindo que a energia mecânica total se conserve ao longo do tempo.
* **Vetor:** Grandeza física que possui módulo (valor numérico), direção (ex: horizontal) e sentido (ex: para a direita), essencial para descrever posição, velocidade e força.

---

### 3. Banco de Prompts Reutilizáveis (Para Revisões Futuras)

Copie e cole estes prompts no seu NotebookLM para realizar revisões rápidas ou aprofundar temas específicos:

1.  **Prompt para Quiz Conceitual:**
    > *"Com base no material de Mecânica Clássica, gere 3 perguntas de múltipla escolha sobre as Leis de Newton aplicadas a planos inclinados com atrito. Após eu responder, me dê o feedback detalhado de cada alternativa."*
2.  **Prompt para Analogias Simples:**
    > *"Explique a diferença entre Energia Cinética e Energia Potencial usando a analogia de uma montanha-russa, mantendo a explicação científica rigorosa, mas fácil de visualizar."*
3.  **Prompt para Resumo de Fórmulas:**
    > *"Crie uma tabela listando as principais equações de Cinemática (MU e MUV) e Dinâmica presentes nas fontes da USP e do MIT, indicando o significado de cada variável e a unidade de medida no Sistema Internacional (SI)."*

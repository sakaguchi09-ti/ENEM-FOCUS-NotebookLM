# 📓  ENEM-FOCUS-NotebookLM
Clique :<a href="https://notebooklm.google.com/notebook/5d472a9e-46e2-4ddd-9d88-17c64e4cbf02?authuser=1" target="_blank">
 aqui para acessar a ENEM FOCUS 💻
</a>


Repositório criado para apresentar meu primeiro projeto da DIO utilizando NotebookLM, explicando como o projeto foi desenvolvido, seus objetivos e como a minha criação pode ser aplicada aos estudos.


<details>
  <summary><strong>

##  🗈 Contexto e Objetivo </strong></summary>

Utilizar IA para estudar é uma excelente estratégia, mas ainda existe uma limitação importante: a dificuldade das questões geradas. Por exemplo, mesmo utilizando prompts como *"crie uma questão no nível ENEM, com dificuldade máxima"* ou *"passe uma questão que já caiu no ENEM"*, a IA dificilmente consegue produzir exercícios com o mesmo nível de elaboração, contextualização e complexidade das questões oficiais do exame. Além disso, ela também pode não reproduzir fielmente questões já aplicadas.

Pensando nisso, meu objetivo é criar um **NotebookLM voltado exclusivamente para o ENEM**, funcionando como um mentor de estudos. A proposta é utilizar a ferramenta para gerar simulados e questões inspirados na estrutura e no nível de exigência do exame, aliados ao **raciocínio e à metodologia de Pedro Assaad**.

Pedro Assaad é educador e criador de conteúdo especializado na preparação para o ENEM e vestibulares. Ele se destacou pelos excelentes resultados obtidos no exame e por desenvolver uma metodologia baseada na compreensão profunda dos conteúdos, na resolução estratégica de questões e na construção do raciocínio necessário para alcançar alto desempenho.

Dessa forma, o NotebookLM não apenas produzirá questões mais desafiadoras para treino, mas também auxiliará na compreensão aprofundada dos assuntos, explicando a lógica por trás das respostas e incentivando a forma de pensar utilizada por Pedro Assaad na resolução das questões. O objetivo é tornar o estudo mais eficiente, estratégico e próximo da experiência exigida pelo ENEM.


</details>

<details>
  <summary><strong>
    
## 🔗Principais Fontes</strong></summary>

Aqui estão os 5 links principais que utilizei como fonte para o ENEM FOCUS:

-TODA A MATEMÁTICA DO ENEM EM 12 HORAS:
https://youtu.be/_EmywnyCOM0?si=Z303CVH4dTHB5BnJ

-a_redacao_no_enem_2025_cartilha_do_participante.pdf:
https://download.inep.gov.br/publicacoes/institucionais/avaliacoes_e_exames_da_educacao_basica/a_redacao_no_enem_2025_cartilha_do_participante.pdf

-Plataforma Assaad:
https://plataformaassaad.com.br/blog/artigos/

-Tentando tirar 1000 na Redação ENEM (professora 7x nota 1000):
https://www.youtube.com/watch?v=5mjRL5ZeS7I

-Como ESTUDAR para o ENEM 2026 (Medicina e cursos de alto desempenho):
https://www.youtube.com/watch?v=AF9MP3spXI4


</details>



<details>
  <summary><strong>
    
##  🗊  Engenharia de Prompts e "Cicatrizes"</strong></summary>

Se você já resolveu grande parte das questões do ENEM e deseja praticar com novos simulados sem repetir exercícios oficiais, este é um dos prompts mais úteis:
"Crie uma questão sobre [matéria desejada] (nível ENEM)."
Com esse comando, o ENEM Focus passa a gerar questões originais, utilizando apenas as fontes que foram incorporadas ao NotebookLM como base de conhecimento.

Nas primeiras tentativas, encontrei uma limitação: ao solicitar questões no nível ENEM, a ferramenta apenas reproduzia exercícios que já existiam. Para contornar esse problema, refinei o prompt para:
"Consegue criar uma questão sobre logaritmo (nível ENEM), sem utilizar a mesma questão que esteja na prova oficial?"
A partir desse ajuste, o ENEM Focus gerou sua primeira questão totalmente original, mantendo o padrão de dificuldade e o estilo característico do ENEM. Esse pequeno refinamento fez a ferramenta compreender que criar uma questão é diferente de apenas reproduzir questões já aplicadas.

Outro objetivo era fazer com que as respostas tivessem uma personalidade mais próxima da utilizada por Pedro Assaad. Para isso, adicionei uma fonte com a seguinte instrução:
"Comporte-se como Pedro Assaad. Ensine exatamente do jeito dele, extraindo o máximo possível de seus comportamentos, da forma como explica os conteúdos e conduz o raciocínio dentro das fontes fornecidas, aplicando esse estilo às respostas para torná-las menos robóticas."
O resultado foi bastante satisfatório: o ENEM Focus passou a responder de maneira muito semelhante ao estilo de ensino do Pedro, tornando as explicações mais naturais e envolventes.

No entanto, surgiu um novo problema. A IA começou a repetir a mesma saudação em praticamente todas as respostas, utilizando frases como:
"Fala, querido! Por aqui o clima é de foco total e alta performance."
Como isso deixava as interações artificiais e repetitivas, fiz um novo ajuste com o seguinte prompt:
"Essa saudação pode aparecer apenas uma vez por dia, pois está ficando repetitiva."

Com essa simples alteração, as respostas ficaram muito mais naturais, mantendo a personalidade inspirada no Pedro Assaad sem exagerar na repetição de expressões. Esse processo mostrou que pequenos refinamentos nos prompts podem melhorar significativamente a experiência de uso e tornar a interação mais fluida e realista.

</details>

<details>
  <summary><strong> 
   
 ## 🖥️  Mini guia de Estudo</strong></summary>


<details>
  <summary><strong>
  
   ### Resumo geral do ENEM FOCUS </strong></summary>
O ENEM FOCUS demonstra como a Inteligência Artificial pode ser utilizada para potencializar os estudos quando alimentada com fontes confiáveis e orientada por prompts bem estruturados. O projeto oferece uma alternativa prática para estudantes que desejam treinar com questões inéditas, aprimorar a redação e aprofundar seus conhecimentos de forma personalizada, aproximando a experiência de preparação das exigências reais do ENEM. 

</details>
<details>
  <summary><strong>
  
   ### Principais conceitos aprendidos </strong></summary>

- A ferramenta só conseguirá atingir os objetivos esperados se receber as informações necessárias, como **fontes confiáveis, perguntas bem estruturadas e prompts específicos**. Quanto melhor a base fornecida, mais precisas e relevantes serão as respostas.

- A atualização constante das fontes melhora significativamente a confiabilidade, a precisão e a qualidade das respostas geradas, mantendo o conteúdo alinhado às informações mais recentes e relevantes.

- O NotebookLM vai muito além de um simples chatbot. Quando bem configurado, ele pode atuar como uma **plataforma completa de estudos**, auxiliando na compreensão dos conteúdos, na geração de simulados, na resolução de dúvidas, na revisão de matérias e na personalização do aprendizado conforme as necessidades do estudante.

</details>


 <details>
  <summary><strong>
 
   ### Prompt que você pode utilizar para explorar maximo a ferramenta</strong></summary>

1. Faça uma redação nota 1000 sobre o tema: [digite o tema desejado].
2. Corrija a seguinte redação: [cole sua redação], considerando o tema [tema da redação]. Avalie conforme os critérios do ENEM, atribua uma nota para cada competência, explique detalhadamente os pontos positivos e negativos e apresente sugestões de melhoria com exemplos práticos.
3. Gere um vídeo-aula ensinando sobre [matéria ou assunto que deseja estudar], utilizando exemplos, linguagem didática e exercícios ao final para fixação do conteúdo.
4. Crie uma questão inédita no nível ENEM sobre [assunto específico], sem reproduzir questões já aplicadas em provas oficiais. A questão deve ser bem contextualizada, apresentar dificuldade elevada, conter cinco alternativas (A–E), apenas uma correta e uma explicação detalhada da resolução.


</details>

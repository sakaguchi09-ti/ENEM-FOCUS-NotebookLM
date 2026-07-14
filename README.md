# 📓  ENEM-FOCUS-NotebookLM
Clique aqui para acessar a:<a href="https://notebooklm.google.com/notebook/5d472a9e-46e2-4ddd-9d88-17c64e4cbf02?authuser=1" target="_blank">
 ENEM FOCUS 💻
</a>


Repositório criado para apresentar meu primeiro projeto da DIO utilizando o NotebookLM, explicando como o projeto foi desenvolvido, seus objetivos e como a minha criação pode ser aplicada aos estudos.


<details>
  <summary><strong>

##  🗈 Contexto e Objetivo </strong></summary>

Utilizar IA para estudar é sempre bom, mas é complicado praticar questões com a mesma dificuldade do ENEM. Por exemplo, mandei prompt dizendo "crie uma questão no nível ENEM, com dificuldade máxima" ou " passa uma questão que caiu no ENEM", IA não vai te dar exercícios realmente elaboradas igual a do ENEM ou mesmo passar questões que já caíram no ENEM. Meu objetivo é criar NotebookLM voltada para o ENEM, com mentor "auxiliando" e fazer com que ferramenta crie "simulados" com ajuda do "Raciocínio do Pedro Assaad" (Pedro Assaad é um educador e criador de conteúdo voltado à preparação para o ENEM e vestibulares, ele conquistou destaque ao obter resultados expressivos no ENEM e desenvolver uma metodologia focada na compreensão dos conteúdos, resolução estratégica de questões e alto desempenho dos alunos). Deixando mais prático tanto no caso do nível elevado das questões para poder treinar e tanto na compreenssão mais aprofundada com ajuda do Pedro Assaad.


</details>

<details>
  <summary><strong>
    
## 🔗Principais Fontes</strong></summary>

Aqui estão os 5 links principais que eu utilizei como fonte para ENEM FOCUS:

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


Se você fez inúmeras exercícios do ENEM e queira fazer mais simulados sem repetir com as mesmas questões, esse é o prompt ideal: "crie uma questão sobre [matéria que você queira responder](nível Enem)", ele vai te dar questão totalmente original dele, utilizando fontes que eu embutir.
Tive dificuldade nas primeiras tentativas usando esse tipo de prompt, pois ENEM Focus não criava, ele só passava questões já existentes. Mas com prompt: "consegue criar uma questão sobre logaritmo( nivel enem), sem utilizar mesma questão que esteja na prova oficial". ENEM Focus, produziu a sua primeira questão original(Nível ENEM). Assim ele capitou a informação que para criar uma questão não é mesma coisa de repassar questões existentes no ENEM.

No primeiro momento, queria deixar com personalidade do Pedro nas respostas geradas, criei fonte :"Comporte-se como Pedro Assaad, ensine extamente do jeito dele (extrai o máximo de comportamentos, maneira como ele ensina e age, dentro das fontes, e aplique o jeito dele nas respostas) deixando menos robótico as respostas."
, comportamento dele ficou "igual" a do Pedro, porém, as respostas ficaram muito repetitivas. Por exemplo, ele sempre mandava saudação "Fala, querido! Por aqui o clima é de foco total e alta performance. ", como era meio redundante, mandei prompt: " a saudação [...], pode mandar uma vez por dia, pois esta sendo repetitivo" , para deicar mais normal a reação dele nas respostas.


</details>

<details>
  <summary><strong> 
   
 ## 🖥️  Mini guia de Estudo</strong></summary>


A parte da redação tambem é importante, caso queira pedir para corrigir sua redação é so usar prompt como: "corrigi para mim essa redação [redação que você criou], seguindo o tema [tema que você se baseou]".Ou até mesmo pedir para ele criar digitando esse prompt:"faça uma redação seguindo o tema [TEMA]".E quando quiser a explicação como ENEM Focus elaborou a redação e só usar "explique cada parágrafo detalhando quais foram as teses e os argumentos".


</details>

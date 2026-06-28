> Miniguia de Estudos: Curiosidades da Copa do Mundo com NotebookLM <

Este repositório contém o projeto prático do desafio de IA e curadoria de conhecimento da DIO, explorando o uso do Google NotebookLM como uma ferramenta de aprendizagem ativa.


Contexto e Objetivos

A escolha do tema "Copas do Mundo" se deu por dois motivos estratégicos. Primeiro, pelo timing perfeito, já que estamos vivenciando o período da Copa do Mundo de 2026. Segundo, por ser um domínio no qual possuo grande conhecimento prévio, o que me permite avaliar com precisão a qualidade, as alucinações e os retornos da Inteligência Artificial.

Como este é meu primeiro contato prático com a plataforma e com a área de programação estruturada com IA, optei por uma abordagem de base: fazer o simples com excelência. O objetivo não foi forçar a ferramenta ao limite logo de cara, mas sim entender o reconhecimento do ambiente, o comportamento da IA com diferentes formatos de arquivo e validar o fluxo de trabalho antes de avançar para usos mais complexos. 



Objetivos de Estudo:
1. Dominar os fundamentos do NotebookLM e a organização de fontes mistas (vídeo, texto e PDF).
2. Validar as respostas usando meu conhecimento histórico sobre Copa do Mundo.
3. Consolidar uma base de conhecimento confiável, que possa até mesmo servir no futuro como fonte de dados para criar perguntas de Quiz, estatísticas ou desafios esportivos.

---

Curadoria de Fontes

Para garantir respostas mais precisas, alimentei o NotebookLM com fontes variadas e de alta credibilidade:

1. PDF Oficial: documento de estatísticas e resumo histórico da FIFA.
2. Artigos da Wikipédia (Múltiplos): páginas principais de cada edição da Copa do Mundo. (Nota: Para otimizar o tempo de busca das URLs, utilizei o ChatGPT para gerar a lista exata de todos os links principais, que foram posteriormente inseridos no NotebookLM).
3. Vídeo (YouTube): "A história da Copa, da origem até 2018" - Canal Euro Fut.
4. Vídeo (YouTube): "O Brasil em todas as Copas do Mundo" - Canal Euro Fut.

---

Engenharia de Prompts e Soluções de Problemas

Ao longo dos testes, documentei o processo de refinamento das perguntas para entender como a IA cruza os dados fornecidos.

Teste 1: O Desafio dos Dados Faltantes
Prompt: "Crie uma lista dos artilheiros de cada edição da Copa do Mundo, mostrando quantidade de gols e quantidade de jogos que cada um atuou."

Problema: Na primeira tentativa, notei que a IA não conseguiu entregar a informação completa. O PDF e os vídeos originais não continham a relação exata de jogos disputados por cada artilheiro. Ainda não tinha os artigos detalhados de cada Copa pelo Wikipédia, apenas uma página central de todas as Copas do Wikipédia.

A Solução: Percebi que a IA precisava de mais dados. Fui ao ChatGPT, pedi a lista de URLs da Wikipédia para cada edição da Copa e fiz um novo upload no NotebookLM expandindo a base de dados.

Resultado: Após a inclusão das novas fontes, repeti o mesmo prompt e a IA retornou com sucesso a lista completa, cruzando a edição, o artilheiro, os gols e os jogos atuados.


Teste 2: Mudança de Contextualização
Prompt: "Aja como um historiador de futebol e liste 5 curiosidades sobre a Copa de 1970, detalhando o contexto da época."

Análise: Teste focado em mudar o tom da resposta (para algo mais professor de história). A IA performou muito bem, extraindo com precisão as cinco curiosidades mais relevantes daquela edição específica e acertando o contexto cultural de 1970.


Teste 3: Capacidade de Síntese
Prompt: "Faça um resumo em tópicos sobre todas as Copas vencidas pela Argentina."

Análise: Teste focado em agregação. A IA conseguiu filtrar todo o material, identificar os anos corretos (1978, 1986, 2022) e resumir as campanhas de forma pontual e precisa.

---

Miniguia de Estudo: História das Copas

Abaixo está o material entregue por um dos prompts, consolidado a partir das interações com o NotebookLM.

Resumo Estruturado do prompt em relação a seleção argentina
Copa do Mundo de 1978 (Argentina)

    Sede e Contexto: O torneio foi realizado na própria Argentina, sob o contexto político de uma ditadura militar.
    A Final: A seleção argentina venceu os Países Baixos por 3 a 1 na prorrogação, após empate em 1 a 1 no tempo normal.
    Destaque: Mario Kempes foi o grande nome da conquista, terminando como o artilheiro do torneio (6 gols) e eleito o melhor jogador da competição.
    Caminho Polêmico: A classificação para a final foi marcada pela goleada de 6 a 0 sobre o Peru, resultado necessário para superar o Brasil no saldo de gols, o que gerou diversas suspeitas de suborno e interferência política na época.

Copa do Mundo de 1986 (México)

    Sede: Realizada no México, que assumiu a organização após a desistência da Colômbia.
    A Final: A Argentina sagrou-se bicampeã ao derrotar a Alemanha Ocidental por 3 a 2 em uma final emocionante.
    A "Era Maradona": Diego Maradona teve uma atuação histórica, sendo eleito o melhor jogador do torneio. Nas quartas de final contra a Inglaterra, ele marcou dois dos gols mais famosos da história: um com a mão ("La Mano de Dios") e outro driblando metade do time adversário ("O Gol do Século").
    Estatísticas: Maradona encerrou a competição com 5 gols e 5 assistências, recorde de dribles (53) e chances criadas (27) em uma única edição.

Copa do Mundo de 2022 (Catar)

    Sede: Primeira edição realizada no Oriente Médio, no Catar.
    A Final: Considerada uma das melhores finais de todos os tempos, a Argentina empatou com a França em 3 a 3 (após prorrogação) e venceu na disputa de pênaltis por 4 a 2.
    Consagração de Messi: Lionel Messi liderou a equipe, tornando-se o único jogador a vencer a Bola de Ouro (melhor da Copa) duas vezes e o primeiro a marcar gols em todas as fases eliminatórias de uma mesma edição.
    Outros Prêmios: Além de Messi, Emiliano Martínez foi eleito o melhor goleiro e Enzo Fernández o melhor jogador jovem. A conquista encerrou um jejum de 36 anos da Argentina sem títulos mundiais.






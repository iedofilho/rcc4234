# Fundamentos de Programação para Dados em Ciências Sociais (RCC4234)

---

## Responsável

Rafael de Freitas Souza

* [Lattes;](https://lattes.cnpq.br/7162963252500422)
* [Google Scholar;](https://scholar.google.com.br/citations?user=Rs9_QbYAAAAJ&hl=pt-BR)
* [Research Gate.](https://www.researchgate.net/profile/Rafael-De-Freitas-Souza-2?ev=hdr_xprf)

---

## Boas-Vindas

Prezadas e prezados,

Sejam muito bem-vindos à disciplina **Fundamentos de Programação para Dados em Ciências Sociais (RCC4234)**, que terá início no dia 05/03/2026 e será desenvolvida ao longo de 8 semanas.

Esta é a primeira vez que a disciplina é oferecida no departamento. **O objetivo central é fomentar entre vocês uma cultura de uso de programação aplicada à pesquisa em Ciências Sociais Aplicadas, habilitando-os a incorporar essas ferramentas de forma autônoma e consistente em suas dissertações, teses e demais produções acadêmicas.**

Cursos de programação, em geral, costumam cair em um de três extremos: tornam-se incompreensíveis, entediantes ou excessivamente tensos por conta da avaliação. Nosso esforço será evitar qualquer um desses cenários.

**A proposta é estruturar a disciplina como uma grande oficina de trabalho.** Teremos momentos expositivos, mas o foco principal será a prática. Vocês trabalharão bastante em sala, trocarão códigos, discutirão soluções e aprenderão colaborativamente. Programação se aprende fazendo, errando, ajustando e tentando novamente.

A avaliação levará em conta não apenas a entrega de tarefas, mas o progresso individual ao longo do curso. Mais importante do que acertar tudo é demonstrar desenvolvimento técnico, consistência e dedicação.

**Se esta é sua primeira experiência com programação, venham com tranquilidade e mente aberta. Não é necessário conhecimento prévio.** Se você já programou antes ou já utilizou R, sua postura colaborativa será essencial para elevar o nível coletivo da turma.

---

## Sobre o livro base, atividades e dedicação esperada

Utilizaremos como referência principal o livro *R for Data Science*, de Garrett Grolemund e Hadley Wickham, disponível gratuitamente online. Ao longo das semanas, complementaremos com trechos selecionados de outras obras relevantes, especialmente nas áreas de programação avançada, mineração de texto e eficiência computacional, tais como:

- Grolemund, Garrett. Hands-On Programming with R;
- Silge, Julia e Robinson, David. Text Mining with R: A Tidy Approach. Disponível em https://www.tidytextmining.com/;
- Wichkam, Hadley. Advanced R. Disponível em http://adv-r.had.co.nz/;
- Gillespie, Colin e Lovelace, Robin. Efficient R programming. Disponível em: https://csgillespie.github.io/efficientR/.

Para cada tópico trabalhado haverá tutoriais, exercícios práticos e leituras obrigatórias. A expectativa é que a maior parte dos exercícios seja realizada em sala, mas será necessário dedicar tempo adicional fora dela para a consolidação do aprendizado.

Além das tarefas avaliativas, vocês desenvolverão um projeto aplicado ao longo do curso, utilizando ao menos uma das técnicas estudadas. O projeto deverá ser entregue em formato reprodutível, com código organizado e documentado.

Programação exige prática regular. Reservem tempo semanal para exercitar, revisar e explorar além do mínimo exigido.

---

## Sobre o repositório do curso e programa

Todos os materiais e informações sobre o curso estarão disponíveis no repositório GitHub criado para a disciplina: https://github.com/fsrafael25/rcc4234

Peço que acompanhem o repositório ao longo do semestre. Temos uma turma de tamanho relevante (15 participantes) e proponho evitar trocas de e-mails desnecessárias. Deixarei tudo (de tutoriais e leituras a dúvidas recorrentes) bem documentado no repositório, para que ninguém fique perdido.

Na primeira aula conversaremos sobre os tópicos do curso. Faremos a definição final em conjunto, a partir da proposta inicial que levarei. Após essa aula, fecharemos o programa e o calendário definitivo.

Sobre a postura esperada

Esta disciplina não é sobre decorar comandos. É sobre ganhar autonomia técnica como pesquisador.

Meu compromisso é oferecer estrutura, orientação e um ambiente intelectualmente seguro para aprendizado. O compromisso de vocês é dedicar tempo, praticar e colaborar.

---

## Proposta de roteiros de aula, calendário e tutoriais

* **Aula 1: 05/03/2026 - Introdução ao Curso e Fundamentos do R**
  - Apresentação da disciplina e objetivos;
  - Estrutura do R e RStudio;
  - Objetos, vetores, tipos de dados;
  - Operadores básicos;
  - Primeiros *scripts*.
  
Leituras recomendadas: Hands-On Programming with R (capítulos de 1 a 5); ou R for Data Science (capítulos 8, 12, 13, 14, 16).

<br>

* **Aula 2: 12/03/2026 - Estruturas de Dados e Manipulação**

  - *Data frames* e *tibbles*;
  - Importação de dados (CSV, Excel, Stata, SPSS, etc.);
  - Manipulação básica;
  - Indexação e subconjuntos;
  - Introdução ao fluxo de dados.

Leituras recomendadas: Hands-On Programming with R (capítulos de 6 e 7); ou R for Data Science (capítulos 7, 8 e 20).


<br>

* **Aula 3: 19/03/2026 - `tidyverse` na Prática**

  - Filosofia do `tidyverse`;
  - `dplyr`: `rename()`, `mutate()`, `filter()`, `select()`, `group_by()`, `reframe()`, etc.;
  - `tidyr`: organização e transformação
  - Pipes (`|>`);
  - Fluxos encadeados.

<br>

* **Aula 4: 26/03/2026 - Visualização de Dados com `ggplot2`**
  - Gramática dos gráficos;
  - Camadas (`geom_()`);
  - Estéticas (`aes()`);
  - Facetas (`facet_()`);
  - Customizações;
  - Boas práticas de visualização.

<br>

* **Aula 5: 09/04/2026 - Programação no R: Funções e Iteração**
  - Criação de funções;
  - Escopo;
  - Estruturas de controle;
  - Vetorialização;
  - Introdução ao `purrr`;
  - Programação funcional.

<br>

* **Aula 6: 16/04/2026 - Integração, Reprodutibilidade e Dados Externos**
  - `Quarto`;
  - Versionamento com `git`;
  - Integração com bancos SQL;
  - Conexões e queries básicas;
  - Estrutura de projetos

<br>

* **Aula 7: 23/04/2026 - Dados Não Estruturados**
  - Manipulação de *strings*;
  - Expressões regulares (regex);
  - Introdução à mineração de textos;
  - Raspagem de dados na web;
  - APIs básicas.

<br>

* **Aula 8: 30/04/2026 - Mapas e Encerramento**
  - Introdução a mapas no R;
  - Conceitos básicos de GIS;
  - Leitura e manipulação de *shapefiles*;
  - Visualização espacial;
  - Apresentação do projeto de pesquisa;
  - Encerramento e consolidação do curso.

---

# Atividades avaliativas


* **Atividade Avaliativa 1: Entrega até 02/04/2026 - Fundamentos e Manipulação de Dados**
  - R base;
  - Objetos e estruturas;
  - *Data frames*;
  - Manipulação com `dplyr`;
  - Limpeza e transformação de dados.
  
<br>

* **Atividade Avaliativa 2: Entrega até 23/04/2026 - Visualização e Comunicação Analítica**
  - Gramática dos gráficos (`ggplot2`);
  - Escolha adequada de `geoms`;
  - Customização;
  - Comunicação visual.
  
<br>

* **Atividade Avaliativa 3: Entrega até 07/05/2026 - Dados do Mundo Real**
  - Raspagem de dados;
  - Manipulação de strings;
  - Mineração textual básica;
  - Mapas;
  - Integração de múltiplas fontes.
  
<br>

* **Atividade Avaliativa 4: Entrega até 07/05/2026 - Aplicação em Pesquisa**
  - Problema de pesquisa claramente definido;
  - Descrição do conjunto de dados (origem, estrutura, limitações);
  - Procedimentos de tratamento e organização;
  - Técnicas aplicadas (manipulação, visualização, texto, mapas, etc.);
  - Resultados esperados em conjunto  com eventuais interpretações analíticas;
  - Código organizado e, necessariamente, reprodutível.
  
  <br>
  
  **ATENÇÃO:** As atividades avaliativas em grupos serão sumariamente desconsideradas. Tanto as eventuais apresentações, quanto as entregas deverão ser individuais.

---

## Referências bibliográficas

Alcoforado, L. F. (2021). *Utilizando A Linguagem R.* Alta Books. 

Borgatti, S. P.; Everett, M. G.; Johnson, J. C. e Agneessens, F. (2022). *Analyzing Social Networks Using R.* Sage Publications. 

Chang, W. (2018). *R Graphics Cookbook.* O'Reilly Media. 

Gandrud, C. (2020). *Reproducible Research with R and RStudio.* CRC Press. 

Gillespie, C. e Lovelace, R. (2021). *Efficient R programming.* O'Reilly Media.

Grolemund, G. (2014). *Hands-On Programming with R.* O'Reilly Media.

Lovelace, R.; Nowosad, J. e Muenchow, J. (2020). *Geocomputation with R.* CRC Press. 

Pebesma, E. e Bivand, R. (2023). *Spatial Data Science.* CRC Press. 

Shmueli, G.; Bruce, P. C.; Yahav, I.; Patel, N. R. e Lichtendahl, K. C. (2018). *Data Mining for Business Analytics.* Wiley. 

Silge, J. e Robinson, D. (2017). *Text Mining with R.* O'Reilly Media.

Wickham, H. (2019). *Advanced R.* CRC Press. 

Wickham, H. e Grolemund, G. (2019). *R para Data Science.* Alta Books. 

Xie, Y.; Dervieux, C. e Riederer, E. (2020). *R Markdown Cookbook.* CRC Press.
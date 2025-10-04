# Analise de Sobrevivencia Aplicada a Evasao Escolar

---

O seguinte projeto tem como objetivo aplicar técnicas de análise exploratória de dados, teste de hipóteses e análise de sobrevivência aplicado ao contexto de evasão escolar.
O seguinte estudo teve motivação devido a um TCC sobre análise de sobrevivência aplicada no estudo da evasão escolar.
Link do TCC: https://lume.ufrgs.br/bitstream/handle/10183/198131/000188649.pdf?sequence=1


"A evasão é um problema que merece ser estudado com profundidade, tanto pelo aspecto pedagógico envolvido, como econômico e social. Alguns cursos superiores da UFRGS são caracterizados como cursos onde a evasão é grande e preocupante. Diversas causas, identificadas através de pesquisas realizadas pela Universidade, são apontadas: necessidade de trabalhar, incompatibilidade de horário de trabalho e estudo, curso que não correspondeu às expectativas, etc." (Tcc, p. 42).

O projeto consiste em principalmente três notebooks, dentro da do diretório `src`, contendo algumas etapas do processo de pesquisa.
O primeiro notebook, `grc_00_sample_size` tem como objetivo estimar o tamanho da amostra necessário de ambos os grupos para a validação das hipóteses. 
O segundo notebook, `grc_01_analise_exploratoria` consiste em análise descritiva e exploratória dos dados, já adianto que é possível fazer análises mais avançadas no conjunto de dados.
O terceiro e último notebook, `grc_02_validacao_hipoteses` é onde são aplicados o teste para a validação das hipóteses e também a análise de sobrevivência.

Destaco que o segundo e o terceiro notebook podem ser muito bem mais aprofundados, é possível fazer análises exploratórias mais avançadas incluindo hipóteses de negócio e mapas mentais e também o terceiro notebook pretendo aplicar análise de sobrevivência pontual com o XGBSE, atualmente, a análise foi desenvolvido com a solução tradicional Kaplan-Mayer.

A principal hipótese a ser validada é, existe diferença nas médias das idades dos gêneros dos alunos que evadiram o curso Bacharel em Estatística da UFRGS ?

- $H_o$: As médias das idades dos dois grupos de alunos são iguais.
- $H_a$: As médias das idades dos dois grupos de alunos são diferentes.


Analisando a tabela para esses valores são necessárias 393 amostras em cada um dos grupos, ou seja, 393 alunos masculinos e femininos do curso de Bacharel em Estatística que saíram do curso, seja por motivo de transferência, abandono, entre outras.

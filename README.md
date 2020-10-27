# ALURA_imersao_dados
Notebooks criados nas imersões #quarentenadados e #imersão dados da Caelum - Alura

# Desafio #ImersãoDados - Grupo Caelum Alura
Participante: André A. Aguiar Gomes, e-mail: andreaguiar.g@gmail.com  /  GIT: https://github.com/AndrehAguiar

---



## <a name="sumario">Sumário</a>
### Análise dos dados Enem 2019

### 1.   <a href="#especial">Necessidade Especial</a>
*   Os particpantes que solicitaram atendimento especial são de quais classes das rendas familiares especificadas no formulário socioeconômico? <a href="#item_1-1">Ver</a>
*   Eles tiveram um bom desempenho? <a href="#item_1-2">Ver</a>

### 2.   <a href="#economico">Socioeconômico</a>
*   Qual o desempenho de cada classe das rendas familiares especificadas no formulário de cadastro do Enem, com e sem computador e internet na residência? <a href="#item_2-1">Ver</a>
*   Onde estão localicalidas, é proporcional ao PIB do estado? <a href="#item_2-2">Ver</a>

### 3.   <a href="#regional">Regional</a>
*   O PIB (Produto Interno Bruto) tem correlação com os resultados? <a href="#item_3-1">Ver</a>
*   A quantidade de escolas, matrículas e docentes têm impacto nos resultados? <a href="#item_3-2">Ver</a>
*   Qual o desempenho de cada estado e DF? <a href="#item_3-3">Ver</a>

### 4.   <a href="#participantes">Participantes</a>
*   Os participantes já concluiram o ensino médio? <a href="#item_4-1">Ver</a>
*   Qual o tipo de escola? <a href="#item_4-2">Ver</a>
*   Qual o tipo de ensino? <a href="#item_4-3">Ver</a>
*   O grau de escolaridade dos tem impacto nos resultados? <a href="#item_4-4">Ver</a>
*   A ocupação dos pais tem impacto nos resultados? <a href="#item_4-5">Ver</a>
*   O acesso à internet tem impacto nos resultados? <a href="#item_4-6">Ver</a>
*   Há diferença entre os resultados de cada raça/cor, como eles estão districuidos nas classe de renda familiar e qual são seus resultados? <a href="#item_4-7">Ver</a>

---

## <a name="especial">1 - Necessidades Especiais</a>

#### <a name="item_1-1"></a>1.1 - Os particpantes que solicitaram atendimento especial são de quais classes das rendas familiares especificadas no formulário socioeconômico?

!["Gráfico de Distribuição - Necessidades Especiais"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_1-1.png)

Os gráficos acima comprovam que deficiência não escolhe classe social, a diferênça nas quantidades dos indivíduos no gráfico à esquerda se dão pela proporção de participantes, se reparar no gráfico logo abaixo, os formatos são bem parecidos, as classes A e B têm muito mais participantes que as demais. Porém, ainda sim, os resultados dos deficientes de renda mais baixa são piores dentro da amostra, de acordo com as medianas das notas impressas acima de cada barra do gráfico.

<a href="#sumario">Voltar aos sumário</a>

---
#### <a name="item_1-2"></a>1.2 - Eles tiveram um bom desempenho?

!["Gráfico de Comparação - Necessidades Especiais"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_1-2.png)
Comparando os gráficos acima de uma forma geral, pode-se observar que os participantes com alguma deficiência tiveram resultados bem similares dos que não declararam nenhuma necessidade especial, de uma certa forma com o volume maior de bons resultados. Se repara nas linhas que dividem o bloco central, vai poder confirmar que a mediana é bem próxima nas 2 classes, porém o volume dos blocos acima do central são considerávelmente maiores na classe com alguma necessidade especial. No gráfico à esquerda, fica evidente que os candidatos com deficit de atenção, outras necessidades, dislexia, autismo e discalculia têm resuldados melhores que os demais, principalmente os que declararam deficit de atanção, com a mediana acima de 600.

<a href="#sumario">Voltar ao sumário</a>

---
## <a name="economico">2 - Socioeconômico</a>

#### <a name="item_2-1"></a>2.1 - Qual o desempenho de cada classe das rendas familiares especificadas no formulário de cadastro do Enem, com e sem computador e internet na residência?

!["Gráfico de Comparação - Acesso computador e internet"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_2-1.png)
Analisando os gráficos acima, fica fácil confirmar que o acesso à internet ajuda muito no estudo, dividos pela renda familiar, ainda há diferença considerável nos resultados, apesar do fato das rendas mais baixas estarem  mais equilibradas, o volume do lado esquerdo da forma(verde), premanece abaixo da metade amarela. Tendo em vista as linhas pontilhadas dos quartis, observa-se que as da metade verde estão sempre abaixo das linhas da metade amarela.
A partir de uma análise rápido do gráfico à direita, as barras crescentes formando uma escada mostram a diferença dos resultados de ter computadores disponíveis para estudo.

<a href="#sumario">Voltar ao sumário</a>

---
## <a name="item_2-2"></a>2.2 - Onde estão localicalizadas, é proporcional ao PIB do estado?

!["Gráfico de Comparação - Acesso computador e internet"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_2-2.png)
Como já era esperado, os quantidade de participantes por estado aparentemente acompanha a curva do PIB(Produto Interno Bruto), representado pela linha vermelha, mas não são em todos os casos como no Pará, Maranhão e Ceará, por exemplo, mostram o contrário para essa amostra de 2019. E também pode-se confirmar a proporção parecida de cada classe pela forma dos gráficos.

<a href="#sumario">Voltar ao sumário</a>

---
## <a name="regional">3 - Regional</a>

#### <a name="item_3-1"></a>3.1 - O PIB (Produto Interno Bruto) tem impacto nos resultados?
!["Gráfico de Comparação - Acesso computador e internet"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_3-1.png)
Tendo em vista os dados contidos na matriz e nos gráficos, mesmo com o critério menos conservador considerando o mínimo de 0.7, o PIB não tem correlação forte com as notas.

<a href="#sumario">Voltar ao sumário</a>

---
#### <a name="item_3-2"></a>3.2 - A quantidade de escolas, matrículas e docentes têm impacto nos resultados?

!["Gráfico de Comparação - Quantidade de escolas Vs Desempenho"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_3-2.png)
Analisando o conjunto de gráficos acima é possível identificar a semelhança entre as variáveis, exceto Área KM², devido regiões com baixa densidade populacional, estados com grandes dimensões de matas, florestas e de algum tipo de cultura agronômica. As curvas (Y Hat) traçadas identificam um certa relação entre as variáveis e a nota média total, que basicamente quanto maiores melhores são as notas, esceto a aréa territorial, que se se comporta inversamente a medida que aumenta.

<a href="#sumario">Voltar ao sumário</a>
---

#### <a name="item_3-3"></a>3.3 - Qual o desempenho de cada estado e DF?

!["Gráfico de Comparação - Desempenho por estado"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_3-3.png)
Comparando os resultados pela mediana das médias de notas no ambito nacional, os resultados estaduais estão bem equilibrados, a maioria dos estados têm a mediana à direita do centro, ponto 0 dos gráficos normalizados, entretanto os resultados dos estados das regiões sul e sudeste ainda têm resultados melhores que o restante, juntamente com o Distrito Federal, variando em torno de 530. Sendo mais criterioso e conservador, pode-se dizer que ainda não está satisfatório, já que os programas de bolsas exigem a média simples das notas acima de 600.

<a href="#sumario">Voltar ao sumário</a>

---
# <a name="participantes"></a>4 - Participantes

#### <a name="item_4-1"></a>4.1 - Os participantes já concluiram o ensino médio?
!["Gráfico de Comparação - Conlusão ensino médio"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-1.png)
Analisando os gráficos acima, pode-se identificar que a grande maioria dos candidatos já concluiram o ensino médio, esses cadidatos tiveram resultados semelhantes aos que ainda estão cursando com a mediana em torno de 500, com sua maioria acima desse valor, já a minoria, os que não conluiram e não cursam o ensino médio, têm em grande parte medianas abaixo de 500. Também é possível conferir o desempenho dos que já concluiram e concluir que o desempenhos são similares em todas as classes, só se diferem na dispersão das notas, ou seja, a quantidade de notas que não estão dentro dos quartis, blocos do gráfico à direita.

<a href="#sumario">Voltar ao sumário</a>

---

#### <a name="item_4-2"></a>4.2 - Qual o tipo de escola?
!["Gráfico de Comparação - Tipo de escola"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-2.png)
O gráfico acima à direta comprova a diferença entre o desempenho dos estudates de escolas privadas, que possuem a mediana acima de 600, além disso, os que não informaram o tipo de escola também possuem a mediana maior que os estudantes de escolas públicas. A amostra reflete a realidade, então mesmo sendo menos que 5% dos participantes do Enem, a qualidade de ensino das escola particulares se mostra bem melhor que as escolas públicas, como já se sabe há tempos.

<a href="#sumario">Voltar ao sumário</a>

---

#### <a name="item_4-3"></a>4.3 - Qual o tipo de ensino? 
!["Gráfico de Comparação - Tipo de ensino"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-3.png)
O gráfico acima à direta comprova a diferença entre o desempenho dos estudates de escolas privadas, que possuem a mediana acima de 600, além disso, os que não informaram o tipo de escola também possuem a mediana maior que os estudantes de escolas públicas. A amostra reflete a realidade, então mesmo sendo menos que 5% dos participantes do Enem, a qualidade de ensino das escola particulares se mostra bem melhor que as escolas públicas, como já se sabe há tempos.

<a href="#sumario">Voltar ao sumário</a>

---
#### <a name="item_4-4"></a>4.4 - O grau de escolaridade dos tem impacto nos resultados?

!["Gráfico de Comparação - Escolaridade"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-4.png)
Os gráficos acima mostram que que a escolaridade dos pais vão aumentando, os resultados dos participantes participantes vão melhorando, podendo dizer que a escolaridade dos pais, tem impacto posito no desempenho dos candidatos.

<a href="#sumario">Voltar ao sumário</a>

---
#### <a name="item_4-5"></a>4.5 - A ocupação dos pais tem impacto nos resultados?

!["Gráfico de Comparação - Ocupação"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-5.png)
Assim como a escolaridade e a renda, provavelmente por serem os mesmos participantes, a medida que o grupo de ocupação aumenta os resultados melhoram nitidamente.

<a href="#sumario">Voltar ao sumário</a>

---
#### <a name="item_4-6"></a>4.6 - O acesso à internet tem impacto nos resultados?

!["Gráfico de Comparação - Acesso internet"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-6.png)
Os gráficos acima confirmam que o acesso À internet faz diferença nos resultados em todas as classes de renda, as formas amarelas têm maior volume acima das formas verdes, a linha pontilhada no meio indica a mediana, e por ela de conclue que os participantes com acesso à internet em casa têm resultamos melhores, principalmente na classe mais alta.

<a href="#sumario">Voltar ao sumário</a>

---
#### <a name="item_4-7"></a>4.7 - Há diferença entre os resultados de cada raça/cor, como eles estão districuidos nas classe de renda familiar e qual são seus resultados?

!["Gráfico de Comparação - raça/cor"](https://github.com/AndrehAguiar/ALURA_imersao_dados/blob/main/images/img_4-7.png)
Analisando os gráficos acima, os de cor parda são maioria em todas as classes, seguidos dos participantes de cor branca e em seguida os de cor preta, e estão distribuidos de forma equilibrada dentres as classes, considerando o volume de indivíduos de cada uma delas. Os resultados são bem similares, variando relevantemente somente de um grupo ocupacional para outro, consequentemente, como já foi ilustrado em gráficos anteriores, a medida que a renda aumenta o desempenho melhora. Porém, considerando a cor/raça de cada grupo de ocupação, os resultados dos partipantes do Enem de 2019 tiveram resultados equivalentes de acordo com a estrutura falimiliar, renda e ocupação, somente nos grupos 4 e 5 há diferença relevante nos resultados de cada raça/cor, os de cor branca e não informada passa a ter resultados melhores.

<a href="#sumario">Voltar ao sumário</a>

---
Agradecimentos:
Grupo Alura Caelum pelo compartilhamento do conhecimento de propagação da informação para aprimorar a carreira e nossas habilidades.
UNI-BH por me proporcionar essa opotunidade de mostrar o que estou aprendendo na Pós-Graduação em Ciência de Dados e Inteligência Artificial me capacitando para chegar a esse resultado, que particularmente, já me deixa muito satisfeito.
Sei que isso é só a ponta o iceberg e estou só começando, mas a cada novo projeto me motivo e me apaixono mais pela área, DS/ML e programação.

## MUITO OBRIGADO!!!


---


#### Referências:
Fonte: IBGE. Diretoria de Pesquisas - DPE -  Coordenação de População e Indicadores Sociais - COPIS.

PENA, Rodolfo F. Alves. "PIB dos estados brasileiros"; Brasil Escola. Disponível em: https://brasilescola.uol.com.br/brasil/pib-dos-estados-brasileiros.htm. Acesso em 24 de outubro de 2020.

---

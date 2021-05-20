# MachineLearningCP

Usando a biblioteca sklearn, elaboramos um programa em python que lê três valores a respeito da glicemia do paciente de modo a ser analisado pelo método "machine learning". Utilizamos os seguintes critérios como forma de diagnóstico: Em jejum\* , pós-sobrecarga\** e glicemia casual\***.

- \* Sem ingestão de alimentos há no mínimo 8 horas.
- \** Duas horas após 75g de glicose.
- \*** Realizado em qualquer hora do dia.

Com base nesses 3 critérios o programa será capaz de dizer se o paciente está com a glicose normal, tolerância à glicose diminuida e diagnóstico de diabetes mellitus.

Primeiro estabelecemos qual biblioteca será importada para parâmetro do programa, que no caso foi a sklearn. Após isso, inserimos os valores para usar como base. Em seguida, classificamos esses valores com os labels. A variável "classif" relaciona as variáveis "features" e "labels", depois ajustamos o modelo com o método ".fit" que encontrará os coeficientes para a equação em questão.
Posteriormente criamos variáveis que recebem o valor da entrada do tipo "float" do usuário com suas informações. As condições estão relacionadas com a variável "x" que faz o julgamento das instâncias dos dados e retorna a conclusão.
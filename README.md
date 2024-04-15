# dio-lab-azure-IA900

Em função de aprender mais sobre Machine Learning no Bootcamp da DIO sobre Microsoft Azure, criei uma conta grátis no Azure e, seguindo as documentações oficiais, desenvolvi um modelo de previsão sobre aluguel de bicicletas. Abaixo estão os links que utilizei:

[Explore Automated Machine Learning in Azure Machine Learning](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html)
<br>
[Documentação do Azure Machine Learning](https://learn.microsoft.com/pt-br/azure/machine-learning/?view=azureml-api-2)
<br>
<hr>

## Passo 1: Criar um recurso
A documentação oficial nos pede para configurar seguindo alguns requisitos. Para o nome do workspace, escolhi Lab-IA900 por ser intuitivo.
<br>
<br>
## Passo 2: Criar um Workspace
Isso pode levar alguns minutos, mas brevemente o workspace é criado e, clicando em "Launch studio", somos direcionados para outra página em que é necessário reconfigurar alguns requisitos do recurso inicial
<br>
<br>
## Passo 3: Entrada de dados de treinamento
Com o workspace criado, precisamos de dados de entrada para que a máquina entenda e siga os algoritmos. Nesse caso, a documentação afirma que os dados utilizados serão do Capital Bikeshare, um sistema de aluguel de bicicletas em Washington D.C. que autorizou a utilização dos dados de suas matrizes. Os dados servirão para que a máquina seja treinada e preveja o número de bicicletas que serão alugadas em um determinado dia, baseados em características sensoriais e meteorológicas.
<br>
<br>
## Passo 4: Criar um Automated ML
A documentação oficial traz as configurações que necessitamos ter para criar um Automated ML job, além de disponibilizar a URL dos dados web que selecionamos como opção de entrada de dados. Após preencher todos os campos necessários, o Azure inicia automaticamente o processo e demora, em média, de 10 a 20 minutos (mas isso pode variar de acordo com a entrada de dados e outros requisitos).
<br>
<br>
## Passo 5: Revisões
Com a conclusão, o trabalho do machine learning pode ser avaliado da melhor maneira que desejar. Eu, particularmente, observei melhor as métricas gráficas para comparar umas com as outras.
<br>
<br>
## Passo 6: Teste de modelo
Para testar o modelo criado, basta seguir as instruções que a documentação traz para analisar os resultados: um número previsto de aluguéis com base nos recursos de entrada.

![image](https://github.com/MaduSales/dio-lab-azure-IA900/assets/166547195/d8762a5b-1950-4740-9c61-a1244f189480)
<br>
![image](https://github.com/MaduSales/dio-lab-azure-IA900/assets/166547195/f3eeda18-57db-4975-9bcb-608acc62da75)





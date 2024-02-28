<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Trabalhando com Machine Learning na Prática no Azure ML </span>
</h1>

Repositório desenvolvido para fins didáticos. 

Parte de um conjunto de labs do Bootcamp Microsoft Azure AI Fundamentals da [Digital Innovation One](https://www.dio.me/).

Este repositório responde ao desafio no lab  **Trabalhando com Machine Learning na Prática no Azure ML** 

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/lab/trabalhando-com-machine-learning-na-pratica-no-azure-ml/learning/feb31f95-6d53-4317-8519-b455fee120fa) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/lab/trabalhando-com-machine-learning-na-pratica-no-azure-ml/learning/feb31f95-6d53-4317-8519-b455fee120fa)

## Objetivo 🎯
Demonstrar a pratica de criar nossa conta no Azure e explorar as capacidades de Machine Learning da plataforma para desenvolver nossa primeira automação prática. 
Ao aplicar implementações e soluções escaláveis de aprendizado de máquina na nuvem da Microsoft, adquiriremos conhecimentos valiosos e experiência na construção de soluções eficientes.

### Azure Machine Learning.

Os elementos testados fazem parte da suite de inteligência artificial do Azure AI services. 
Então uma sequencia de passos é necessária:

1o. Ter uma conta na Azure. Acesso o  Azure portal no link https://portal.azure.com

2o. Ter uma assinatura válida (signature). É possível testar por 1 mês com 200 dólares de crédito.

3o. Criar um recurso "Azure AI services" dentro de um Grupo de Recursos


3.1 Criar o grupo de recursos:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/2f5b7b4c-d3ee-49d4-9844-b015d6f59c2e)

3.2 Criar o recurso, clicar em + criar recurso do tipo Azure Machine Learning:
![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/38781a9a-1c7e-45fd-ae2b-9a97566da28a)

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/7a5fad22-4981-47dd-8655-71a881d01c7a)

4o. Acessar o Ai Studio
4.1 depois de criado o recurso pode diretamente clicar no botão launch studio:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/70757851-0bd7-486f-a8f9-0e686a203d51)

OU acessar a url : https://ml.azure.com

## 5o. Usar o ML automatizado para treinar um modelo

5.1 Selecionar o menu de ML Automatizado:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/42ec1865-82f0-42c0-b1f0-6e424103bb99)

Clicar no botão "+ Novo trabalho de ML Automatizado"

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/631b80c3-af31-4320-8cd1-429a304c3885)

Criar o ativo de dados:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/791b15f9-1ee1-4f41-a900-79a6b035fbce)

A fonte de dados selecionar arquivos da web e usar a url https://aka.ms/bike-rentals

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/87f15d5d-da5a-43e9-8bd2-88de4b4e374c)

Nas configurações atenção para selecionar "somente o primeiro arquivo tem cabeçalhos"

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/9defd680-9221-47ea-95b8-d48544bcebd0)

No "Esquema" deixar como a sugestão de todos selecionados menos o "Path"

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/a69e5429-3464-4e69-9563-d4dc3bfc1327)

Conferir os tipos de dados sugeridos (todos inteiros) e clicar em criar:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/885b8ea2-9b66-4078-8c39-c0c9b4185e22)


Selecionar o ativo criado e avançar:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/61fb089b-0abc-48ec-8fb1-4f573f8b26e0)


![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/faf94aef-93de-474e-a5b9-848816e1183c)


Clicar no botão de engrenagem: "Exibir definições de configurações adicionais" que irá abrir um menu na direita.
Atenção para fazer a seleções conforme imagem abaixo:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/10e9805c-28be-46ac-9244-11fc30bf92bd)

Clicar para definir os limites:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/2537da72-a814-42c2-91fb-9b54107a3883)

Definir os detalhes da computação (pode aceitar as sugestões conforme abaixo):

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/7cfc6d33-e994-438e-a276-51ddb533a56c)

Clicar em enviar o treinamento:

![image](https://github.com/toniacprado/DIO-Trabalhando-com-Machine-Learning-na-Pratica-no-Azure-ML/assets/105946569/b38bb17d-579d-4ca8-b979-e48af1ca65d1)

Aguardar alguns minutos para o trabalho ser executado.





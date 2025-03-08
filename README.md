# 3 -- Análise-de-Sentimentos-com-Language-Studio-no-Azure-AI

# Análise de Sentimentos com Language Studio no Azure AI

Passo a passo do desafio de projeto "Análise de Sentimentos com Language Studio no Azure AI" da DIO.

Links importantes:

- [Explore Speech Studio](https://aka.ms/ai900-speech)
- [Analyze text with Language Studio](https://aka.ms/ai900-text-analysis)

# Tópico 1: Primeiramente, conhecendo a função de converter fala para texto

## Passo 1: Criando recurso do Speech service no Azure AI Services e convertendo fala em texto

Primeiro foi preciso criar um recurso do Speech service dentro do Azure AI Services.

![Img](./img/img1.gif)

Após o recurso ter sido criado, tive que acessar o [Estúdio de fala do Azure](https://speech.microsoft.com/portal). Na página inicial, no tópico "Conversão de fala em texto", cliquei em "Conversão de fala em texto em tempo real".

Na próxima página, foi preciso indicar o recurso anterior que eu iria usar. Para isso, cliquei em meu nome no canto superior, e em "Recurso atual", tive que mudar para o recurso criado anteriormente no Portal do Azure.

![Img](./img/img2.png)

Assim o checkbox informando sobre o uso do recurso ficou disponível.

![Img](./img/img3.png)

Entretanto, essa é a forma que segui para criar e usar o recurso. A forma utilizada no vídeo para criar o recurso dentro do Estúdio de fala deve funcionar.

Em seguida, fiz o upload de uma gravação de voz que eu havia feito minutos antes. A fala foi convertida para texto muito rapidamente.

![Img](./img/img4.gif)

Esse foi o resultado da conversão:

![Img](./img/img5.png)

# Tópico 2: Análise de sentimento

## Passo 1: Criando um recurso do Language Service no Azure AI Services

Primeiro foi preciso criar um recurso do Language Service dentro do Azure AI Services.

![Img](./img/img6.gif)

Após o recurso ter sido criado, acessei o [Estúdio de linguagem do Azure](https://language.cognitive.azure.com/).

Assim que foi logado, foi preciso indicar a minha assinatura e o recurso que eu havia criado em um modal que abriu. Também é possível criar um novo recurso de linguagem aqui.

Após isso, foi aberta a aba "Classify text" e cliquei em "Analyze sentiment and opinions". Em "Select text language", escolhi Portuguese (Brazil) e em seguida colei uma opinião bem positiva sobre um computador para testar.

![Img](./img/img7.gif)

Ao testar, inseri o seguinte texto:

[OBS: Descreva o seu Desktop ou Notebook]  
Estou bem satisfeito com o meu Desktop, ele é bem rápido e supera e muito as minhas expectativas, espero que ele dure por muito mais tempo, tenho muito apreço pelo meu computador, ele tem uma capacidade bem bacana, e até agora está me atendendo muito bem.

Resultado da análise do texto:

![Img](./img/img8.png)

Resultado no texto original:

![Img](./img/img9.png)

# Tópico 3: Excluir os recursos criados

Por fim, exclui os recursos que criei para este desafio.

![Img](./img/img10.gif)

# Azure Cloud

O propósito deste repo foi somente explorar Azure Speak Studio e Azure Language Studio, e aplicar em algum contexto prático.


## Azure Speak Studio


Azure Speech Studio é uma plataforma da Microsoft que permite criação e personalização de soluções baseadas em fala, integrando os recursos do Azure Cognitive Services. Algumas das aplicações são: *Reconhecimento de fala (speech-to-text)*, *Síntese de fala (text-to-speech)*, *Custom Voice (criação de voz a partir de amostras)*, *Tradução  de fala entre idiomas*, *Análise de conversas (extração de insights delas)*.


## Azure Language Studio

O Azure Language Studio é uma plataforma da Microsoft voltada ao **Processamento de Linguagem Natural** (NLP), que permite criar, testar e personalizar modelos de IA para análise de textos. Oferece recursos como análise de sentimentos, extração de entidades, classificação de textos, detecção de idioma, tradução, compreensão de intenções e criação de bases de conhecimento.

## Análise de Sentimentos no dataset Amazon Fine Food Reviews utilizando Azure Language Studio

Este é um resumo da minha exploração na Azure, mais específicamente, executando uma Análise de Sentimentos utilizando o serviço Cloud da Azure [Language Studio](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://language.cognitive.azure.com/&ved=2ahUKEwjTkp__2LWOAxU9DLkGHXz3B4cQFnoECAoQAQ&usg=AOvVaw0RIrbRgryzFjxZXgFWxWWt) no dataset [Amazon Fine Food Reviews](www.kaggle.com/datasets/snap/amazon-fine-food-reviews).

O tipo de **Análise de Sentimentos** escolhido foi o **nível de Documento**, porém, para uma análise mais detalhada e com insights mais pontuais precisariamos o **nível de Aspecto**. Pelo dataset estar composto de múltiplas reviews sem um contexto em comum, apenas sumarizei os resultados, o notebook pode ser encontado [aqui](https://github.com/AlejandroAlberoni/azure-studio-speech-and-language/blob/main/AmazonFineFoodReviews_AzureSentimentAnalysis.ipynb). 



<p align="center">
<img width="515" height="417" alt="AmazonFineFoodReviewsSentimentPolarityDist" src="https://github.com/user-attachments/assets/e4012afe-3716-49da-bb3c-58dd68f9ce1c" />
</p>

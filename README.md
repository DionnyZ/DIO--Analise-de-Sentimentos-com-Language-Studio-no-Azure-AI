# Análise de Sentimentos com Language Studio no Azure AI

O objetivo desse desafio foi utilizar na prática alguns serviços do Speech Studio e do Language Studio.

Para evitar cobranças, não criei uma conta e utilizei as amostras gratuitas.

## Speech Studio

O Speech Studio oferece serviços, como:
 - Legendar vídeos em tempo real
 - Transcrever gravações de call center
 - Avatar que fala o texto que foi fornecido

O serviço utilizado nesse desafio foi o de criar legendas em tempo real.

A legenda é criada conforme a fala, então o texto que é exibido vai sendo atualizado a cada palavra que é detectada.

O exemplo abaixo mostra como a legenda é gerada. É possível ver que a mesma frase vai se completando conforme o tempo avança e detecta novas palavras.

```
0
00:00:02,440 --> 00:00:02,800
When

1
00:00:02,800 --> 00:00:03,330
When it comes to the neural

2
00:00:03,330 --> 00:00:03,710
When it comes to the neural TTS

3
00:00:03,710 --> 00:00:04,470
When it comes to the neural TTS in

4
00:00:04,470 --> 00:00:04,830
When it comes to the neural TTS in order to
```

<img src="/images/legenda_em_tempo_real.png" width="600">

Esse serviço pode ser utilizado em videos chamadas ou transmições ao vivo para criar legendas em tempo real, melhorando a acessibilidade e o entendimento do conteúdo.

## Language Studio

O Languade Studio oferece serviços, como:
 - Extração de informação de textos
 - Classificação de texto para análise de sentimento
 - Customização de respostas para uma lista de perguntas

O serviço utilizado para o desafio foi o de analisar o sentimento a partir de um texto.

Foi feito a análise de sentimento do seguinte texto:

```
Long waits...BUT FOR GOOD REASON. Some awesome Italian food and great vibes. Contoso Bistro always has live music or events going on to keep you entertained. The food is good enough to keep me entertained though!

        The Contoso Bistro lasagna is a classic! The outdoor back patio is such a vibe, especially in the summer. Great service as well :) Love this place and will be back for more.
```

A imagem a seguir exibe qual foi o sentimento detectado no texto. Nesse caso foi misto, voltado mais para o positivo.

<img src="/images/analise_de_sentimento_1.png" width="300">

A próxima imagem exibe como a análise foi feita, indicando quais foram as palavras chaves e o sentimento detectado nessa sentença.

<img src="/images/analise_de_sentimento_2.png" width="600">

Esse serviço pode ser utilizado para analisar a opinião de um público muito grande, reduzindo o tempo de análise caso fosse feito manualmente.

# Atividade II

## Proposta

Longo dia esse, hein?!
Seu chefe pediu para que você aplique o teste em um candidato a uma vaga para redes e te passou um seguinte problema para você utilizar.  

Porém, ele pediu para que você o resolvesse antes, e este é o enunciado:  
>***Imagine que uma pessoa treinou o seu cachorro, o Piteco, para carregar uma caixa de fitas DAT que pode conter até 3 fitas de 5 GBytes.
O cachorro consegue caminhar ao lado de seu dono a uma velocidade de até 15 Km/h.
Para qual faixa de distâncias o cachorro consegue ser mais rápido do que um canal de comunicação de 100 Mbps?***  

 Seu chefe dá aquele sorriso maroto e diz para você que não se trata de um problema de física ou de matemática, mas de operações básicas o que interessa é somente seu entendimento do problema e a correta interpretação para construir a resposta.  
 Por fim, ele vira para você e diz para você se apressar, pois o candidato chega em 1 hora.

## Solução

Bom, como a ideia central é Piteco vencer essa corrida, primeiramente é necessário descobrir o tempo que o adversário será capaz de entregar ``até 3 fitas de 5 GB``.  

**Então, o Canal de Comunicação:**

```"
QtdDados = 3 * 5 GB => 15 GB * 1024 => 15.360 MB * 1024 => 15.728.640 KB;
TaxaTransm = 100 Mbps * 1024 => 102.400 / 8 => 12.800 Kbps;
Tempo = 15.728.640 / 12.800 => 1.228,8 segundos / 60 => 20,48 minutos
O Canal de Comunicação fará a entrega em 00:20:48  
```

Se o pitaco caminha 15 km/h, para sair com a vitória ele deve percorrer 1/3 de hora o que equivale à 20 min e como 15 km / 3 é igual a 5 km, o canino sairá vitorioso se a distância for igual ou inferior à 5 km.  
>***Portanto, em uma distância de até 5 km o pitaco será o campeão e poderá sair para comemorar.*** :dog: :dancer:

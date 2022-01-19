# Projeto Airbnb

![orla](https://www.viagensecaminhos.com/wp-content/uploads/2011/02/florianopolis-santa-catarina.jpg)

O objetivo desse projeto é realizar uma análise exploratória dos dados do Airbnb referentes à cidade de Florianópolis para responder às seguintes perguntas:

1. Qual é o número de anúncios em cada bairro?
2. Qual é o faturamento médio dos imóveis em cada bairro?
3. Existem correlações entre as características de um anúncio e seu faturamento? 
    a. Quais? Explique
4. Qual a antecedência média das reservas?
     a. Esse número é maior ou menor para finais de semana?

A análise foi realizada em Pyhton.

### Dados

Foram utilizadas duas bases, details e price. A base details está a nível do imóvel(anúncio) e traz características do imóvel como bairro, número de banheiros e quartos, nome do anúncio, avaliação em estrelas, superhost e número de avaliações. A segunda base, price, está a nível do imóvel e da data de ocupação e traz informações como data, data da reserva, preço da diária e ocupação.

### Bibliotecas

Os dados foram manipulados com as bibliotecas <i>Pandas</i> e <i>Numpy</i>. Para as visulizações, os pacotes utilizados foram <i>Seaborn</i> e <i>Matplotlib</i>. Por fim, para gerar automaticamente o relatório em PDF, os pacotes utilizados foram <i>Ipyhton.display</i>, <i>nbconvert</i>, <i>codecs</i> e <i>nbformat</i>.


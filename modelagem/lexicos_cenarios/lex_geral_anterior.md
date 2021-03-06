# Léxicos Gerais - Versão Inicial

***
## Airbnb <a name="AIRBNB"></a>

#### Noção:
- Aplicativo que promove a intermediação entre prestadores de serviço [Anfitrião](#ANFITRIAO) e consumidores de serviço [Hóspede](lex_geral.md#HOSPEDE).

#### Impacto
- [Hóspede](lex_geral.md#HOSPEDE) podem contratar serviços.
- [Anfitrião](#ANFITRIAO) podem ofertar e vender serviços.

#### Classificação:
Objeto

***

## Usuário <a name="USUARIO"></a>
#### Sinônimos:
- user
- cliente
- utilizador

#### Noção:
- Qualquer tipo de pessoa cadastrada ou não no sistema.
- Pode ser diferenciado em : [Hóspede](lex_geral.md#HOSPEDE), [Anfitrião](#ANFITRIAO) e [Visitante](#VISITANTE)

#### Impacto
- O usuário podera utilizar os [serviços](lex_geral.md#SERVICO) do [Airbnb](lex_geral.md#AIRBNB)
- O usuário poderá se cadastrar no [Airbnb](lex_geral.md#AIRBNB)
- O usuário pode realizar [Anúncio](lex_geral.md#ANUNCIO) para divulgar a sua [acomodação](lex_geral.md#ACOMODACAO) no airbnb

#### Classificação:
Objeto

***

## Acomodação <a name="ACOMODACAO"></a>

#### Sinônimos:
- aposentos
- local residencial

#### Noção:
- Divisão, compartimento, cômodo  onde as pessoas se instalam, moram, se hospedam.
- Local que o [Anfitrião](lex_geral.md#ANFITRIAO) disponibiliza para locação

#### Impacto
- [Anfitrião](lex_geral.md#ANFITRIAO) disponibiliza através de [Anúncio](lex_geral.md#ANUNCIO) para que os [hóspedes](lex_geral.md#HOSPEDE) possa alugar.

#### Classificação:
Objeto

***

## Anúncio <a name="ANUNCIO"></a>

#### Sinônimos:
- propaganda
- publicidade

#### Noção:
- Notícia ou aviso por meio do qual se divulga algo ao público.

#### Impacto
- [Anfitrião](lex_geral.md#ANFITRIAO) pode crir um anúncio grátis
- Anúncio é realizado pelo [anfitrião](lex_geral.md#ANFITRIAO) para que possam divulgar o local que querem disponibilizar para os [hóspedes](lex_geral.md#HOSPEDE) alugarem.

#### Classificação:
Objeto

***

## Anfitrião <a name="ANFITRIAO"></a>
#### Sinônimos:
- host
- dono da casa

#### Noção:
- Um usuário que anuncia algum [Serviço](lex_geral.md#SERVICO) atravez do [Airbnb](lex_geral.md#AIRBNB).
- [Recebe Remuneração](lex_geral.md#REMUNERACAO) pelo serviço oferecido.
- É divido em [Anfrião de Experiencia](lex_experiencia.md#ANFITRIAO-EXPERIENCIA), [Anfitrião de Hospedagem](#) e [Anfitrião de Restaurante](#)

#### Impacto
- [Hóspedes](lex_geral.md#HOSPEDE) poderão usufruir do serviço, após realizar o [Pagamento](lex_geral.md#PAGAMENTO).

#### Classificação:
Objeto

***

## Visitante <a name="VISITANTE"></a>
#### Sinônimos:
- usuário não cadastrado

#### Noção:
- Um usuário que acessa o [Airbnb](#AIRBNB) sem estar logado.
#### Impacto:
- Visitante pode efetuar [busca por acomodação](#cen_hospedagem.md#BUSCAR-ACOMODACAO)
- Visitante pode acessar detalhes de acomodação.
#### Classificação:
- Objeto

***

## Hóspede <a name="HOSPEDE"></a>
#### Sinônimos:
- guest
- visitas

#### Noção:
- Um usuário que contrata um anuncia algum [Serviço](lex_geral.md#SERVICO) oferecido por um [Anfitriao](lex_geral.md#ANFITRIAO).
- [Faz Pagamento](lex_geral.md#PAGAMENTO) atravéz do  [Airbnb](lex_geral.md#AIRBNB).

#### Impacto
- [Anfitrião](#ANFITRIAO) recebe pelo [Serviço](lex_geral.md#SERVICO) prestado.

#### Classificação:
Objeto

***

## Serviço <a name="SERVICO"></a>
#### Sinônimos:
- service
- emprego
- função

#### Noção:
- Atividade oferecida por um [Anfitriao](lex_geral.md#ANFITRIAO).
- [Hóspede](lex_geral.md#HOSPEDE) [Faz Pagamento](lex_geral.md#PAGAMENTO) por utiliza-lo.
- Pode ser divido em [Experiencia](lex_experiencia.md#EXPERIENCIA), Restaurante e Hospedagem.

#### Impacto
- [Hóspede](lex_geral.md#HOSPEDE) o utiliza.  

#### Classificação:
Objeto

***

## Vagas <a name="VAGAS"></a>
#### Sinônimos:
- vacancies
- vaga
- disponíveis

#### Noção:
- Um [Serviço](lex_geral.md#SEVICO) que não [Foi Reservado](lex_geral.md#RESERVADA)

#### Impacto
- [Serviços](lex_geral.md#SEVICO) que não [Foi Reservado](lex_geral.md#RESERVADA) estarão disponíveis.  

#### Classificação:
Estado

***

## Faz Pagamento <a name="PAGAMENTO"></a>
#### Sinônimos:
- do payment

#### Noção:
- Atividade realizada pelo [Hóspede](lex_geral.md#HOSPEDE) no momento em que contrata o serviço oferecido pelo [Anfrião](lex_geral#ANFITRIAO)

#### Impacto
- [Hóspede](lex_geral.md#HOSPEDE) [Recebe Remuneração](lex_geral.md#REMUNERACAO) pelo [Serviço](lex_geral.md#SEVICO).  

#### Classificação:
Verbo

***

## Recebe Remuneração <a name="REMUNERACAO"></a>
#### Sinônimos:
- get payment

#### Noção:
- [Anfrião](lex_geral#ANFITRIAO) atravéz do [Airbnb](lex_geral.md#AIRBNB) o pagamento pela prestação do [Serviço](lex_geral.md#SERVICO).

#### Impacto
- [Airbnb](lex_geral.md#AIRBNB) faz a intermediação e recebe porcentagem

#### Classificação:
Verbo

***

##  Ser Reservada <a name="RESERVADA"></a>
#### Sinônimos:
- be reserved
- ser locada
- foi reservada

#### Noção:
- Atividade realizada pelo [Hospede](lex_geral.md#HOSPEDE) no momento em que se confirma a locação do [Serviço](lex_geral.md#SERVICO) desejado com o [Anfrião](lex_geral#ANFITRIAO).

#### Impacto
- O [Serviço](lex_geral.md#SERVICO) fica indisponível para outro [Hospede](lex_geral.md#HOSPEDE) no período que ele foi reservado.  

#### Classificação:
Verbo

***

## Avaliação<a name="AVALIACAO"></a>
#### Sinônimos:
- opinião
- julgamento
- análise
- nota

#### Noção:
- Nota atribuida à alguma pessoa, [anfitrião](lex_geral.md#ANFITRIAO) ou [hóspede](lex_geral.md#HOSPEDE)); à um lugar, [acomodação](lex_geral.md#ACOMODACAO)  ou [restaurante](lex_restaurantes.md#RESTAURANTE); à uma [experiência](lex_experiencia.md#EXPERIENCIA)

#### Impacto
- O [hóspede](lex_geral.md#HOSPEDE) visualiza a avaliação
- O [hóspede](lex_geral.md#HOSPEDE) dá uma avaliação
- O [anfitrião](lex_geral.md#ANFITRIAO) visualiz a avaliação
- O [anfitrião](lex_geral.md#ANFITRIAO) dá uma avaliação
- O [Airbnb](lex_geral.md#AIRBNB) ordena por avaliação

#### Classificação:
Objeto

***

## Internet<a name="INTERNET"></a>
#### Sinônimos:
- web
- rede

#### Noção:
- Rede mundial que, pela troca virtual de dados e mensagens, une computadores particulares, smartphones, organizações de pesquisa, institutos de cultura, institutos militares, bibliotecas, corporações de todos os tamanhos; rede mundial de computadores.

#### Impacto
- O [usuário](lex_geral.md#USUARIO) conecta-se a internet para obter informações do [Airbnb](lex_geral.md#AIRBNB)
- O [usuário](lex_geral.md#USUARIO) conecta-se a internet para submeter informações parao [AIrbnb](lex_geral.md#AIRBNB)

#### Classificação:
Objeto

***

## Smartphone<a name="SMARTPHONE"></a>
#### Sinônimos:
- celular
- smartphone

#### Noção:
- Telefone inteligente com um sistema operacional configurável

#### Impacto
- O [usuário](lex_geral.md#USUARIO) realiza as interações com o [Airbnb](lex_geral.md#AIRBNB) através do smartphone

#### Classificação:
Objeto

***

## Quesitos de Busca <a name="QUESITOS"></a>
#### Sinônimos:
- quesitos
- aributos de busca

#### Noção:
- Atributos utilizados para que o [usuário](lex_geral.md#USUARIO) possa buscar um [Serviço](lex_geral.md#SERVICO)
- São eles: "[Onde](lex_geral.md#ONDE)", "[Check-in](lex_geral.md#CHECKIN)", "[Checkout](lex_geral.md#CHECKOUT)" e "[Hóspede](lex_geral.md#HOSPEDE)"(quantidade de hóspedes).

#### Impacto
- O [usuário](lex_geral.md#USUARIO) realiza uma busca por um [Serviço](lex_geral.md#SERVICO) por meio de algum desees quesitos.

#### Classificação:
Objeto

***

## Onde <a name="ONDE"></a>
#### Sinônimos:
- localização
- local
- endereço

#### Noção:
- Localização geográfica ou endereço de onde se encontra o serviço.

#### Impacto
- O [usuário](lex_geral.md#USUARIO) realiza uma busca por um [Serviço](lex_geral.md#SERVICO) por meio de sua [Localização](lex_geral.md#ONDE)
- [Serviço](lex_geral.md#SERVICO) se encontra em uma [Localização](lex_geral.md#ONDE)

#### Classificação:
Objeto

***

##  Check-in <a name="CHECKIN"></a>
#### Sinônimos:
- dar entrada
- apresentar-se

#### Noção:
- Data inicio, na qual o [Serviço](lex_geral.md#SERVICO) [será reservado](lex_geral.md#RESERVADA).

#### Impacto
- A apartir desse dia o [Serviço](lex_geral.md#SERVICO) reservado ficará indisponível para outro [Hospede](lex_geral.md#HOSPEDE) até o [Checkout](lex_geral.md#CHECKOUT).  

#### Classificação:
Verbo

***

##  Checkout <a name="CHECKOUT"></a>
#### Sinônimos:
- dar saída
- encerrar reserva

#### Noção:
- Data final, na qual o [Serviço](lex_geral.md#SERVICO) [será reservado](lex_geral.md#RESERVADA).

#### Impacto
- A apartir desse dia o [Serviço](lex_geral.md#SERVICO) reservado volta a estar disponível para outro [Hospede](lex_geral.md#HOSPEDE).  

#### Classificação:
Verbo

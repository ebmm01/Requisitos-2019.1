## Introdução

Trata-se de uma técnica que procura descrever os símbolos de uma linguagem. O principal objetivo a ser perseguido pelos Engenheiros de Requisitos é a identificação de palavras ou frases peculiares ao meio social e da aplicação sob estudo.

Para o levantamento inicial de palavras e termos, o grupo realizou um [Brainstorm](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso). A partir daí, e dos próprios léxicos foram aparecendo outros termos que o grupo julgou interessante serem modelados.

Obs.: Vale salientar que aqui estão dispostos somente os léxicos feitos individualmente. Dessa forma, caso algum hyperlink redirecione para outra wiki, isso signigica que o Léxico hyperlinkado não foi feito por mim, mas sim por outro membro do Guiabolso.

## Léxicos

### L1 - Nome Sujo

| **L1** | **Nome Sujo**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l1-nome-sujo_1) |
| **Classificação** | Estado |
| **Sinônimos** | Devedor, caloteiro |
| **Noção** | > Quando uma pessoa possui nome sujo no serasa <br> > O nome da pessoa está no cadastro da dívida ativa de órgãos de cobrança <br> > Status da pessoa que não honra com suas dívidas | 
| **Impacto** | > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) com o nome sujo não faz empréstimos <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) com o nome sujo não consegue contratar alguns serviços <br> > Operadoras de cobrança ligam constantemente para o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) com o nome sujo |
| **Rastro** | [Brainstorm BS2](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L4 - Score do Serasa

| **L4** | **Score do Serasa**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l4-score-do-serasa_1) |
| **Classificação** | Objeto |
| **Sinônimos** | Pontuação |
| **Noção** | > Pontuação numérica que classifica economicamente uma pessoa <br> > Chance percentual de um indivíduo não pagar uma conta | 
| **Impacto** | > Um indivíduo com o score do serasa alto tem o [cadastro positivo](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l2-cadastro-positivo) aceito <br> > Um indivíduo com o score do serasa baixo tem uma chance alta de estar com o [nome sujo](#l1-nome-sujo) <br> > Um indivíduo com o score do serasa baixo tem dificuldade em conseguir um [crédito pré-aprovado](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l6-credito-pre-aprovado) |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |

### L5 - Dívida ativa

| **L5** | **Dívida Ativa**  |
|--|--|
| **Versão**| Atual: 1.1 (23/04) <br> Anterior: [1.0](#l5-divida-ativa_1) |
| **Classificação** | Objeto |
| **Sinônimos** | Negativado, cadastro devedor |
| **Noção** | > Inserção do nome de um indivíduo com o status de [nome sujo](#l1-nome-sujo) no cadastro de devedores dos serviços de proteção de crédito <br> > Estar com o [nome sujo](#l1-nome-sujo) | 
| **Impacto** | > Um [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) que está na dívida ativa tem seu [score do serasa](#l4-score-do-serasa) reduzido <br> > Um [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) que está na dívida ativa tem uma redução de linhas de crédito |
| **Rastro** | [Brainstorm BS2](../../elicitacao-de-requisitos/brainstorm/#brainstorm-2-levantamento-de-palvras-chave-dentro-do-contexto-do-guiabolso) |


### L27 - Cartão de débito 

| **L27** | **Cartão de débito** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Classificação** | Objeto |
| **Sinônimos** | Despesa, À vista |
| **Noção** | > Modo de pagamento usando cartão; <br> > Pagamento feito à vista usando cartão, geralmente de um banco; |
| **Impacto** | > Ao comprar no débito o indivíduo sabe o valor gasto na hora; <br> > Ao se comprar no débito, o valor da [transação](#l30-transacao-bancaria) é descontado imediatamente do dinheiro do indivíduo; <br> > O indivíduo não pode parcelar uma compra feita no débito; <br> Ao comprar no débito o indivíduo passa a ter mais controle dos seus gastos; <br> > Ao comprar no débito o usuário pode ter um histórico de compras, a depender da [instituição financeira](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l31-instituicao-financeira) do cartão | 
| **Rastro**| Não possui (elicitado ao se fazer cenários) | 

### L28 - Cartão de crédito

| **L28** | **Cartão de crédito** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Classificação** | Objeto |
| **Sinônimos** | À prazo, crediário |
| **Noção** | > Modo de pagamento usando cartão; <br> > Pagamento feito usando o cartão, que terá seu valor debitado *à posteriori*; |
| **Impacto** | > Ao comprar no crédito o indivíduo pode parcelar ou não a compra; <br> > Ao se comprar no crédito, o valor da [transação](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l30-transacao-bancaria) não é descontado imediatamente do dinheiro do indivíduo; <br> > O indivíduo pode parcelar uma compra feita no débito; <br> > Ao comprar no crédito o indivíduo pode acabar tendo um descontrole financeiro; <br> > Ao comprar no crédito o indivíduo pode pagar a compra em valores menores, permitindo a compra de um produto mais caro de forma suave | 
| **Rastro**| Não possui (elicitado ao se fazer cenários) | 

### L29 - Desconto 

| **L29** | **Desconto** |
|--|--|
| **Versão**| Atual: 1.0 <br> Anterior:-- |
| **Classificação** | Objeto |
| **Sinônimos** | Corte, dedução, pechincha |
| **Noção** | > Redução no preço de um produto ou serviço; |
| **Impacto** | > O indivíduo que consegue um desconto paga preços menores em certos produtos; <br> > O desconto em contas permite que o usuário tenha uma maior ;[saúde financeira](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l19-saude-financeira) <br> > Compras com desconto permitem um menor [comprometimento de renda](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l7-comprometimento-de-renda) de um indivíduo; <br> > O desconto pode incentivar um indivíduo a gastar mais do que pode pagar, obrigando-o a reccorer à um empréstimo; | 
| **Rastro**| Não possui (elicitado ao se fazer cenários) | 

## Versões anteriores

### L1 - Nome Sujo

| **L1** | **Nome Sujo**  |
|--|--|
| **Versão**| 1.0 | 
| **Noção** | > Quando uma pessoa possui nome sujo no serasa <br> > O nome da pessoa está no cadastro da dívida ativa de órgãos de cobrança <br> > Status da pessoa que não honra com suas dívidas | 
| **Impacto** | > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) com o nome sujo não faz empréstimos <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) com o nome sujo não consegue contratar alguns serviços <br> > Operadoras de cobrança ligam constantemente para o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) com o nome sujo |

### L4 - Score do Serasa

| **L4** | **Score do Serasa**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Pontuação numérica que classifica economicamente uma pessoa <br> > Chance percentual de um indivíduo não pagar uma conta | 
| **Impacto** | > Um indivíduo com o score do serasa alto tem o cadastro positivo aceito <br> > Um indivíduo com o score do serasa baixo tem uma chance alta de estar com o nome sujo <br> > Um indivíduo com o score do serasa baixo tem dificuldade em conseguir um crédito pré-aprovado |

### L5 - Dívida ativa

| **L5** | **Dívida Ativa**  |
|--|--|
| **Versão**| 1.0 |
| **Noção** | > Inserção do nome de um indivíduo com o status de nome sujo no cadastro de devedores dos serviços de proteção de crédito <br> > Estar com o nome sujo | 
| **Impacto** | > Um [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) que está na dívida ativa tem seu score do serasa reduzido <br> > Um [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) que está na dívida ativa tem uma redução de linhas de crédito |

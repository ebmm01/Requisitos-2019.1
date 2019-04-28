## Introdução

Esta técnica descreve os requisitos numa linguagem fácil de entender e validar para todas as pessoas relacionadas com o projecto, motivando-as a discutir e participar, obtendo assim um maior feedback sobre o que se está a fazer.

Obs.: Vale salientar que aqui estão dispostos somente os cenários feitos individualmente. Dessa forma, caso algum hyperlink redirecione para outra wiki, isso signigica que o Léxico hyperlinkado não foi feito por mim, mas sim por outro membro do Guiabolso.

## Cenários

### C8 - Simular um empréstimo

| **C8** | **Simular um empréstimo**|
|--|--|
| **Versão**| Atual: 1.0 (21/04) <br> Anterior: -- |
| **Metas/Objetivos** | Permitir ao [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) conhecer as condições e prazos de um empréstimo antes de ele fazer um |
| **Contexto** |**O que?**  <br>> O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) simula um empréstimo; <br><br> **Onde?** <br>> Na aba “Empréstimos” do aplicativo; <br><br> **Quando?** <br>> A qualquer momento, desde que haja um empréstimo disponível; <br> <br>**Por quê?** <br>> Para verificar se vale a pena ou não a realização do empréstimo.|
|**Ator(es)** | > [Usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario); <br> > Guiabolso; <br> > [Instituições financeiras]; <br> Serviços de proteção ao crédito.|
| **Recursos** | > Conta no Guiabolso; <br> > Internet; <br> > [Crédito pré-aprovado].|
| **Restrição** | > Ter CPF; <br> > Não ter o noome sujo; <br> > Ter conta no aplicativo. |
| **Exceção** | > [Score](../lexicos/#l4-score-do-serasa) do [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) ser baixo; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) não ter [crédito pré-aprovado]; <br> > Internet indisponível; <br> > Falha no aplicativo; <br> > Falha na comunicação com a [Instituição financeira]; <br> > Ausência ou quebra do celular do [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario).|
| **Episódios** | > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) instala o Guiabolso; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) navega até a aba “Empréstimos” do aplicativo; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) insere os dados solicitados (CPF, valor pretendido, tempo que pretende pagar, etc); <br> > O aplicativo procura um empréstimo de acordo com as necessidades do [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario); <br> > Se disponível, o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) visualiza o(s) empréstimo(s) disponíveis e opta por fazer ou não o empréstimo; <br> > Caso contrário o aplicativo não exibirá nenhum empréstimo disponível.|

### C13 - Criar uma conta

| **C13** | **Criar uma conta**|
|--|--|
| **Versão**| Atual: 1.0 (21/04) <br> Anterior: -- |
| **Metas/Objetivos** | Descrever como o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) cria uma conta no aplicativo do Guiabolso |
| **Contexto** |**O que?** <br> > [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) criar uma nova conta; <br><br> **Onde?** <br>> No aplicativo Guiabolso; <br><br> **Quando?** <br>> A qualquer momento; <br><br> **Por quê?** <br> > Para o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) desfrutar de todas as funcionalidades do Guiabolso; |
|**Ator(es)** | > [Usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario); <br> > Guiabolso.|
| **Recursos** | > Celular e/ou computador; <br> > Guiabolso; <br> > Indíviduo |
| **Restrição** | > O indíviduo não possuir um dispositivo capaz de acessar  Guiabolso; |
| **Exceção** | > Internet indisponível; <br> > Falha no Aplicativo; <br> > Erro ao importar os dados bancários |
| **Episódios** | > indivíduo deseja utilizar o Guiabolso; <br> > indivíduo instala o Guiabolso <br> > O indivíduo preenche todos os dados necessários para o cadastro; <br> >O indivíduo se torna um [Usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) da aplicação |

### C15 - Avaliar dicas

| **C15** | **Avaliar dicas**|
|--|--|
| **Versão**| Atual: 1.0 (21/04) <br> Anterior: -- |
| **Metas/Objetivos** | Descrever como o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) pode avaliar uma dica da aba "Guia" do aplicativo |
| **Contexto** |**O que?** <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) avalia uma dica; <br><br> **Onde?** <br>> Na aba "Guia" do aplicativo Guiabolso; <br><br> **Quando?** <br>> Sempre que o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) visualizar uma dica ; <br><br> **Por quê?** <br> > Para melhorar as dicas exibidas para o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) e ser uma forma de feedback para o Guiabolso; |
|**Ator(es)** | > [Usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario); <br> > Dicas da aba "Guia" <br> > Guiabolso.|
| **Recursos** | > Celular e/ou computador; <br> > Guiabolso; <br> > Indíviduo |
| **Restrição** | > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) não ter uma [conta automática](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l12-conta-automatica); |
| **Exceção** | > Internet indisponível; <br> > Falha no Aplicativo;  |
| **Episódios** | > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) entra no aplicativo; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) entra na aba "Guia" e visualiza uma dica; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) avalia a dica como útil ou não. |

### C16 - Adicionar código de segurança

| **C16** | **Adicionar código de segurança**|
|--|--|
| **Versão**| Atual: 1.0 (21/04) <br> Anterior: -- |
| **Metas/Objetivos** | Descrever como o [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) pode adicionar um código de segurança no aplicativo |
| **Contexto** |**O que?** <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) adiciona um código de segurança; <br><br> **Onde?** <br>> No Guiabolso; <br><br> **Quando?** <br>> A qualquer momento ; <br><br> **Por quê?** <br> > Para melhorar a segurança das informações do [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) ; |
|**Ator(es)** | > [Usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario);  <br> > Guiabolso.|
| **Recursos** | > Celular e/ou computador; <br> > Guiabolso; <br> > Indíviduo|
| **Restrição** | > O indíviduo não possuir uma conta no Guiabolso; |
| **Exceção** | > Internet indisponível; <br> > Falha no Aplicativo; <br> > Senha pouco segura |
| **Episódios** | > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) entra no aplicativo; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) entra nas configurações e clica em "Código de segurança"; <br> > O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) insere o PIN desejado; <br> O [usuário](https://fga-disciplinas.github.io/2019.1-Guia-Bolso/modelagem/lexicos/#l13-usuario) passa a usar o Guiabolso somente se inserir o PIN |


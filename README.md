# Automação Web

Testes automatizados Web utilizando o Robot Framework + Selenium.

**Site:** http://automationpractice.com/index.php

## CENÁRIOS DE TESTE

**CN0001-Criação de novo cadastro no Automation Practice**

<p>Dado que acesso o site automation practice <br />
E o cliente deseja realizar um cadastro<br />
Quando preencher o campo email<br />
E clicar em Create an account<br />
E entrar com as informações de cadastro<br />
Então um novo cadastro é criado<br />

**CN0002-Login com sucesso no Automation Practice**

<p>Dado que acesso o site automation practice <br />
E clico em Sign In<br />
Quando preencho o campo email no email<br />
E preencho o campo senha<br />
E clico no botão Sign In no login<br />
Então sou direcionado para a pagina com titulo My account - My Store<br />

**CN0003-Pesquisar roupas femininas com o menor valor**

<p>Dado que acesso o site automation practice<br />
E clico na categoria Women<br />
Quando filtrar para ordenar os preços por ordem decrescente<br />
Então são exibidas as peças ordenas do menor para o maior valor<br />

**CN0004-Compra com sucesso utilizando forma de pagamento Pay by bank wire**
<p>Dado que acesso o site automation practice <br />
E clico em Sign In<br />
E clico na opção Women<br />
Quando adicionar o produto Faded Short Sleeve T-shirts ao carrinho<br />
E adicionar o produto Blouse no carrinho<br />
E realizo os proximos passos da venda com pagamento Pay by bank wire<br />
Então a mensagem Your order on My Store is complete é exibida após concluir compra<br />

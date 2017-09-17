# Instalação e Preparação do Ambiente

## Instalação

Para realizar nosso projeto em JavaScript vamos precisar de algumas ferramentas que facilitarão nosso trabalho. A primeira delas é o <b>Node.js</b>.

## Para que serve o Node.js?

Já vimos que JavaScript é uma linguagem pensada para atender ao cliente, ou seja, ao usuário de uma página web. Com o JS, as páginas ganham interatividade e dinamismo com scripts (instruções) interpretados pelo próprio navegador, no computador de quem está utilizando o site. Lembra que explicamos o que significa front-end? Podemos chamar também de client-side, isto é, o lado do cliente.

Em oposição, o back-end – ou server-side – é o lado do servidor, que é onde o site fica hospedado. As linguagens server-side são desenvolvidas para serem entendidas pelo servidor, que então envia a resposta para o navegador.

Por exemplo: se quisermos que o site faça um cálculo matemático e criarmos o script para essa função em uma liguagem de back-end (algumas das mais usadas: Java, PHP, Ruby), quem vai calcular é o servidor, e depois ele enviará o resultado para o navegador no qual o usuário está acessando a página. No entanto, se escrevermos esse script em uma linguagem front-end como o JavaScript, o cálculo será feito pelo navegador, ali mesmo no computador do usuário.

O Node.js é uma plataforma de desenvolvimento de aplicações server-side que utiliza linguagem JavaScript.

## Como é? Achei que JavaScript era uma linguagem front-end!

Pois é, essa é a grande vantagem de utilizar o Node. Com ele, podemos usar a mesma linguagem tanto no front-end como no back-end, e não precisamos nos preocupar com a comunicação entre as duas partes – que já vão estar falando a mesma língua!

Para instalar o Node.js você pode [baixar](https://nodejs.org/en/#download) e executar o instalador para o seu sistema operacional. Se você utilizar uma distribuição Linux baseada em Debian ou Ubuntu, pode seguir as instruções abaixo:

###Linux baseado em Debian ou Ubuntu:

Abra o terminal e digite o comando a seguir:

```
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
```

Pressione Enter e aguarde o processamento. Quando o processo finalizar, digite:

```
sudo apt-get install -y nodejs
```

E pressione Enter novamente. Pronto! :)


## Preparando o Ambiente

:construction:


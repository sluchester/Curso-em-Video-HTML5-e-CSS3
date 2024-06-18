# Anotações Curso em Vídeo HTML5 e CSS3

## Sites necessários
github.com/gustavoguanabara
gustavoguanabara.github.io

## Documentação
* Mozilla Developer Network
* W3C Standards (W3C World Wide Web Consortium)
* WHATWG Living Standard
* W3Schools (Refsnes Data)

## Domínio x Hospedagem

Sites estão armazenados em servidores. Para acessar o site, é necessário efetuar uma requisição ao DNS.  Este irá direcioná-lo ao site. 

* Domínio: Nome que identifica o site. Pago anualmente. Vários TLDs (Top Level Domains).
* Hospedagem: Local onde o site está armazenado. Pago mensalmente. Espaço, memória, recursos.

## HTML x CSS x JS

HTML e CSS não são linguagens de programação. HTML é uma linguagem de marcação. CSS é uma linguagem de estilos. 

- HTML: focado em conteúdo (texto, imagem, lista, etc)
- CSS: focado em estilo/design (cores, sombras, tamanhos)
- JS: linguagem de programação focada em interações com o usuário (menu, interações)

### Conteúdo em HTML

Para fazer um título:

```HTML
<h1> Exemplo de título </h1>

OBS: abertura/fechamento de tag
```

Para abrir um parágrafo:
```HTML
<p> Exemplo de título </p>
```

Estrutura básica:
```
<!DOCTYPE html>
<html lang="pt-br">
.   <head>
.       //configurações
.       <meta charset="UTF-8">
.       <meta name="viewport"
.       content="width=device-width,initial-scale=1.0">
.       <title>Document</title>
.   </head>
.   <body>
.       //onde fica o site
.       <h1>Olá, Mundo!</h1>
.   </body>
</html>
```

### Conteúdo em CSS

```
h1{
    font-family: Arial;
    font-size: 20pt;
    color: blue;
}

OBS: h1 é o seletor. O que está dentro das chaves é a "declaração". Cada declaração é um conjunto de propriedade e valor. O h1 é referente ao título HTML anteriormente criado.
```

### Curiosidades
- Front-end: tecnologias que vão rodar do lado do cliente. UX/UI.
- Back-end: tecnologias que vão rodar no lado do servidor. Ex: php, js, c#, python, ruby, java.
- Full-Stack: a junção dos dois acima.
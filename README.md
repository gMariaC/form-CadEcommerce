# Projeto - Formulário de Cadastro Ecommerce.

Projeto criado como parte da disciplina de Fundamentos de Desenvolvimento, ministrada pelo professor Leonardo Rocha.

## Índice

* [Descrição](#descrição)
* [Tecnologias](#tecnologias)
* [Referências](#referencias)
* [Autor(a)](#autora)
* [Estilização](#estilização)

### Descrição

O projeto consiste na composição de uma página de "Log-in", "Endereço" e "Conclusão", para que o usuário insira informações sensíveis para se cadastrar em um site de compras. Para construção desse projeto, foram reutilizados os projetos de [Formulário de contato](https://github.com/gMariaC/form-contato), [Formulário de login](https://github.com/gMariaC/projeto-login) e o [Projeto Ecommerce](https://github.com/gMariaC/projeto-ecommerce)

Antes de iniciar o projeto, foram feitas pesquisas em três diferentes sites de compra online, eles foram: [SHEIN](https://br.shein.com), [Shopee](https://shopee.com.br) e a [Amazon](https://www.amazon.com.br).

# Resultado do projeto.

![Resultado Final do Projeto](img/resultado-login.png)
![Resultado Final do Endereço](img/resultado-endereco.png)
![Resultado Final de Conclusão](img/resultado-conclusão.png)

## Cadastro Ecommerce.

* DOCTYPE - É uma instrução para o navegador da web que diz em qual versão do HTML a página é escrita.
* Main - Define o título do documento, mostrado na barra de título de um navegador ou na aba da página.
* Link - Especifica as relações entre o documento atual e um recurso externo.
* Meta - Define qualquer informação de metadados que não podem ser definidos por outros elementos HTML.
* title - Define o título do documento, mostrado na barra de título de um navegador ou na aba da página.
Veja a seguir uma imagem de parte do código, onde é possível identificar o uso dos elementos mencionados a cima:

![Estrutura do Index](img/estrutura-index.png)

* Head - Providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos.
* body - Serve para representar tudo o que é exibido na página.
* br - Cria uma quebra de linha em um texto.
* form - Serve para criar formulários e definir a forma como eles se comportam.
* label - Especifica o rótulo de um input em um formulário, e é importante para a experiência de um usuário.
* input - Serve para criar campos de entrada de dados interativos, que permitem o usuário insira textos, números, datas, cores, entre outros.
* a - com o atributo href cria-se um hiperligação nas páginas web.
* button - Insere botões clicáveis em páginas e formulários, que podem executar ações quando um usuário clica neles.
A seguir, mais uma imagem de parte do código, onde se visualiza os elementos usados a cima:
![](img/estrutura-elementos.png)

## Estilização

O projeto foi estilizado, utilizando CSS3. Foi criado um arquivo chamado login.css. Neste arquivo, constam as seguintes configurações de estilo:

#### Estilo de cores na página.
* background-color - Define a cor de fundo da página, e foi usado como se vê a seguir:
```
body{
    background-color: rgb(170, 99, 236);
}
```
* color - Define a cor das letras na página.
```
.form{
    color: rgb(30, 3, 103);
}
```

#### Altura e largura de um conteúdo.
* height - Determina a altura da área do conteúdo de um elemento.
```
.container{
    height: 100%;
}
```
* width - Determina a largura da área de conteúdo de um elemento.
```
.container{
    width: 100%;
}
```

#### Distância entre conteúdos.
* padding - Define uma a distância entre o conteúdo de um elemento e suas bordas.
```
.form{
    padding: 40px;
}
```
* padding-top - Define as dimensões do espaçamento interno superior (distância do elemento para sua própria borda.
```
.form{
    padding-top: 0;
}
```

#### Fonte principal da página:
```
body{
    font-family: Verdana;
}
```

#### Caixa para inserir textos.
* border-radius - Adiciona bordas arredondadas a caixa de textos.
```
.form{
    border-radius: 30px;
}
``` 
* box-shadow - Adiciona sombra a volta da caixa.
```
.form{
    box-shadow: 0 0 30px black;
}
```

#### Organização.
* display - Uma propriedade utilizada para organizar os elementos na página HTML.
```
body{
    display: flex;
}
```

## Tecnologias

* HTML
* CSS3
* README
* Git
* GitHub

## Referencias

* [Alura](https://www.alura.com.br/artigos/escrever-bom-readme) - Como escrever um README íncrivel no seu GitHub.
* [Formulário de contato](https://github.com/gMariaC/form-contato)
* [Formulário de login](https://github.com/gMariaC/projeto-login)
* [Projeto Ecommerce](https://github.com/gMariaC/projeto-ecommerce)
* [SHEIN](https://br.shein.com)
* [Shopee](https://shopee.com.br)
* [Amazon](https://www.amazon.com.br)

## Autor(a)

Projeto desenvolvido pela aluna:
* Maria Clara da Silva Gonçalves
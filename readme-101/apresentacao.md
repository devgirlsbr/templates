# **README 101: teoria e prática**

![Logo-meetup](../../assets/logo1.png)

Após ter visto o Legadão e entender o que é, que tal deixar um bom legado no seu portifólio do GitHub e no seu trabalho?  Bora manter as coisas organizadas e bem acessíveis para quem encontrar o seu repositório?

## O que você encontrará nessa talk?

=================
<!--ts-->
   * [O que é um README](#O-que-é-um-README)
   * [Muito prazer: Eu sou o Markdown!](#Eu-sou-o-Markdown)
     * [Alguns exemplos](#Alguns-exemplos)
   * [Importância](#Importância)
   * [Dúvida vital](Dúvida-vital)
   * [README Estruturado](#README-Estruturado)
   * [Dica](Dica)
   * [Fontes e Referências](Fontes-e-Referências)
 <!--te-->

## O que é o arquivo README?

Em tradução livre, do inglês *README* significa leia-me.

Em alguns softwares, encontramos o arquivo do tipo **leiame.txt**. Neste arquivos podemos encontrar algumas instruções como apresentação do software, como instalar e o que encontrar no pacote de instalação.

O README é um arquivo do tipo markdown. E não difere da sua versão .txt no que diz respeito aos seus objetivos. 
 	
Nele estão contidas as informações necessárias para entender o objetivo do projeto, como foi desenvolvido (considerando suas etapas), Tecnologias e dependências necessárias, as motivações para desenvolvimento, o porquê das escolhas feitas, as etapas de construção e o passo a passo de como ele funcionará, caso seja feita uma cópia. 
 	
Trocando em miúdos, ele é a 'Receita' do projeto.
 	
Ele também é uma espécie de 'cartão de visitas' do projeto e de sua desenvolvedora. E pode ser usado na avaliação de um currículo, como portifólio, pelas empresas.
 	
Falando em nível de conhecimento mesmo, é através dele que pode ser observadas características como: organização de ideias, enumeração de etapas de desenvolvimento e até a linha de raciocínio para chegar à solução final. 

## Muito prazer: Eu sou o Markdown!

Esta é a extensão do arquivo README. Este é o nome completo do md.

A sintaxe básica do Markdown é aquela que foi originalmente definida por John Gruber, o criador do Markdown. A grande maioria dos aplicativos que suportam Markdown oferecem suporte a todos os elementos dessa sintaxe. Ainda assim, pode haver pequenas variações dependendo do processador de texto que você usa, mas elas serão minoria.

O [Markdown](https://guides.github.com/features/mastering-markdown/) é uma forma de estilizar texto na web. Como ele você controla a exibição do documento, formata palavras como negrito ou itálico, adiciona imagens e cria listas. 

Na maioria das vezes, ele é um texto que contém caracteres não alfabéticos, como '#' ou '*'.

### Alguns exemplos de formatos Markdown.

1. Textos

É muito fácil colocar algumas palavras em **negrito** e outras palavras em *itálico* com Markdown. 

2. Listas

Podem ser:

Numeradas

1. Um
2. Dois
3. Três

Pontos/Traços

* Comece uma linha com uma estrela
* Lucro!

Traços (itens e subitens)

- Traços funcionam tão bem
- E se você tiver subpontos, coloque dois espaços antes do travessão ou estrela
  - Como isso
  - E isto

3. Imagens

Se você deseja incorporar imagens, faça o seguinte:

![Imagem-de-Mona-the-Riveterocat](../assets/mona.png)


4. Cabeçalhos e citações

Na linguagem HTML os seis níveis de tamanhos são marcados pela letra <'h'+ 'número'>, no markdown esses níveis são marcados por '#'. 

# H1
## H2
### H3
#### H4
##### H5
###### H6


Para fazer uma citação use o caracter '>' antes da linha.

> Nossa família é uma estratificação alternativa de poesia e matemática.

> - Ada Lovelace

5. Código

O código fica entre 6 acentos graves, separados 3 a 3.

```js

if (isAwesome) {
  retornar verdadeiro
}
```

6. Outros (Marcar um @) ou links

@isagiongo - amei saber do legadão!

Você pode até usar o [link para o Google!](http://google.com)

É possível ver outras funcionalidades do [Markdown](https://guides.github.com/features/mastering-markdown/) acessando sua documentação. 

## Mas, Eline, qual é a importância de se construir um README?

Como falei lá no início, ele pode ser usado como seu cartão de visitas. Alguns recrutadores, na verdade a maioria deles, não domina tecnologias, então utilizam o GitHub como concretização do seu currículo, então eles observam o que você sabe fazer e o que você já fez através do que está escrito no README.

Também é bem comum as empresas não pedirem um currículo e sim aplicar testes práticos. Estes testes ficam em seu GitHub(ou site que você use para versionar projetos)pessoal e o link é enviado. A descrição do que foi feito é um dos requisitos.

Você pode utilizar plugins no VSCode (Readme Parttern ou Simple Readme), ferramentas como: [Typora](https://typora.io/) ou fazer online, utilizando o site [makeareadme](https://www.makeareadme.com/).

Porém, o mais importante é **escrever bem**.

Ser Desenvolvedora não é só sobre códigos, é também sobre saber escrever o que você sabe fazer. É o famoso: Vender o peixe!!!

### Dúvida Vital: que idioma devo usar?

A resposta é: Depende!

Observe qual é o seu objetivo e do seu projeto. 

Caso, você esteja de olho em vagas fora do país, vale colocar em inglês, incluse já praticar com as mensagens de commit.

Mas, não fique decepcionada. Se você ainda não sabe inglês, pode ser em português mesmo =)

## README Estruturado - O que não pode faltar?

É bom seguir um passo a passo. Saber quais são os itens que devem estar no arquivo e utilizar os recursos que o markdown oferece.

- Logo ou Banner(opcional) - apresentação visual do seu projeto. É a sua marca;
- Título e Descrição(obrigatório) - O nome do projeto;
- Badges(opcional) - São as etiquetas identificadoras, As tags ;
- Status do Projeto(obrigatório) - Em que ponto seu projeto se encontra? Em andamento, finalizado;
- Tabela de Conteúdos(obrigatório) -  O que tem no seu projeto;
- Features(opcional) -  Funcionalidades do projeto, O que ele faz;
- Demonstração da Aplicação(opcional) - Como usar um link no Netlify ou no Heroku;
- Pré-requisitos e como rodar a aplicação/testes(obrigatório) - Mostrar os passos de como instalar seu projeto. Se tiver testes, é bom descrever como rodá-los;
- Tecnologias utilizadas(obrigatório) - Bom usar para projetos de portfólio/estudos;
- Contribuição(opcional) - É legal colocar quem está contribuindo com seu projeto;
- Autor(obrigatório) - Mostre quem fez;
- Licença(recomendado ) - A mais usada é a do MIT que permite que as pessoas baixem o projeto e modifiquem isentando o autor de qualquer responsabilidade.

## Dica

- Quer usar emojis e está em um computador windows? Clica as teclas (Windows + . ) e veja a mágica acontecer.
- Você pode usar tags html para facilitar sua escrita, mas lembre-se que este não será um markdown puro. Antes dê uma olhada na sintaxe estendida. 


### Aff, mas é muito complicado fazer isso tudo! 😄 
### Que tal usar um template onde você possa somente inserir as informações referentes ao seu projeto?

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////

**Fontes e Referências:**

1. [Como criar um Readme incível](https://onebitcode.com/como-criar-um-readme-incrivel-para-seus-projetos-e-perfil-no-github/).

2. [Como fazer um bom readme](https://blog.rocketseat.com.br/como-fazer-um-bom-readme/).

3. [Guia do Markdonw](https://guides.github.com/features/mastering-markdown/).

4. [O que é Readme](https://blog.rocketseat.com.br/o-que-e-readme-e-porque-e-tao-importante/).

5. [Sobre Ada Lovelace](https://citacoes.in/autores/ada-lovelace/).

6. [Emojis em Markdown](https://tutorialmarkdown.com/emojis).

7. [Markdown](https://guides.github.com/features/mastering-markdown/);

8. [Sintaxe estendida - Markdown](https://markdown.net.br/sintaxe-estendida/);




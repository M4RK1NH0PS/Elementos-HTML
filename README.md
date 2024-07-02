# Elementos-HTML
Esta página lista todos os elementos HTML. Eles são agrupados por função para ajuda-lo a achar o que quer fácilmente. Apesar deste guia ser escrito para aqueles mais inexperientes com a programação, nós esperamos que seja útil para todos.

# Metadados do documento
Os metadados são onde se guardam várias informações sobre a página, incluindo informações sobre estilos, scripts e dados para auxiliar software (ferramentas de pesquisa, navegadores, etc) usar e renderizar a página. Os metadados de estilos e scripts podem ser definidos dentro da própria página ou escritos em um arquivo externo que é referênciado pela mesma.


<base>	O elemento HTML Base (<base>) especifica o endereço (URL) utilizada por todos os endereços relativos contidos dentro de um documento. Há um número máximo de 1 (um) elemento Base <base> do documento.

<head>	O elemento HTML <head> providencia informações gerais (metadados) sobre o documento, incluindo seu título e links para scripts e folhas de estilos.

<link>	O Elemento HTML <link> especifica as relações entre o documento atual e um recurso externo. Possíveis usos para este elemento incluem a definição de uma estrutura relacional para navegação. Este elemento é mais usado para vincular as folhas de estilo.

<meta>	O elemento **HTML <meta> **define qualquer informação de metadados que não podem ser definidos por outros elementos HTML. (<base>, <link>, <script>, <style> ou <title>).

<style>	O elemento HTML <style> contém informações de estilo para um documento ou uma parte do documento. As informações de estilo específico estão contidas dentro deste elemento, geralmente no CSS.

<title>	O elemento HTML <title> (Elemento HTML Título) define o título do documento, mostrado na barra de título de um navegador ou na aba da página. Pode conter somente texto e quaisquer marcações contidas no texto não são interpretadas.

#Sectioning root
<body>	O elemento <body> do HTML representa o conteúdo de um documento HTML. è permitido apenas um <body> por documento.


# Separação de conteúdo
Elementos de separação de conteúdo permitem organizar o conteúdo do documento em partes lógicas. Use elementos de separação para criar um esboço do conteúdo da página, incluindo navegação por cabeçalho e rodapé, e elementos de cabeçalho para identificar seções de conteúdo.

<address>	O elemento HTML <address> fornece informações de contato para seu ancestral <article> ou <body> mais próximo; no segundo caso, ele se aplica ao documento inteiro.

<article>	O Elemento HTML Article (<article>) representa uma composição independente em um documento, página, aplicação, ou site, ou que é destinado a ser distribuido de forma independente ou reutilizável, por exemplo, em sindicação. Este poderia ser o post de um fórum, um artigo de revista ou jornal, um post de um blog, um comentário enviado por um usuário, um gadget ou widget interativos, ou qualquer outra forma de conteúdo independente.

<aside>	O elemento HTML <aside> representa uma seção de uma página que consiste de conteúdo que é tangencialmente relacionado ao conteúdo do seu entorno, que poderia ser considerado separado do conteúdo. Essas seções são, muitas vezes, representadas como barras laterais. Elas muitas vezes contem explicações laterais, como a definição de um glossário; conteúdo vagamente relacionado, como avisos; a biografia do autor; ou, em aplicações web, informações de perfil ou links de blogs relacionados.

<footer>	O elemento HTML de Rodapé (<footer>) representa um rodapé para o seu sectioning content (conteúdo de seção) mais próximo ou sectioning root elemento (ou seja, seu parente mais próximo <article>, <aside>, <nav>, <section>, <blockquote>, <body>, <details>, <fieldset>, <figure>, <td>). Normalmente um rodapé contém informações sobre o autor da seção de dados, direitos autorais ou links para documentos relacionados.

<header>	O elemento HTML <header> representa um grupo de suporte introdutório ou navegacional. Pode conter alguns elementos de cabeçalho mas também outros elementos como um logo, seções de cabeçalho, formulário de pesquisa, e outros.
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>	Os elementos HTML <h1>–<h6> representam seis níveis de título de seção. <h1> é o nível de seção mais alto e <h6> é o mais baixo.

<main>	O elemento <main> define o conteúdo principal dentro do <body> em seu documento ou aplicação. Entende-se como conteúdo principal aquele relacionado diretamente com o tópico central da página ou com a funcionalidade central da aplicação. O mesmo deverá ser único na página, ou seja, dentro do elemento <main> não deverão ser incluidas seções da página que sejam comuns a todo o site ou aplicação, tais como mecanismos de navegação, informações de copyright, logotipo e campos de busca (a não ser, é claro, caso a função principal do documento seja fazer algum tipo de busca).

<nav>	O Elemento HTML de Navegação (<nav>) representa uma seção de uma página que aponta para outras páginas ou para outras áreas da página, ou seja, uma seção com links de navegação.

<section>	O elemento HTML <section> representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.


# Conteúdo textual
Usam-se elementos HTML de conteúdo textual para se organizar blocos ou seções de conteúdo postos entre as tags de abertura <body> e fechamento </body>. Importantes para accessibilidade e SEO, esses elementos identificam o propósito ou estrutura do conteúdo.

<blockquote>	O Elemento HTML <blockquote> (ou Elemento HTML de citação de bloco) indica que o texto incluído é uma longa citação. Normalmente, este é processado visualmente pelo recuo (ver Notas sobre como mudá-lo). A URL para a fonte da citação pode ser dada usando o atributo cite, enquanto uma representação de texto da fonte pode ser dada usando o <cite> elemento.

<dd>	O elemento HTML <dd> fornece detalhes ou uma definição mais completa do termo precedente (definido por <dt>) numa lista de descrições (<dl>).

<div>	O elemento de divisão **HTML <div> **é um container genérico para conteúdo de fluxo, que de certa forma não representa nada. Ele pode ser utilizado para agrupar elementos para fins de estilos (usando class ou id), ou porque eles compartilham valores de atributos, como lang. Ele deve ser utilizado somente quando não tiver outro elemento de semântica (tal como <article> ou <nav>).
<dl>	O elemento HTML Definition List (<dl>) engloba uma lista de pares de termos e descrições. Um uso comum para este elemento é para implementar um glossário ou exibir metadados(uma lista de pares chave e valor).

<dt>	O elemento HTML <dt> (ou Elemento HTML de Definição de Termo) identifica um termo na lista de definição. Este elemento pode ocorrer somente em um elemento filho de <dl>. Geralmente seguido por um elemento <dd>; ou multiplos <dt> na mesma linha indicam vários termos sendo definidos pelo próximo element <dd>.

<figcaption>	O Elemento HTML Figcaption (<figcaption>) representa uma legenda ou uma legenda associada com uma figura ou ilustração descrita pelo resto dos dados do elemento <figure> que seu elemento pai.

<figure>	O elemento <figure> HTML representa conteúdo autocontido, potencialmente com uma legenda opcional, que é especificada usando o <figcaption> elemento. A figura, sua legenda e seu conteúdo são referenciados como uma única unidade.

<hr>	O elemento HTML <hr> representa uma quebra temática entre elementos de nível de parágrafo (por exemplo , uma mudança da cena de uma história, ou uma mudança de tema com uma seção). Nas versões anteriores do HTML, representava uma linha horizontal. Pode continuar sendo exibida como uma linha horizontal nos navegadores, mas agora está definida em termos semânticos, em vez de termos de apresentação.

<li>	O elemento HTML <li> (ou a Lista dos Itens de um elemento HTML) é usado para representar um item que faz parte de uma lista. Este item deve estar contido em um elemento pai: uma lista ordenada (<ol>), uma lista desordenada (<ul>) , ou um menu (<menu>) e representa uma única entidade dessa lista. Em menus e listas desordenadas a relação de itens é exibida, normalmente, usando pontos de marcação (as bolinhas). Em listas ordenadas eles são, comumente, mostrados com algum contador ascendente - como um número, ou letra - à sua esquerda.
<menu>	Uma alternativa semântica para (<ul>, mas tratada pelos navegadores (e exposta por meio da árvore de acessibilidade) como não diferente de (<ul>. Representa uma lista não ordenada de itens (que são representados por (<li> elementos).

<ol>	O Elemento HTML <ol> (ou Elemento HTML de lista ordenada) representa uma lista de itens ordenados. De forma característica esses itens ordenados em uma lista são mostrados com uma contagem que os precede, que pode ser de qualquer tipo, como numerais, letras, algarismos romanos, ou simples símbolos. Esse modelo numerado não é definido na descrição html da página, mas na folha de estilos CSS associada, pela propriedade list-style-type.

<p>	O elemento HTML <p> representa um parágrafo. Em mídias visuais, parágrafos são representados como blocos indentados de texto com a primeira letra avançada e separados por linhas em branco. Já em HTML, parágrafos são usados para agrupar conteúdos relacionados de qualquer tipo, como imagens e campos de um formulário.

<pre>	HTML texto preformatado (<pre>) é a tag utilizada para representar texto pré-formatado. Um texto dentro desse elemento é tipicamente exibido em uma fonte não proporcional da mesma maneira em que o texto original foi disposto no arquivo. Espaços em branco são mantidos no texto da mesma forma em que este foi digitado.

<ul>	O elemento HTML<ul> (ou elemento HTML de Lista desordenada) representa uma lista de itens sem ordem rígida, isto é, uma coleção de itens que não trazem uma ordenação numérica e as suas posições, nessa lista, são irrelevantes. Caracteristicamente, os itens em uma lista desordenada são exibidos com um marcador que pode ter várias formas, como um ponto, um círculo, ou um quadrado. O tipo de marcador não é definido na descrição HTML da página, mas na CSS associada, utilizando a propriedade list-style-type

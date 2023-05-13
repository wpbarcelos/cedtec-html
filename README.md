## O que é HTML
É uma linguagem de marcação de texto, utilizada para exibir o conteúdo dos sites.
HyperText – texto mais rico,  com links vídeos, áudios.
Markup – marcação de texto
Linguagem – Linguagem 

## Comentários
São utilizados para explicar ou documentar  um trecho de código para facilitar as futuras manutenções. Não são interpretados pelo navegador e também pode utilizar durante o desenvolvimento para omitir uma parte do código.

## Anatomia da tag (Elemento)
Um elemento HTML é formato pelo abertura de tag <p> e fechamento de tag </p>. As podem receber conteúdo , cada tag tem um significado que vai ser interpretado pelo navegador. 
Exemplo: <p>Isto é um paragrafo</p> . 
O elemento HTML é todo formado por todo conteúdo da abertura até o fechamento da tag.
Algumas tags não possuem fechamento, exemplo: img, <br> ou <br/> <hr>.

## Atributos da tag
Algumas tags possuem atributos que são declarado na abertura da tag, os atributos devem ser declarado usando o nome do atributo, sinal de igual e o valor do atributo entre aspas.
Existem atribuitos booleano, esses não receber valor só precisam serem declaradas , exemplo required ou disabled da tag input.
Exemplo <img src=”...” alt=”Texto alternativo caso a imagem não seja exibida ele vai aperecer” />

## Atributos Globais
Existe alguns atributos que são globais pode ser aplicados a todas as tags.
Ex: Id, class, title, data-*
Id – Deve existe somente um id por página, utilizado para links locais, no css e no Javascript.
Class – Serve para classificados um elemento, usado para aplicar css ou Javascript. 
Title – quando deixa o mouse em cima no elemento o title é exibido.
Data-* - Utilizado para criar qualquer atributo com o prefixo data-, data-nome, data-idade, data-telefone.

## Titulos e paragrafo
Os titulos são utilizados pelas tags h1,h2...h6, sendo o h1 o titulo principal, e geralmente temos somente um h1 por página o caso tenho outros títulos usando o h2 e h3, geralmente não usando o restante.
A tag <p /> serve para criar parágrafo.

## Imagem
A tag img não tem conteúdo e devemos utilizar o atributo src para informar o caminho da imagem, o atributo alt serve como texto alternativo caso a imagem não seja carregada. Os parâmetros width e height podem ser utilizado para redimensionar  a imagem mas não boa prática utilizar os dois juntos pois a imagem pode ficar distorcida. Tambem não devemos utilizar imagens em alta resolução para o carregamento não ficar muito lento.
Exemplo:

```html
<img src=https://placehold.co/400x300/007bff/003366/png 
alt=”imagem do placeholder.co” />
```

## Link
É utilizado para link a página a outra página de qualquer site ou criar atalhos para a própria página utilizando apontando para o id de um elemento na página. O atributo href serve para indicar o destino e o target serve para indicar o local que a página vai ser carregada, podendo ser _self (própria página) ou _blank (uma nova aba). 
 
## Lista 
Ul para criar lista não ordenada, ol para criar lista ordenada, para a tag ol existe o atributo type para podendo que tem como padrão 1, para criar lista numeradas usando os decimals.
Atributo type da tag ol 1 ,a , A, i ou I. 
A tag li é um para informar o item da lista 

## Tabela

Table , tem um atributo border para informar se tem borda o padrão 0, sem borda.
Tr  para criar a linha da tabela
Th Celular para titulo
Td Celular da tabela
Atributos da th e td:
Colspan  para a celular ocupar mais de uma coluna
Rowspan para a celular ocupar mais de uma linha


## Formulario 
Form
Input type: text , password, hidden, number, checkbox radio.
	Placeholder
Select – lista de seleção, deve ser utilizado usando a tag option como filho para popular o select.
	Option, atributo value para indicar o valor que sera selecionado e dentro o conteúdo da tag option é o que sera exibido para o usuário.
Button type=’submit’

caracteres especiais
&nbsp; &copy; &times; &larr; &darr; &uarr; &barr; &lt; &gt; &acute; &atilde; &ccedil;


## dl description list
	d- lista de descrição
	dt – titulo da descrição
	dd – descrição do item da lista

## iframe
Serve para carregar uma página html dentro da página
Exemplo embed do youtube

## Details Summary
Para colapsar um conteúdo somente usando HTML

```html
<details>
    <summary>Details</summary>
    Something small enough to escape casual notice.
</details>
```

## Documento Completo
Explicar uma estrutura completo HTML5
Exemplo do emmet no visual studio code 

## Projeto Final
Construir uma página de FAQ usando todos o recursos já passado, somente em HTML

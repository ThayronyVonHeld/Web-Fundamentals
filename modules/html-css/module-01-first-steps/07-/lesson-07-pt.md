Semântica e formatação de textos HTML

O que é semântica? A forma literal é, o significado dos vocábulos, por oposição à sua forma, ou ainda ciência que estuda a evolução do significado das palavras, signos e símbolos que estão a serviço da comunicação; semiologia

Estamos vendo essa definição por que há alguns anos no html4 existiam algumas tags que hoje já não usamos mais, por que naquela época se falava mais sobre forma que o significado 

Como por exemplo, hoje existem tags que estão em desuso/obsoletas, como bgcolor = red, ou a tag center, ou a tag marquee. 

Um outro exemplo é endereço, antigamente poderíamos fazer <p>Eu moro na <u>Rua dos capixabas, 229 - Botafogo - RJ</u></p>

Isso já não é mais uma boa pratica hoje, e sim: <p>Eu moro na <address>Rua dos capixabas, 229 - Botafogo - RJ</address></p> 

html5 não se constrói mais em forma/estilo, e sim em significado/semântica 

html5 significado/semântica 
css estilo/forma

Cuidado, algumas tags podem ficar obsoletas, por isso é sempre importante se atualizar!

Principais formatações de textos:

Começando com Negrito

Existem duas maneiras,

1-> não semântico -> Basta adicionar a tag <b>seu texto</b> dessa forma, estamos apenas mudando a forma do texto.
2->semântico -> Basta adicionar a tag <strong></strong>, dessa forma, estamos mudando além da forma, o significado, o sentido para essa coisa. 

Italico/Ênfase

Não semântico -> <i></i>
semântico -> <em></em>

Esses foram, um exemplo de formatações de texto, então aprendemos que as duas versões, negrito b e itálico i, ainda funcionam hoje no html5, porém elas ainda são do html4, e semanticamente não fazem sentido pois elas mudam apenas a forma, não o sentido. Então, se caso você queria destacar um termo em seu html use Strong, pois assim mudará seu sentido, se usar b, vai mudar apenas a sua forma, seu estilo

Uso de marca texto com estilo, com css

Em html podemos usar a tag <mark>seu texto</mark> para marcar o texto

Um ponto interessante, essa marcação ficará com a cor amarela, e em html não conseguimos mudar isso, com html vamos mudar somente a semântica/sentido. Para mudar a cor, ou seja, a forma, precisamos utilizar o style="" dentro da tag.

por exemplo: <mark style = "background-color:lime;"> seu texto </mark>

Para algumas estilizações pontuais e unicas, essa funcionalidade é bem importante e bastante usual. Mas para estruturas maiores, como com mais de um mark estilizado na mesma pagina, prefira no head, você cria um seletor.

<head>
<style>
mark{
backgroung-color:limegreen
}
</style>
</head>

em caso você queira em outras paginas, precisará criar um style.css com link externo (futuramente veremos melhor sobre estilização)





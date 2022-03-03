# LIMA (Linguagem de Marcação)

* control + shift + p = use para envelopar codigo (seleciona o conteúdo que pode ser colocado dentro de uma tag)

## GitHub
https://www.alura.com.br/artigos/escrever-bom-readme?gclid=CjwKCAiAyPyQBhB6EiwAFUuakmcd_kgTi9wg9wR42saG6dWKvps8zwFrFMFlab732szisW0VNd4QXhoCDs0QAvD_BwE
* GitHub é uma plataforma, já Git é um protocolo.
* Linha do tempo (não tem função de backup).
* Trabalho em equipe.
* Versionar código e fazer branches (ramificações do código).

## TAGs semânticas
* HEADER (Cabeçalho)
* MAIN (Conteúdo principal)
* FOOTER (Rodapé)

## TAGs genéricas (sem significado semãntico)
* DIV (Usado para "conter" qualquer item, funciona como os cômodos de uma casa)
* SPAN (usado para escrever textos simples e pequenos)

## Seletores
https://flukeout.github.io/
*   "*"   --> Universal
* header  --> Nome da tag
* .itens  --> Nome da classe
* #titulo --> Nome do ID (MUITO ESPECÍFICO, USADO POR APENAS UM ELEMENTO)
* A + B --> seleciona todos os elementos "B" que seguem diretamente "A"
* A ~ B --> seleciona todos os irmãos "B" que seguem o "A"
* A > B --> seleciona todos os elementos "B" que são filhos de "A"
* :first-child --> seleciona o primeiro elemento filho
* :oly-child --> seleciona qualquer elemento que seja o único dentro de outro, ou seja, qualquer elemento que tenha apenas um filho
* :last-child --> seleciona o último elemento filho dentro de outro elemento
* :nth-child(A) --> seleciona o elemento de acordo com a ordem(A) que está dentro de outro elemento
* :nth-last-child(A) --> seleciona o filho de trás para frente de acordo com o elemento pai

## Display flex (flex-box)
https://flexboxfroggy.com/
* Column (coluna)
* Row (linha)
* Dependem da direção que estão, column ou row
    * justify-content (eixo principal)
    * align-items (eixo secundário)

## TAG a
* Atributos
    * href="#" (link sem destino)
    * target= "_blank" (abre em nova guia)

## Unidades de Medida
* px = pontos na tela
* % = segue o tamanho do pai
* vh/vw/rem/em = segue o tamanho da janela
* Geralmente damos tamanhos fixos para o header e o footer

## Propriedades CSS
* flex-grow = representa a "força" que a tag selecionada vai ter no html, ou seja, qual o tamanho total que a tag vai ter
* gap = espaço entre as caixas

## Símbolos (HTML)
* Para usar um símbolo basta colocar o sinal "&" o conteúdo desejado e o ";" no fim. 

Ex: ``` &copy; ```, ``` &trade; ```, ``` &reg; ```...

## Imagens
https://unsplash.com/
https://www.pexels.com/

### Formatos
* JPEG/JPG (formato com alta compactação)
* PNG (formato que permite transparência)
* 1500 é o tamanho máximo de imagem adequado para um site
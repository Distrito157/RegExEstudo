# EXPRESSÕES REGULARES NO LINUX
Obs.: Nenhum dos vídeos abaixo são de minha autoria. Crédito dos vídeos para Boson Treinamentos.<br>
SITE PARA ESTUDO: https://www.regexpal.com/

- AULA-1: https://www.youtube.com/watch?v=31FgxWsRRMw   " . \ "
- AULA-2: https://www.youtube.com/watch?v=WDvHnq85rfE   " [ ] - Expressões POSIX ^ "

`primeiros conceitos:` caractere e metacaractere,
Caractere é um texto qualquer, uma letra, um número, símbolo que você pesquisa usando exp regular.
Metacaracteres são caracteres que possuem significado especial. Transformam caracteres literais
(comuns) em expressões de busca.

## São os seguintes:
\ . * + - { } [ ] ^ $ | ? ( ) : ! =

Os Metacaracteres podem ter mais de um significado, dependendo do contexto de uso.

Obs.: Aspas não são Metacaracteres.

## Caracter único .
O ponto representa qualquer Caracter único.

## Caracter de Escape
Trata-se de um metacaractere \ que indica a mudança no significado de outro caractere, transforma
um metacaractere em um literal comum.

## Classes ou conjuntos de caracteres:
- São listas de caracteres escritas dentro de colchetes [ ] e que servem para corresponder apenas um
dos caracteres listados.
- Permite selecionar um dos caracteres dentro dos colchetes, não importa a ordem.

## Expressões POSIX:
[[:alpha:]] - equivale a a-zA-z
[[:upper:]] - A-Z
[[:lower:]] - a-z
[[:digit:]] - 0-9
[[:alnum:]] - 0-9a-zA-Z
[[:space]] - espaços

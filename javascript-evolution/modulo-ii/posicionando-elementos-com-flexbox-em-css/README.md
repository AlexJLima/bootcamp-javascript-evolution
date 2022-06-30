![Logo do curso posicionando elementos com flex box em CSS](assets/flex-box-logo.png) 

# Posicionando elementos com Flexbox em CSS

Neste curso estou aprendendo sobre o modelo de layout flexbox do CSS. Em cada aula eu criei arquivos separados que implementam diferentes características desse modelo.

## Fudamentos do Flexbox - Parte 1

* `display: flex`

    O primeiro arquivo cria uma que implementa uma classe. Esta, por sua vez, possui a propriedade `display: flex`. Isso significa que qualquer tag que estiver dentro dessa div estará distruibuída automaticamente ao longo desse espaço, independentemente do tamanho da tela.

* `flex-direction`

    O segundo arquivo trabalha com a propriedade `flex-direction`. Para isso, foram criadas quatro classes para definir cada um dos quatros valores possíveis para essa propriedade: `row`, `row-reverse`, `column`, `column-reverse`. Para mostrar na prática o que cada um desses itens faz, foram criadas quatro listas que implementam as classes criadas.

* `flex-wrap`

    Essa propriedade impede que conteúdos dentro de uma div vazem para fora quando não couberem dentro desta. Quando ocorre essa situação, o `flex-wrap` reposiciona o conteúdo para cima ou para baixo, dependendo do valor que for passado para propriedade. Ele também reposiciona para esquerda ou para a direita, caso a propriedade `flex-direction` esteja com o valor `column`.

* `flex-flow`

    Ele é um atalho que permite alterar as propriedades `flex-direction` e `flex-wrap` ao mesmo tempo. Para isso basta adicionar os valores de cada uma na propriedades `flex-flow` separados por espaço, por exemplo: `flex-flow: row wrap`.

* `justify-content`

    Basicamente, ele oferece maneiras diferentes de reorganizar os itens dentro de uma div. O primeiro valor é o `flex-start`, ele posiciona os itens bem no começo da div. O `flex-end` faz o contrário, posiciona no final da div. O `center` apenas centraliza os itens mantendo-os juntos com o espaçamento original. O `space-between` distribuí os itens ao longo da div, porém, os que ficam na ponta permanecem nessa posição. Em outras palavras, ele coloca um espaçamento entre o item inicial e o item final. Por fim, temos o `space-around`, ele faz a mesma coisa do anterior só que tanto o primeiro quanto o segundo item recebem espaçamento, eles não ficam grudados nas bordas da div como aconteciam no `space-between`.

* `align-items`

    Uma das propriedades mais difíceis de entender, ela possui o mesmo propósito de reorganização dos itens dentro da div, entretanto ele apenas considera o eixo vertical como referência para essa reorganização. Ele possui os mesmos valores do `justify-content`.

* `align-content`

    Tive a mesma dificuldade da propriedade anterior, ela faz a mesma coisa do `align-items`, mas utilizando o eixo horizontal como referência.


![Logo do curso posicionando elementos com flex box em CSS](assets/flex-box-logo.png) 

# Posicionando elementos com Flexbox em CSS

Neste curso estou aprendendo sobre o modelo de layout flexbox do CSS. Em cada aula eu criei arquivos separados que implementam diferentes características desse modelo.

## Propriedades

* `display: flex`

    O primeiro arquivo cria uma `div` que implementa a classe `.flex`. Esta, por sua vez, possui a propriedade `display: flex`. Isso significa que qualquer tag que estiver dentro dessa `div` estará distruibuída automaticamente ao longo desse espaço, independentemente do tamanho da tela.

* `flex-direction`

    O segundo arquivo trabalha com a propriedade `flex-direction` em listas, cada classe implementa os quatros valores diferentes dessa propriedade: `row`, `row-reverse`, `column`, `column-reverse`. Para exemplificar cada um desses valores, foram criadas quatro listas que implementam cada uma dessas funcinalidades.

* `flex-wrap`

    Essa propriedade impede que conteúdos dentro de uma div vazem para fora quando não couberem dentro desta. Quando ocorre essa situação, o `flex-wrap` reposiciona o conteúdo para cima ou para baixo, dependendo do valor que for passado para propriedade. Ele também pode reposicionar para esquerda ou para a direita, caso a propriedade `flex-direction` esteja com o valor `column`.
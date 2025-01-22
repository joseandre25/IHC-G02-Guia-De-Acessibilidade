## Alto contraste e tamanho da fonte

Botões para alto contraste e ajuste do tamanho das letras, embora não sejam obrigatórios para garantir a acessibilidade, podem ser úteis para os usuários. Isso ocorre porque muitas pessoas com deficiência já utilizam essas funções diretamente em seus navegadores ou por meio de atalhos no teclado. No entanto, é fundamental que o site seja bem elaborado e compatível com essas ferramentas. Assim, esses botões podem oferecer mais conforto durante a navegação, apesar de não serem uma exigência


<div class="container">
  <button id="aumentar" onclick="aumentarFonte()">A+</button>
  <button id="diminuir" onclick="diminuirFonte()">A-</button>
</div>

<div class="text-parag">
<p id="texto">Este é um exemplo de texto que pode ter seu tamanho ajustado.</p>
</div>

<script>
  function aumentarFonte() {
    var texto = document.getElementById('texto');
    var style = window.getComputedStyle(texto, null).getPropertyValue('font-size');
    var fontSize = parseFloat(style);
    texto.style.fontSize = (fontSize + 2) + 'px';
  }

  function diminuirFonte() {
    var texto = document.getElementById('texto');
    var style = window.getComputedStyle(texto, null).getPropertyValue('font-size');
    var fontSize = parseFloat(style);
    texto.style.fontSize = (fontSize - 2) + 'px';
  }
</script>

<style>
  .text-parag{
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }

  #aumentar, #diminuir {
    font-size: 400%;
    margin: 10px;
  }

  #aumentar:hover, #diminuir:hover {
    color: blue;
    font-size: 425%;

  }
</style>

## Ampliação da tela

Ao aumentar a tela com o zoom do navegador em até 200%, o conteúdo precisa continuar claro e organizado, sem que nenhuma informação desapareça ou fique sobreposta.

## Áreas de clique

Os botões e áreas de clique de uma página devem ter um tamanho suficiente para que qualquer pessoa consiga usar com facilidade e segurança. Em computadores, o tamanho mínimo recomendado é de 24x24px, e em celulares é 48x48px. Mesmo que o ícone ou botão em si seja menor, como por exemplo 40px ou 24px de largura, a área que pode ser clicada deve ter pelo menos 48x48px para garantir que seja confortável de usar. Porém, não tão grandes a ponto de invadirem o espaço de outros botões ou elementos próximos. Ainda mais em telas menores para não ocorrer cliques acidentais.

## Contraste da cor

Botões para aumentar o contraste ou ajustar o tamanho das letras podem ser úteis para quem navega, mas não são obrigatórios. Isso porque muitas pessoas com deficiência já usam esses recursos diretamente no navegador ou por meio de atalhos no teclado. O importante é garantir que o site funcione bem com essas ferramentas.

## Design responsivo

O design responsivo é muito importante para a acessibilidade, pois permite que a interface se adapte às necessidades de quem está navegando. Por exemplo, se a pessoa prefere usar o celular na vertical ou horizontal, ou se precisa aumentar o tamanho das letras, o site se ajusta para atender essas preferências.
Uma dica é começar a criar o design para celular e, depois, ajustar para computadores. Isso facilita o desenvolvimento e garante que o conteúdo fique bem organizado em telas de todos os tamanhos.

## Foco visível

Outro ponto importante é garantir que o foco esteja visível na tela. O foco é como um destaque ao redor do elemento em que o usuário está interagindo, como uma borda ou moldura. Quando o foco não aparece ou simplesmente não existe, fica muito difícil navegar usando apenas o teclado.
Para resolver isso, é possível usar recursos visuais para mostrar claramente onde está o foco. Por exemplo, é comum criar um contorno ao redor do elemento que está selecionado, destacando-o para o usuário. Isso torna a navegação mais fluida e acessível.

## Navegação 100% por teclado

Todas as funções de uma página web precisam funcionar usando apenas o teclado. Por isso, é importante evitar efeitos visuais que dependem somente do movimento do mouse, como quando passamos o cursor sobre algo (*mouseover*) para revelar informações. Uma boa alternativa é fazer com que as ações também sejam ativadas com um clique, permitindo que pessoas que usam leitores de tela consigam acessar tudo usando o teclado.

Um exemplo comum são os submenus que aparecem apenas quando o mouse passa por cima. Nesses casos, é importante oferecer a opção de abrir e fechar estes submenus usando o teclado, garantindo que todos possam navegar sem dificuldades.

## Navegação em celular e computador

No Brasil, há mais celulares do que computadores, e muitas pessoas navegam por *notebooks* ou desktops sem encontrar problemas. Porém, ao acessar o mesmo conteúdo pelo celular, é possível que surjam barreiras, algo que não deveria ocorrer. A experiência de navegação acessível pode variar bastante dependendo do fabricante do celular ou do navegador utilizado.

## Pausar, parar ou ocultar conteúdo

Para conteúdos que se movem, como carrosseis, é essencial permitir que o usuário possa pausar, esconder ou parar. Movimentos automáticos sem controle podem prejudicar a experiência de pessoas com condições neurodiversas ou que usam leitores de tela. Isso acontece porque esses conteúdos podem gerar sobrecarga mental, distrair do restante da página ou dificultar a navegação.
Por isso, evite usar movimentos automáticos sempre que possível. Se for realmente necessário mantê-los, ofereça opções de pausar, reduzir o movimento, além de botões para avançar e voltar.


## Uso da cor

A escolha das cores de um site deve ser feita com cuidado, pois as pessoas enxergam as cores de formas diferentes. Algumas têm dificuldade em distinguir certas cores, como nos casos de daltonismo, em que a pessoa pode não enxergar vermelho, verde, azul ou, em alguns casos, nenhuma cor. Por isso, as cores podem ter um impacto muito grande na forma como essas pessoas entendem o conteúdo.
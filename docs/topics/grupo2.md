
<style>
  button:not(#aumentar):not(#diminuir) {
    border: 1px solid black;
    padding: 5px 10px;
    border-radius: 10px;
    background-color: #4051B5;
    color: white;
    font-size: 16px;
    cursor: pointer;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
    transition: background-color 0.3s, transform 0.3s;
  }
  button:not(#aumentar):not(#diminuir):hover {
    background-color: #0056b3;
    transform: scale(1.05);
  }
</style>
## 1. Semântica
 - [ ] Utilize as tags HTML corretamente, como `<header>`, `<footer>`, e `<main>`, para estruturar a página. Isso ajuda tecnologias assistivas a entenderem o página e a funcionarem de forma correta.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('semantica-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="semantica-conceito" style="display: none;">
O uso correto de tags semânticas permite que tecnologias assistivas, como leitores de tela  , interpretem melhor a estrutura da página. Isso beneficia usuários com deficiência visual, ajudando-os a navegar de maneira lógica e eficiente pelo conteúdo.<a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-1">[1]</a>.
</div>


## 2.Breadcrumbs
 - [ ] Inclua trilhas de navegação para que os usuários saibam onde estão no site e possam retornar facilmente às páginas anteriores.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('breadcrumb-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="breadcrumb-conceito" style="display: none;">
As trilhas de navegação orientam os usuários sobre sua posição dentro do site, possibilitando um retorno fácil às páginas anteriores. Esse recurso é especialmente útil para pessoas com dificuldades cognitivas ou para quem depende de uma navegação estruturada. <a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-2">[2]</a>.
</div>

## 3.Rótulos e Descrições de Botões e Links
 - [ ] Use textos descritivos nos botões e links, como “Enviar formulário” ao invés de “Clique aqui”. Assim, os usuários sabem exatamente a função do elemento.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('rotulo-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="rotulo-conceito" style="display: none;">
Textos descritivos tornam mais claro o propósito de botões e links, evitando ambiguidades como "Clique aqui". Isso facilita o uso por leitores de tela e melhora a experiência de navegação para todos, incluindo pessoas com deficiência visual ou motora. <a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-3">[3]</a>.
</div>

## 4.Textos Alternativos
 - [ ] Adicione descrições claras e objetivas às imagens por meio do atributo alt. Isso garante que pessoas com deficiência visual compreendam o conteúdo visual.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('alt-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="alt-conceito" style="display: none;">
O atributo alt permite que leitores de tela descrevam o conteúdo de imagens para usuários cegos ou com baixa visão. Imagens sem texto alternativo são inacessíveis para essas pessoas, deixando-as sem acesso a informações importantes. <a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-4">[4]</a>.
</div>

## 5.Textos em Imagens
 - [ ] Evite incluir textos importantes em imagens. Caso seja necessário, forneça uma alternativa textual para garantir acessibilidade.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('imagens-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="imagens-conceito" style="display: none;">
Incluir textos importantes em imagens pode impedir a acessibilidade, pois leitores de tela não conseguem interpretar texto dentro de imagens. Alternativas textuais são fundamentais para garantir que o conteúdo seja acessível a todos.<a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-5">[5]</a>.
</div>

## 6.CSS e Árvore de Acessibilidade
 - [ ] Configure o CSS de forma que ele respeite a hierarquia semântica do HTML. Isso mantém a página acessível para leitores de tela.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('css-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="css-conceito" style="display: none;">
Um CSS bem configurado que respeita a semântica HTML preserva a hierarquia visual e estrutural da página. Isso é crucial para usuários que dependem de leitores de tela ou outras tecnologias assistivas, garantindo que a navegação seja intuitiva. <a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-6">[6]</a>.
</div>

## 7.Atalhos de Navegação
 - [ ] Implemente atalhos de teclado para facilitar o acesso a áreas importantes da página, como menus ou campos de busca.

 <button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('atalhos-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="atalhos-conceito" style="display: none;">
 Atalhos de teclado tornam o site mais acessível para pessoas com deficiência motora ou que preferem navegar sem o uso de um mouse. Eles também agilizam a navegação para usuários avançados..<a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-7"/>[7]</a>.
</div>

## 8.Alturas
 - [ ] Certifique-se de que os elementos na página tenham altura suficiente para facilitar cliques e leitura, especialmente em dispositivos móveis.

 <button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('altura-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="altura-conceito" style="display: none;">
Garantir alturas adequadas para áreas clicáveis melhora a usabilidade em dispositivos móveis e para pessoas com dificuldade motora. Isso evita cliques acidentais e torna a interação com a página mais confortável.<a href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">Guia de Boas Práticas UK-BR</a> <a href="#referencia-8">[8]</a>.
</div>


## Referências
<a id="referencia-1" href="https://ceweb.br/projetos/bruk/guia-html/#introducao" target="_blank">1. CEWEB.br. BRUK - Guia HTML, seção: Semântica</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#introducao. Acesso em: 25 Jan. 2025.

<a id="referencia-2" href="https://ceweb.br/projetos/bruk/guia-html/#estrutura-basica-de-um-documento-html" target="_blank">2. CEWEB.br. BRUK - Guia HTML, seção: Semântica</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#estrutura-basica-de-um-documento-html. Acesso em: 25 Jan. 2025.

<a id="referencia-3" href="https://ceweb.br/projetos/bruk/guia-html/#uso-de-tags-sem%C3%A2nticas" target="_blank">3. CEWEB.br. BRUK - Guia HTML, seção: Semântica</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#uso-de-tags-sem%C3%A2nticas. Acesso em: 25 Jan. 2025.

<a id="referencia-4" href="https://ceweb.br/projetos/bruk/guia-html/#atributos-alt-em-imagens" target="_blank">4. CEWEB.br. BRUK - Guia HTML, seção: Execução</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#atributos-alt-em-imagens. Acesso em: 25 Jan. 2025.

<a id="referencia-5" href="https://ceweb.br/projetos/bruk/guia-html/#estrutura-e-hierarquia" target="_blank">5. CEWEB.br. BRUK - Guia HTML, seção: Cabeçalhos</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#estrutura-e-hierarquia. Acesso em: 25 Jan. 2025.

<a id="referencia-6" href="https://ceweb.br/projetos/bruk/guia-html/#praticas-de-acessibilidade" target="_blank">6. CEWEB.br. BRUK - Guia HTML, seção:CSS e a Árvore de Acessibilidade </a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#praticas-de-acessibilidade. Acesso em: 25 Jan. 2025.

<a id="referencia-7" href="https://ceweb.br/projetos/bruk/guia-html/#links-e-navegacao" target="_blank">7. CEWEB.br. BRUK - Guia HTML, seção: Atalhos de navegação</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#links-e-navegacao. Acesso em: 25 Jan. 2025.

<a id="referencia-8" href="https://ceweb.br/projetos/bruk/guia-html/#atalhos-de-teclado" target="_blank">8. CEWEB.br. BRUK - Guia HTML, seção: Altura</a>. Disponível em: https://ceweb.br/projetos/bruk/guia-html/#introducao. Acesso em: 25 Jan. 2025.

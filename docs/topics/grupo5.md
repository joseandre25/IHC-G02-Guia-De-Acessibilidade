# Guia de Acessibilidade 

## 1. Formulários 
- [ ] <b>Formularios identificados:</b> todo campo deve ter sua finalidade explicada
- [ ] <b>Explicar erros:</b> em caso de dados informados de forma incorreta, o erro deve ser explicado, alem de apontar o campo do qual o erro originou
- [ ] <b>Evitar retrabalho:</b> em caso de dados informados de forma incorreta, ao recarregar a página, os dados informados devem permanecer nos campos preenchidos

<style>
  .botao-conceito {
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
  .botao-conceito:hover {
    background-color: #0056b3;
    transform: scale(1.05);
  }
</style>

<button title="Conceito formulários" class="botao-conceito" onclick="let el = document.getElementById('formulários'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="formulários" style="display: none;">
Forulários devem ser de facil preenchimento e, no caso de erros, devem evitar retrabalho ao maximo e explicar a todo momento para o usuário o que aconteceu. <a href="#referencia-1">[1]</a>

</div>

---

## 2. Modais  
- [ ] <b>Tamanho de diálogos modais:</b> janelas de pop up de diálogos modais devem ter tamanho apropiado independente do tamanho da tela
- [ ] <b>Em telas menores:</b> devem cobrir toda a tela de modo a impedir interações acidentais com o resto da página 

<button title="Conceito modais" class="botao-conceito" onclick="let el = document.getElementById('Modais'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="Modais" style="display: none;">
As caixas de diálogos modais devem puxar o foco do usuario para si enquanto estiverem sendo usadas, devendo ser bloqueada a interação com o resto do site para evitar erros por parte do usuário. <a href="#referencia-2">[2]</a>
</div>

---

## 4. Wireframes 
- [ ] <b>Facilidade de navegação:</b> usuários devem navegar com facilidadde e facilmente saber onde estão a qualquer momento
- [ ] <b>Estrutura de páginas:</b> estrutura deve ser facilmente entendível para os usuários
- [ ] <b>Conteudos de importancia claros:</b> os conteudos mais relevantes devem ser facilmente reconhecíveis, especialmente elementos interativos
- [ ] <b>Mensagens de erro:</b> em casos de erro do sistema, deve ser especificado o que aconteceu para o usuário

<button title="Conceito wireframes" class="botao-conceito" onclick="let el = document.getElementById('Wireframes'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="Wireframes" style="display: none;">
O usuário deve ser capaz de se localizar dentro da página a qualquer momento e deve ser capaz de entender a ordem dos elementos e como facilmente chegar a onde ele quer acessar. <a href="#referencia-3">[3]</a>
</div>

---

## 4. Links e botões  
- [ ] <b>Links devem ser sinalizados:</b> deve ser obvio links clicáveis
- [ ] <b>Botões devem ter aparencia de clicaveis:</b> botões devem ser obvios, alem de seguirem um padrão para evitar confusão
- [ ] <b>tamanho de botões:</b> botões devem ter tamanho apropiado para serem clicados e ao mesmo tempo não cobrirem outros conteudos

<button title="Conceito links e botões" class="botao-conceito" onclick="let el = document.getElementById('Links'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="Links" style="display: none;">
Elementos interativos como links e botões devem ser destacados de forma sua funcionalidade estar aparente, alem de deverem ser padronizados para que o usuário sempre saiba o que esperar quando for interagir com algo. <a href="#referencia-4">[4]</a>
</div>

---

## 5. Pausar, parar ou ocultar conteúdo
- [ ] <b>Autoplay de mídia:</b> evitar usar mídia que comece automaticamente
- [ ] <b>Pausar mídia:</b> toda midia deve ser pausavel se possivel
- [ ] <b>Mutar mídia:</b> toda midia deve ser possivel de desligar o som
- [ ] <b>Evitar uso de mídia que segue o usuário:</b> evitar usar ou permitir que seja fechado

<button title="Conceito pausar, parar ou ocultar conteúdo" class="botao-conceito" onclick="let el = document.getElementById('Pausar'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="Pausar" style="display: none;">
Midias devem ser possiveis de desligar para evitar cansaço e sobreccarregamento sensorial, expecialmente para pessoas com problemas sensoriais e neurologicos, que são mais vulneraveis a isso. <a href="#referencia-5">[5]</a>
</div>

---

## Referências 

<a id="referencia-1" href="https://www.w3.org/WAI/tutorials/forms/" target="_blank">1. w3c</a>. Disponível em: https://www.w3.org/WAI/tutorials/forms/. Acesso em: 25 Jan. 2025.

<a id="referencia-2" href="https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/" target="_blank">2. w3c</a>. Disponível em: https://www.w3.org/WAI/ARIA/apg/patterns/dialog-modal/. Acesso em: 25 Jan. 2025.

<a id="referencia-3" href="https://accessibility.deque.com/applying-accessibility-heuristics-to-a-wireframe" target="_blank">3. deque</a>. Disponível em: https://accessibility.deque.com/applying-accessibility-heuristics-to-a-wireframe. Acesso em: 25 Jan. 2025.

<a id="referencia-4" href="https://www.w3.org/TR/WCAG21/" target="_blank">4. w3c</a>. Disponível em: https://www.w3.org/TR/WCAG21/. Acesso em: 25 Jan. 2025.

<a id="referencia-5" href="https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide.html" target="_blank">5. w3c</a>. Disponível em: https://www.w3.org/WAI/WCAG21/Understanding/pause-stop-hide.html. Acesso em: 25 Jan. 2025.
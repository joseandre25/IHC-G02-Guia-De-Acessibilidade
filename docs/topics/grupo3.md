# Guia de Acessibilidade 
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

## 1. Checklists 

- [ ] Listar critérios de acessibilidade baseados no WCAG
- [ ] Criar listas separadas para design, conteúdo e desenvolvimento.
- [ ] Revisar frequentemente para garantir atualizações.

<button title="Conceito Checklists" class="botao-conceito" onclick="let el = document.getElementById('checklists-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="checklists-conceito" style="display: none;">
Checklists são listas práticas que garantem que os critérios de acessibilidade sejam atendidos em cada etapa do desenvolvimento de um site ou aplicação, desde o design até a implementação final. Exemplos podem ser encontrados em projetos como o <a href="https://www.a11yproject.com/checklist/" target="_blank">A11Y Project</a> <a href="#referencia-1">[1]</a>.
</div>

---

## 2. Grupo de Teste 

- [ ] Formar grupo com PcD para testes reais.
- [ ] Variar deficiências representadas no grupo.
- [ ] Conduzir testes em dispositivos móveis e desktops.

<button title="Conceito Grupo de Teste" class="botao-conceito" onclick="let el = document.getElementById('grupo-teste-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="grupo-teste-conceito" style="display: none;">
Grupos de teste são compostos por pessoas, preferencialmente PcD, que avaliam a acessibilidade de sistemas. O envolvimento direto dessas pessoas promove feedbacks mais reais e eficazes. <a href="#referencia-2">[2]</a>
</div>

---

## 3. Testes Manuais e Automáticos 

- [ ] Usar ferramentas automáticas como o Lighthouse.
- [ ] Realizar testes manuais com leitores de tela.
- [ ] Validar navegação 100% por teclado.

<button title="Conceito Testes Manuais e Automáticos" class="botao-conceito" onclick="let el = document.getElementById('testes-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="testes-conceito" style="display: none;">
Testes automáticos identificam problemas gerais, enquanto os manuais detectam barreiras específicas e nuances que ferramentas não podem avaliar, como a experiência do usuário. <a href="#referencia-3">[3]</a>
</div>

---

## 4. Recursos de Acessibilidade 

- [ ] Incluir leitores de tela.
- [ ] Garantir suporte para contraste alto.
- [ ] Implementar redimensionamento de texto.

<button title="Conceito Recursos de Acessibilidade" class="botao-conceito" onclick="let el = document.getElementById('recursos-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="recursos-conceito" style="display: none;">
Recursos de acessibilidade incluem ferramentas e funcionalidades que ajudam PcD a interagir melhor com sistemas, como legendas em vídeos, leitores de tela e contraste ajustável. <a href="#referencia-4">[4]</a>
</div>

---

## 5. Campo de Busca 

- [ ] Prover função de busca visível.
- [ ] Implementar suporte a navegação por teclado.
- [ ] Garantir mensagens de erro claras para buscas inválidas.

<button title="Conceito Campo de Busca" class="botao-conceito" onclick="let el = document.getElementById('campo-busca-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="campo-busca-conceito" style="display: none;">
Campos de busca acessíveis permitem que usuários encontrem informações rapidamente, mesmo aqueles com baixa habilidade digital ou que usam tecnologias assistivas. <a href="#referencia-5">[5]</a>
</div>

---

## 6. Captchas 

- [ ] Evitar desafios exclusivamente visuais.
- [ ] Oferecer opções como perguntas simples.
- [ ] Garantir compatibilidade com leitores de tela.

<button title="Conceito Captchas" class="botao-conceito" onclick="let el = document.getElementById('captchas-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="captchas-conceito" style="display: none;">
Captchas frequentemente criam barreiras, especialmente para PcD. Métodos simples e alternativos, como perguntas textuais, são mais inclusivos. <a href="#referencia-6">[6]</a>
</div>

---

## 7. Página de Acessibilidade e Dúvidas Frequentes 

- [ ] Disponibilizar guia claro de acessibilidade.
- [ ] Incluir tópicos de perguntas frequentes.
- [ ] Atualizar constantemente com base no feedback.

<button title="Conceito Página de Acessibilidade" class="botao-conceito" onclick="let el = document.getElementById('pagina-acessibilidade-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="pagina-acessibilidade-conceito" style="display: none;">
Essas páginas orientam usuários sobre como usar as funcionalidades de acessibilidade do site, promovendo uma experiência mais independente e informada. <a href="#referencia-7">[7]</a>
</div>

---

## 8. Analfabetismo Digital 

- [ ] Usar linguagem simples em instruções.
- [ ] Adotar ícones ilustrativos ao lado de texto.
- [ ] Oferecer tutoriais básicos no site.

<button title="Conceito Analfabetismo Digital" class="botao-conceito" onclick="let el = document.getElementById('analfabetismo-digital-conceito'); el.style.display = el.style.display === 'none' ? 'block' : 'none';">
  Conceito 📖
</button>
<div id="analfabetismo-digital-conceito" style="display: none;">
Analfabetismo digital refere-se à dificuldade de usar tecnologias por falta de habilidade ou conhecimento. Criar interfaces intuitivas ajuda a reduzir essa barreira. <a href="#referencia-8">[8]</a>
</div>

## Referências

<a id="referencia-1" href="https://www.a11yproject.com/checklist/" target="_blank">1. W3C Web Accessibility Initiative. A11Y Project - Accessibility Checklist</a>. Disponível em: https://www.a11yproject.com/checklist/. Acesso em: 25 Jan. 2025.

<a id="referencia-2" href="https://mwpt.com.br/" target="_blank">2. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 6: Desenvolvimento, seção "Grupo de Teste"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

<a id="referencia-3" href="https://mwpt.com.br/" target="_blank">3. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 6: Desenvolvimento, seção "Testes Manuais e Automáticos"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

<a id="referencia-4" href="https://mwpt.com.br/" target="_blank">4. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 7: Design, seção "Recursos de Acessibilidade"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

<a id="referencia-5" href="https://mwpt.com.br/" target="_blank">5. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 6: Desenvolvimento, seção "Campo de Busca"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

<a id="referencia-6" href="https://mwpt.com.br/" target="_blank">6. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 6: Desenvolvimento, seção "Captchas"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

<a id="referencia-7" href="https://mwpt.com.br/" target="_blank">7. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 7: Design, seção "Página de Acessibilidade e Dúvidas Frequentes"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

<a id="referencia-8" href="https://mwpt.com.br/" target="_blank">8. Movimento Web para Todos. Guia de Boas Práticas para Acessibilidade Digital, capítulo 6: Desenvolvimento, seção "Analfabetismo Digital"</a>. Disponível em: https://mwpt.com.br/. Acesso em: 25 Jan. 2025.

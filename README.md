# FEZ Lamp Login Panel

<p align="center">
  <img alt="Status" src="https://img.shields.io/badge/status-conclu%C3%ADdo-22c55e?style=for-the-badge" />
  <img alt="Tech" src="https://img.shields.io/badge/HTML-CSS-JS-0ea5e9?style=for-the-badge" />
  <img alt="UI" src="https://img.shields.io/badge/UI-Interativa-6366f1?style=for-the-badge" />
</p>

Uma tela de login **interativa e imersiva** com estética noturna, onde uma luminaria em SVG controla a iluminacao da interface ao puxar a corda.

## Preview

Projeto focado em:
- Experiencia visual moderna com atmosfera "night studio"
- Microinteracoes fluidas e responsivas
- Interface de login com visual premium

## Destaques

- Luminaria SVG com variaveis CSS dinamicas (`--on`) para ligar/desligar ambiente
- Corda com fisica de arraste (Bezier + easing elastico/bounce)
- Balanco idle automatico da corda quando a luz esta desligada
- Efeito sonoro de clique ao alternar a luz (`click-sound.mp3`)
- Campo de senha com alternancia mostrar/ocultar
- Feedback visual no botao de entrada (erro e sucesso)
- Layout responsivo para desktop e mobile

## Tecnologias

- HTML5
- CSS3 (animacoes, gradientes, variaveis CSS)
- JavaScript Vanilla
- SVG (componente da luminaria)

## Como Executar

1. Abra a pasta `FEZ-Lamp-Login-Panel`.
2. Entre em `Abajur`.
3. Abra o arquivo `index.html` no navegador.

Opcional (recomendado para audio/recursos locais):
- Rode com servidor local (ex.: Live Server no VS Code).

## Interacoes

- **Puxar a corda:** liga/desliga a luminaria e ativa o destaque do cartao.
- **Botao do olho:** alterna visibilidade da senha.
- **Entrar sem dados:** aplica animacao de erro.
- **Entrar com dados preenchidos:** mostra estado de carregamento e sucesso.

## Autor

Projeto feito por **Isaléo Guimarães**.

---

Se quiser, eu tambem posso criar uma versao com GIF de demonstracao e secao de deploy (GitHub Pages) para deixar o repositorio ainda mais profissional.

# Arena Sport

Loja virtual fictícia de tênis, camisetas e shorts esportivos. Projeto acadêmico de web design com foco em acessibilidade (WCAG), heurísticas de Nielsen, UI/UX e psicologia das cores.

**Site:** https://brunoeng-061.github.io/arena-sport/

## O que o site tem

- Carrossel de ofertas com pausa e setas
- Busca e abas de categoria (Tênis, Camisetas, Shorts)
- Cartões de produto e cartões explicativos
- Depoimentos
- Página de login com validação
- Formulário de contato
- Modo claro e escuro
- Ajuste do tamanho da fonte (A− e A+)
- Rodapé

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis, grid, flexbox, media queries)
- JavaScript puro, sem frameworks
- Google Fonts: Barlow e Barlow Condensed

## Como rodar

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno.

Não precisa de servidor nem de instalação.

## Passo a passo da construção

1. **Tema e público:** loja esportiva para corrida, academia e futebol.
2. **Paleta:** azul (confiança), amarelo (energia) e neutros. Contraste calculado antes de aplicar, com mínimo de 4,5:1.
3. **Cores como variáveis CSS:** `--bg`, `--sf`, `--tx`, `--pr`, `--ac` na raiz da página.
4. **Modo escuro:** as mesmas variáveis com novos valores, usando `prefers-color-scheme` e o atributo `data-theme`.
5. **Estrutura HTML:** link para pular ao conteúdo, cabeçalho, seções principais e rodapé.
6. **Cabeçalho fixo** com navegação e barra de acessibilidade.
7. **Carrossel:** 3 slides, setas, pontos, botão de pausa e respeito à preferência por menos movimento.
8. **Produtos:** lista em JavaScript, cartões gerados na tela, filtro por aba e busca por texto.
9. **Cartões explicativos e depoimentos.**
10. **Formulários** de login e contato, com validação e mensagens de status.
11. **Acessibilidade:** foco visível, rótulos nos campos, `aria-pressed`, `aria-selected`, botões de 44 px e fonte ajustável.
12. **Persistência:** tema e tamanho da fonte salvos no navegador.
13. **Humanização:** textos em tom de conversa e seção de depoimentos.
14. **Testes:** cálculo de contraste, telas larga e estreita e navegação só com teclado.

## Versões

- **v1.0:** estrutura, tema claro/escuro, carrossel, produtos, login e contato
- **v1.1:** textos humanizados e depoimentos

## Melhorias futuras

- Setas do teclado nas abas, seguindo o padrão WAI-ARIA
- Fotos reais dos produtos, com texto alternativo
- Carrinho e login reais, com back-end
- Testes com leitor de tela e auditoria com Lighthouse ou axe

## Aviso

Marca, produtos, preços e depoimentos são fictícios.

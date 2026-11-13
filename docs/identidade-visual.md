# Identidade visual — Tramma Inteligência Digital

## Direção visual
A interface combina tecnologia e inteligência digital com a assinatura visual da Tramma. A base permanece escura, com azul elétrico e roxo neon como cores tecnológicas e terracota como acento institucional reconhecível.

## Paleta de marca e interface

| Papel | Cor | HEX |
|---|---|---|
| Fundo principal | Preto azulado | `#030817` |
| Superfícies | Azul-marinho profundo | `#07142B` |
| Azul tecnológico | Azul elétrico | `#147BFF` |
| Roxo de apoio | Roxo neon | `#8B2CFF` |
| Terracota Tramma | Cor institucional | `#C24724` |
| Terracota luminoso | Realce e brilho | `#FF6A32` |
| Texto principal | Branco frio | `#F4F7FF` |
| Texto secundário | Cinza azulado | `#AAB8D0` |
| Indicador positivo | Verde | `#25D978` |

Os tons terracota são referências digitais aproximadas da identidade visual apresentada. Se houver um manual oficial com códigos HEX/RGB, ele prevalece sobre esta aproximação.

## Aplicação do terracota

O terracota deve ser visível na interface sem competir com o azul e o roxo:

- **Menu selecionado:** contorno terracota, ícone terracota e brilho externo suave; manter o fundo escuro.
- **Botão principal/CTA:** preenchimento terracota Tramma, texto branco e hover em terracota luminoso.
- **Ícones de marca:** terracota em ícones de destaque, sem colorir todos os ícones da interface.
- **Cards:** usar filete ou pequeno detalhe terracota em cards prioritários; manter bordas azuis nos painéis de dados.
- **Gráficos:** reservar terracota para uma série, meta ou ponto de atenção; azul e roxo continuam nas demais séries.
- **Iluminação:** reflexos terracota localizados em divisórias, cantos e elementos ativos, inspirados na imagem de referência.
- **Logotipo:** utilizar o arquivo original, preservando desenho, proporções, tipografia e cores.

## Hierarquia de uso
1. Preto azulado e azul-marinho: estrutura e superfícies dominantes.
2. Azul elétrico: dados, links, indicadores e elementos de tecnologia.
3. Roxo neon: categorias secundárias e elementos complementares.
4. Terracota Tramma: identidade, ações primárias e estados selecionados.
5. Verde: estados de sucesso e crescimento, não como cor institucional.

Evitar aplicar brilho em todos os componentes simultaneamente. O terracota deve funcionar como assinatura visual e guia de atenção.

## Tokens CSS

Os tokens estão definidos em `src/styles/brand-tokens.css`. Componentes devem consumir os tokens, evitando valores de cor soltos e inconsistentes.

## Responsividade e acessibilidade
Manter contraste legível, foco visível e estados hover/active/focus consistentes em desktop e dispositivos móveis. Não usar apenas a cor para comunicar sucesso, erro ou seleção.

# Identidade visual — Tramma Inteligência Digital

## Direção visual

A interface deve transmitir inteligência, tecnologia e sofisticação sem perder o vínculo visual com a marca Tramma. A referência aprovada combina uma base escura com azul elétrico, roxo neon e acentos terracota.

## Paleta de cores

| Papel | Cor | HEX |
|---|---|---|
| Fundo principal | Preto azulado | `#030817` |
| Superfícies e painéis | Azul-marinho profundo | `#07142B` |
| Azul tecnológico | Azul elétrico | `#147BFF` |
| Roxo de apoio | Roxo neon | `#8B2CFF` |
| Terracota institucional | Terracota Tramma | `#C24724` |
| Terracota luminoso | Laranja terracota | `#FF6A32` |
| Texto principal | Branco frio | `#F4F7FF` |
| Texto secundário | Cinza azulado | `#AAB8D0` |
| Indicador positivo | Verde | `#25D978` |

> O tom `#C24724` foi extraído visualmente da referência enviada. O tom `#FF6A32` funciona como variação luminosa para estados ativos e efeitos de brilho.

## Como introduzir o terracota

O terracota deve aparecer como acento institucional recorrente, em equilíbrio com o azul e o roxo:

- **Navegação ativa:** borda terracota iluminada, fundo em degradê terracota escuro e ícone em laranja.
- **Ações principais:** botões de destaque com terracota, brilho suave e texto branco; reservar o azul para ações secundárias.
- **Cards e painéis:** filetes, cantos ou bordas com gradiente azul–terracota, sem contornar todos os painéis com a mesma intensidade.
- **Ícones e indicadores:** terracota em ícones de seção, alertas positivos de marca e elementos selecionados.
- **Gráficos:** usar terracota para uma série ou ponto de destaque, mantendo azul e roxo nas demais séries.
- **Efeitos de luz:** reflexos terracota discretos em bases, divisórias e áreas de foco, como na imagem de referência.
- **Logotipo:** preservar integralmente o arquivo original, sem redesenhar, deformar ou alterar proporções.

## Regras de equilíbrio

1. O preto azulado e o azul-marinho continuam dominando o espaço.
2. Azul elétrico comunica tecnologia e dados; roxo diferencia recursos e categorias.
3. Terracota deve reforçar a assinatura Tramma e destacar interações importantes, não dominar a interface.
4. Evitar brilho intenso em todos os elementos ao mesmo tempo; priorizar hierarquia visual e legibilidade.
5. Garantir contraste adequado e estados de foco acessíveis em desktop e dispositivos móveis.

## Tokens CSS iniciais

```css
:root {
  --color-bg: #030817;
  --color-surface: #07142B;
  --color-blue: #147BFF;
  --color-purple: #8B2CFF;
  --color-terracotta: #C24724;
  --color-terracotta-glow: #FF6A32;
  --color-text: #F4F7FF;
  --color-text-muted: #AAB8D0;
  --color-success: #25D978;

  --glow-terracotta: 0 0 18px rgb(255 106 50 / 28%);
  --glow-blue: 0 0 18px rgb(20 123 255 / 28%);
}
```

## Referência de aplicação

A imagem enviada pelo usuário é a referência visual para o equilíbrio entre painéis escuros, contornos azuis, roxos e acentos terracota. Esta especificação documenta a direção visual para ser aplicada aos componentes da interface na etapa de implementação.

# Design Tokens Todá Inventividade

Tokens de identidade visual da agência Todá Inventividade — usados como
assinatura da agência nos relatórios mensais de performance de redes sociais
de todos os shoppings da carteira Gazit Brasil.

**Importante:** isto não é um design system substituto do da Gazit. É uma
camada separada, aplicada por cima do design system Gazit — a Gazit segue
sendo a base visual do relatório inteiro; a Todá aparece só como assinatura
(logo em todos os slides + bloco de considerações finais no fechamento).

## Paleta de marca

| Nome | Hex | Uso |
|---|---|---|
| Roxo escuro | `#170141` | Cor base; fundo do círculo do logo; palavra "inventividade" |
| Rosa/pink | `#ff0060` | Cor de destaque; palavra "todá" no logo; títulos e elementos de assinatura |

## Tipografia

- **Run** — textos curtos e títulos
- **Montserrat Bold** — números, textos longos e acentuação

## Logo — variantes e regra de aplicação

| Variante | Arquivo | Quando usar |
|---|---|---|
| Colorido | `Todá_Logo_-_Colorido_1.png` | Fundo branco (aplicação padrão, dá maior leitura) |
| Branco | `Todá_Logo_-_Branco.png` | Fundo colorido (ex.: bloco em azul-marinho ou dourado da Gazit) |
| Preto | — (sem arquivo próprio ainda) | Caso extremo: fundo claro que não é branco puro, mas onde o colorido perde leitura |

## Onde entra no relatório mensal

- **Todo slide**: logo da Todá (na versão correta pro fundo daquele slide) no
  canto superior direito
- **Página 11 — "Considerações finais da agência"**: assinatura completa da
  Todá, com leitura estratégica do mês e recomendações para o próximo ciclo

## Uso

Arquivo `tokens-toda-inventividade.json` traz os mesmos dados acima em
formato estruturado, para consumo automatizado na geração dos relatórios
(scripts, templates de slide, etc.). Este README serve de referência rápida
para quem for aplicar a identidade manualmente ou revisar as regras.
# Observações sobre elementos HTML

## 1. Elementos Block e Inline

| Elemento | Block ou inline? | Observação |
|---|---|---|
| h1/h2/h3 | Block | O elemento h1, h2, h3 ocupa uma linha inteira por padrão, pois representa um título, seção ou subseção principal da página. |
| p | Block | O elemento p ocupa uma linha inteira por padrão, pois representa um bloco de texto ou parágrafo. |
| ul/ol | Block | O elemento ul ocupa uma área própria na página porque representa uma lista ou uma lista ordenada de itens. |
| a | Inline | O link ocupa apenas o espaço necessário para o seu texto e pode aparecer no meio de uma frase. |
| strong | Inline | O elemento strong ocupa apenas o espaço do conteúdo marcado e pode aparecer dentro de um parágrafo. |
| img | Inline | A imagem é um elemento inline por padrão e ocupa o espaço correspondente à própria imagem. |

## 2. Experimento com strong e p

### Dois elementos strong

Quando dois elementos `strong` são colocados lado a lado dentro do mesmo parágrafo, eles permanecem na mesma linha, desde que exista espaço suficiente.

Isso acontece porque o elemento `strong` possui comportamento **inline** por padrão.

### Dois elementos p

Quando dois elementos `p` são colocados um depois do outro, eles aparecem em blocos separados, normalmente um abaixo do outro.

Isso acontece porque o elemento `p` possui comportamento **block** por padrão.


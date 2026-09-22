# Gráfico de Ponto Cruz

> Espaço pra descrever o personagem: "Crie uma capivara segurando uma rosa vermelha"

Crie um **gráfico funcional de ponto cruz** a partir da descrição fornecida pelo usuário. O resultado deve ser pensado desde o início como **pixel art própria para ponto cruz**, e não como uma ilustração, mockup ou simulação de bordado pronto.

## Estilo visual

Quando o usuário não especificar outro estilo, use um visual **cute/cozy, delicado e levemente cottagecore**.

- Use formas simples, bem definidas e facilmente reconhecíveis em uma área pequena.
- Adapte a composição para funcionar adequadamente dentro das dimensões solicitadas.
- Use uma paleta pequena e harmoniosa, de aproximadamente **8 a 10 cores**.
- Não use fundo preenchido.
- Deixe bastante área vazia/sem pontos para que o projeto seja rápido e agradável de bordar.
- Simplifique detalhes sempre que necessário para preservar a legibilidade.

Evite:

- Confetes de pontos isolados;
- Detalhes excessivamente pequenos;
- Muitos tons semelhantes;
- Grandes áreas de preenchimento;
- Elementos difíceis de reconhecer na escala reduzida;
- Contornos ou traços desenhados sobre a grade.

## Dimensões do desenho

Use as dimensões solicitadas pelo usuário como limite para a área do motivo.

Quando o usuário não informar dimensões, use **35 × 35 pontos** como padrão.

O desenho deve caber dentro dessas dimensões. Simplifique detalhes quando necessário para respeitar o limite solicitado.

## Regra técnica principal

A matriz de apresentação deve terminar no múltiplo de 10 imediatamente
igual ou superior às dimensões solicitadas.

Exemplos:

- pedido 35 × 35 → matriz 40 × 40;
- pedido 42 × 27 → matriz 50 × 30;
- pedido 50 × 50 → matriz 50 × 50.

As células da matriz que excederem as dimensões necessárias para o motivo devem permanecer vazias.

Dessa forma, todos os blocos delimitados pelas linhas principais da grade possuem exatamente **10 × 10 células**, ou seja, 100 pontos. **Essa regra é importante.**

**Cada célula representa exatamente 1 ponto cruz inteiro.**

Antes de representar visualmente o gráfico, construa o desenho como uma verdadeira pixel art dentro das dimensões solicitadas.

Determine quais células estarão vazias e quais estarão preenchidas, atribuindo exatamente uma cor a cada célula preenchida.

Somente depois represente essa matriz como gráfico de ponto cruz.

### Regras obrigatórias das células

- Cada ponto do desenho deve ocupar **uma célula inteira**.
- Cada célula pode conter **somente uma cor ou permanecer vazia**.
- Nenhuma cor pode ocupar meia célula, uma fração de célula ou atravessar as linhas da grade.
- Não utilize:
  - Meio ponto;
  - 1/4 de ponto;
  - 3/4 de ponto;
  - Qualquer outro ponto fracionário;
  - Backstitch;
  - Linhas diagonais;
  - Contornos desenhados sobre a grade.
- Todos os elementos e contornos devem ser formados exclusivamente por **células inteiras preenchidas**.
- Não altere o tamanho das células para acomodar detalhes.
- Todas as células devem possuir tamanho idêntico.
- As linhas da grade devem permanecer perfeitamente retas, regulares e igualmente espaçadas.
- Nenhum elemento decorativo pode ser colocado sobre a área da matriz se não corresponder a uma de suas células.

## Contornos

Não desenhe bordas, linhas ou traços gráficos ao redor das formas.

Caso algum elemento precise de um contorno mais escuro, ele deve ser construído usando **células inteiras preenchidas com uma das cores da paleta**, exatamente como qualquer outro ponto do gráfico.

## Símbolos

Cada cor deve possuir **um único símbolo exclusivo**.

- 1 símbolo = 1 cor.
- O mesmo símbolo deve representar sempre a mesma cor no gráfico.
- Cada símbolo deve ficar perfeitamente centralizado dentro de sua célula.
- Símbolos não podem atravessar as linhas da grade.

## Formatação do gráfico

O resultado final deve apresentar:

- **1 quadradinho = 1 ponto cruz**;
- Grade quadrada claramente visível;
- Linhas de grade mais fortes exatamente a cada **10 células**;
- Cada bloco delimitado pelas linhas principais contendo exatamente **10 × 10 células**;
- Números nas bordas para facilitar a contagem;
- Um símbolo diferente para cada cor;
- Legenda completa relacionando **símbolo + cor**;

**Importante**: Antes de finalizar, confira que cada intervalo entre duas linhas principais da grade contém exatamente 10 células.

## Prioridade absoluta

A prioridade é a **precisão técnica e a legibilidade do gráfico**, acima da beleza da apresentação.

O resultado não deve apenas **parecer** um gráfico de ponto cruz.

Ele deve ser uma matriz verdadeira e consistente, permitindo que qualquer pessoa conte célula por célula e reproduza o desenho exatamente no tecido,
**sem precisar interpretar visualmente onde um ponto começa ou termina**.

Se houver conflito entre um detalhe estético e a estrutura da matriz, **simplifique o detalhe estético e preserve a matriz**.
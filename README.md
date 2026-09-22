# 🧵 Gerador de Gráficos de Ponto Cruz

Um prompt para transformar descrições curtas em gráficos de ponto cruz. O desenho é criado como pixel art: cada quadradinho da grade representa um ponto cruz inteiro.

<p align="center">
  <img src="./examples/porquinho-natal.png" alt="Gráfico de um porquinho com gorro de Natal e girassol" width="480">
</p>

<p align="center"><em>Exemplo: “Crie um porquinho fofo usando um gorrinho vermelho e segurando um girassol”.</em></p>

## 🧶 Como usar

1. Abra o [`PROMPT.md`](./PROMPT.md).
2. No início do arquivo, troque a descrição após **“Espaço pra descrever o personagem”** pelo desenho que deseja criar. Por exemplo: `Crie uma capivara segurando uma rosa vermelha`.
3. Copie o conteúdo do arquivo para uma ferramenta de IA capaz de gerar imagens e peça o gráfico.
4. Antes de bordar, confira se a grade, os símbolos e a legenda correspondem entre si.

### O que conferir no resultado

- Cada célula preenchida corresponde a **um ponto cruz inteiro** e contém apenas uma cor.
- A grade tem linhas mais fortes a cada **10 células** e números nas bordas para facilitar a contagem.
- Cada cor tem um símbolo próprio, identificado na legenda.
- O desenho cabe nas dimensões pedidas, mesmo que a grade se estenda até o próximo múltiplo de 10.

## ✨ Mais exemplos

<p align="center">
  <img src="./examples/patinho-bruxinha.png" alt="Gráfico de um patinho com avental e chapéu de bruxa" width="480">
</p>

<p align="center"><em>Exemplo: “Crie um patinho amarelo com um avental e um chapéu de bruxa roxo”.</em></p>

<p align="center">
  <img src="./examples/capivara-com-rosa.png" alt="Versão ajustada do gráfico da capivara, com os pontos preenchidos corretamente" width="480">
</p>

<p align="center"><em>Exemplo: “Crie uma capivara segurando uma rosa vermelha”.</em></p>


## ⚠️ Atenção
Às vezes, a IA não preenche todos os pontos corretamente. Nesse caso, basta pedir que ela ajuste o gráfico.

<p align="center">
  <img src="./examples/capivara-ruim.png" alt="Primeira versão do gráfico da capivara, com alguns pontos sem preenchimento" width="360">
  <img src="./examples/capivara-com-rosa.png" alt="Versão ajustada do gráfico da capivara, com os pontos preenchidos corretamente" width="360">
</p>

<p align="center"><em>Exemplo: "Ajuste alguns pontos que não estão ocupando o quadradinho inteiro."</em></p>

## 🌱 Status

Este projeto ainda está em experimentação. Gráficos gerados por IA podem apresentar erros na contagem de células, na correspondência entre símbolos
e cores ou na legenda. **Confira o gráfico ponto a ponto antes de iniciar 
um bordado definitivo.**

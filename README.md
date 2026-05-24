# 🌍 Mundo do Dinheiro

<p align="center">
  <img src="image.png" alt="Capa do Jogo Mundo do Dinheiro" width="400">
</p>

Um minijogo educativo e interativo criado para ensinar os conceitos básicos da **Macroeconomia Brasileira** (Inflação, Câmbio e Taxa SELIC) de forma divertida e prática, direto no navegador.

## 🎮 Jogue Agora

Para jogar, basta abrir o arquivo `mundo-do-dinheiro.html` em qualquer navegador moderno. Não é necessário instalar nenhum servidor local ou dependência!

## ✨ Funcionalidades

- **Múltiplas Fases de Aprendizado:**
  - 📈 **Inflação:** Um mini-desafio sobre oferta, demanda e perda de poder de compra.
  - 💵 **Câmbio:** Um simulador onde você atua como um importador tendo que lidar com as oscilações do Dólar.
  - 🏦 **SELIC:** O "termostato" da economia. Aprenda como o Banco Central controla a inflação através da taxa de juros básica.
  - 🔗 **Conexão:** Como todos os conceitos se amarram na vida real.
- **Gráficos em Alta Resolução:** UI polida, desenhada usando vetores do Canvas 2D nativo e formatada com CSS moderno.
- **Trilha Sonora Procedural:** Uma versão em 8-bits da música **"Pedrada" do Chico César** gerada totalmente em código através da Web Audio API (sem uso de arquivos mp3).
- **Acessibilidade Mobile:** Desenvolvido com responsividade em mente, suporta eventos de toque (`touch-action`) e adapta-se a qualquer tela (iOS e Android).
- **Sistema de Progresso:** Salva o avanço do jogador e as estrelas obtidas usando `localStorage`.

## 🛠️ Tecnologias Utilizadas

- **[Phaser 3](https://phaser.io/)** - Motor gráfico (Game Engine) rodando em modo Canvas para garantir anti-aliasing perfeito em todas as plataformas.
- **HTML5 & CSS3** - Estrutura e estilização externa, com layout responsivo (`max-width`, `vh/vw` limits) e gradientes complexos.
- **Web Audio API** - Para geração de som (efeitos sonoros e música de fundo procedurais).
- **Vanilla JavaScript** - Toda a lógica e gerenciamento de estado construída sem frameworks de terceiros.

## 🎵 Sobre a Música de Fundo

A música de fundo é um "Reggae Skank" gerado proceduralmente no código. 
- Baixo e Acordes reproduzem a harmonia: `Bb - Gm - Eb - Cm7 - F - Bb`
- A melodia principal e a oitava cantam no ritmo exato da letra.

## 💻 Contribuição

Sinta-se à vontade para fazer um *fork* do repositório, propor novos mini-jogos (ex: Taxa de Desemprego, Tesouro Direto, etc.) e abrir *Pull Requests*!

1. Faça um Fork do projeto
2. Crie uma branch para a sua feature (`git checkout -b feature/NovoConceito`)
3. Faça o commit das suas mudanças (`git commit -m 'feat: adiciona fase sobre PIB'`)
4. Faça o push para a branch (`git push origin feature/NovoConceito`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é de código aberto e possui licença MIT. Pode usar, modificar e distribuir à vontade!

---
layout: default
title: Chess Games
permalink: "/chess_games/"
---

## Chess Games

Here are some annotated chess games in PGN format:


<script src="https://cdnjs.cloudflare.com/ajax/libs/chessboard.js/1.0.0/chessboard.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/chess.js/1.0.0/chess.min.js"></script>
<script>
document.addEventListener("DOMContentLoaded", function () {
  const pgnElement = document.querySelector("pre>code");
  const pgnText = pgnElement.textContent;
  const game = new Chess();
  const gameMoves = pgnText.split("\n").filter(Boolean);

  for (const move of gameMoves) {
    game.move(move);
  }

  const board = Chessboard("board", {
    position: game.fen(),
    orientation: "white",
  });
});
</script>

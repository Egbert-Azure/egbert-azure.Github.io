---
layout: default
title: Chess Games
permalink: "/chess_games/"
---

## Chess Games

Here are some annotated chess games in PGN format:

```pgn
[Event "Annotated Game 1"]
[Site "Location"]
[Date "2023-08-06"]
[Round "1"]
[White "Player A"]
[Black "Player B"]
[Result "1-0"]

1. e4 e5
2. Nf3 Nc6
3. Bb5 a6
4. Ba4 Nf6
5. O-O Be7
6. Re1 b5
7. Bb3 d6
8. c3 O-O
9. h3 Nb8
10. d4 Nbd7
11. Nbd2 Bb7
12. Bc2 Re8
13. Nf1 Bf8
14. Ng3 g6
15. a4 c5
16. d5 c4
17. Bg5 Nc5
18. Nh2 Be7
19. Be3 Nfd7
20. Ng4 Bg5
21. Qf3 Bxe3
22. Qxe3 h5
23. Nh2 Qf6
24. Ne2 Nb6
25. a5 Nbd7
26. Rf1 Qg7
27. g4 Nf6
28. f3 Bc8
29. Kh1 Ra7
30. Rf2 Rae7
31. Rg1 Qh8
32. Rfg2 Kf8
33. Nf1 hxg4
34. hxg4 Qh7
35. Rh2 Qg7
36. Nfg3 Rc7
37. Nf5 Bxf5
38. gxf5 Ke7
39. fxg6 fxg6
40. Rh6 Rh8
41. Rxh8 Qxh8+
42. Kg2 Nh5
43. Kf2 Kd8
44. Qg5+ Kc8
45. Qxg6 Kb7
46. Rh1 Rh7
47. Qxd6 Nd3+
48. Bxd3 cxd3
49. Qb6+ Kc8
50. Qxa6+ Kb8
51. Qxb5+ Ka8
52. Qa6+ Kb8
53. Qxd3 Qf8
54. Qb5+ Ka8
55. Qc6+ Kb8
56. Qb6+ Ka8
57. a6 Nf6
58. Qc6+ Kb8
59. Rxh7 Nxh7
60. d6 Qf7
61. d7 Qxd7
62. Qxd7 Nf6
63. Qb7# 1-0

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
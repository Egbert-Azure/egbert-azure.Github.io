---
layout: default
title: Chess Games
permalink: "/chess_games/"
---

## Chessboard Example

Here's a simple example of a chessboard using Chessboard.js:

<div id="board" style="width: 400px;"></div>

<script>
// Add Chessboard.js script
var board = Chessboard("board", "start");
</script>

## Embedded Chess Game

<div style="display: flex; justify-content: center;">
  <iframe style="border: 0;" width="900px" height="600px" src="https://share.chessbase.com/SharedGames/frame/?p=D5xLg9gaS734iSy+vMBkEtr9n5Mj+sxY+ZACRCBXPNmndNFxyWV6+1u444th7DxV"></iframe>
</div>

## ChessBase PGN Viewer

You can use the ChessBase PGN viewer to display chess games as well:

<link rel="stylesheet" type="text/css" href="https://pgn.chessbase.com/CBReplay.css"/>
<script src="https://pgn.chessbase.com/jquery-3.0.0.min.js"></script>
<script src="https://pgn.chessbase.com/cbreplay.js" type="text/javascript"></script>

<div class="cbreplay" data-url="https://pgn.chessbase.com/your-pgn-file.pgn"></div>

<div class="cbreplay">
[Event "World Championship 28th"]
[White "Spassky, Boris V"]
[Black "Fischer, Robert James"]
[Site "Reykjavik"]
[Result "1–0"]
[Date "1972.08.06"]
[WhiteElo "2660"]
[BlackElo "2785"]

1. e4 c5 2. Nf3 d6 3. d4 cxd4 4. Nxd4 Nf6 5. Nc3 a6 6. Bg5 e6 7. f4 Qb6 8. Qd2 Qxb2 9. Nb3 Qa3 10. Bxf6 gxf6 11. Be2 h5 12. 0-0 Nc6 13. Kh1 Bd7 14. Nb1 Qb4 15. Qe3 d5 16. exd5 Ne7 17. c4 Nf5 18. Qd3 h4 19. Bg4 Nd6 20. N1d2 f5 21. a3 Qb6 22. c5 Qb5 23. Qc3 fxg4 24. a4 h3 25. axb5 hxg2+ 26. Kxg2 Rh3 27. Qf6 Nf5 28. c6 Bc8 29. dxe6 fxe6 30. Rfe1 Be7 31. Rxe6
</div>

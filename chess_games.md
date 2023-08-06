---
layout: default
title: Chess Games
permalink: "/chess_games/"
---
<!DOCTYPE html>
<html>
  <head>
    <title>Chess</title>
    <link rel="stylesheet" href="assets/css/chessboard-1.0.0.min.css">
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="assets/chessboard-1.0.0.min.js"></script>
  </head>
  <body>
    <div id="board1" style="width: 400px"></div>
    <script>
        var board1 = ChessBoard('board1', 'start');
    </script>
  </body>
</html>

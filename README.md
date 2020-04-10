# gridmap
2d grid shader, glow, neon, unity, tilegrid, wireframe shader

<img src="https://raw.githubusercontent.com/USSRcoder/gridmap/master/gridmap.png">

1. Создаем GameObject, к нему добавляем mesh, mesh renderer.<br>
2. Добавляем в этому GameObject этот скрипт - <a href="mapgrid1.cs">mapgrid1.cs</a><br>
Мешь создается динамически 126x126, и устанавливает материал.<br><br>
Если делать вручную, то нужно создать материал и добавить в него <a href="gridshader2.shader">gridshader2.shader</a> шейдер. <br>

Использует оси x,y; z для глубины.

Сылки:<br>
https://thebookofshaders.com/07/?lan=ru<br>
https://thndl.com/square-shaped-shaders.html<br>


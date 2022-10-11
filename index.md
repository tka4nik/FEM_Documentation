\section commands_sec Примеры команд:

### Запуск моделирования ###
\code
set geom/geom5.bin geom/profile5.bin
run
render_mode grid
\endcode

geom5.bin и profile5.bin соотвествуют Geometry/0-Mesh/5.0.spr из прототипа.
В файле sample_text.g геометрия корректна, но файлы инструмента для неё был утерян.

### Запуск анимации из файла результатов. ###

\code
show_complete_simulation res/steps_res.res
pause
continue
\endcode

### Настройка градиента в соотвествии с прототипом (gradient 9 colors) ###

\code
render_mode smooth false
render_mode gradient 9 3 120
\endcode

### Настройка градиента в соотвествии с прототипом (gradient 5 colors) ###

\code
render_mode smooth false
render_mode gradient 5 2 120
\endcode

### Обратный анализ ###
\code
reverse_analysis d
pause
target 2
pause
\endcode

 
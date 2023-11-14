# Слайсер в Grasshopper и изготовление керамической поверхности

Целью проекта было создать алгоритм в Grasshopper, который будет выдавать готовый GCODE для печати на керамическом 3D-принтере.

## Моделирование и изготовление поферхности 

Поверхность была смоделирована в GH, переведена в STL формат и отфрезерована. 

![image](https://github.com/gitzense/GH-slicer/assets/114235388/1940f2f1-573e-48e4-afe5-89f880b16913)

![image](https://github.com/gitzense/GH-slicer/assets/114235388/70a43063-2507-4681-aa38-65150f6cc0f7)

https://github.com/gitzense/GH-slicer/assets/114235388/879509e2-b8a5-4eb3-8c93-facc945f1e8e

## GCODE и печать

В Grasshopper был изготовлен алгоритм для моделирования прохода сопла. После этого был составлен алгоритм для получения GCODE.

Изначально напечатать поверхность не вышло, так как ось X на принтере направлена в другую сторону. Поверхность была отзеркалена и был получен новый GCODE. После чего была произведена печать 

https://github.com/gitzense/GH-slicer/assets/114235388/e5ae849a-5a40-47c6-9b8f-4f5d36be6b53

![printing_3](https://github.com/gitzense/GH-slicer/assets/114235388/7799150c-fd17-4977-8e42-c7e65edfa9b6)

![surface-isometry](https://github.com/gitzense/GH-slicer/assets/114235388/6e525de2-be9c-402d-aaf4-5ac89c5cec6c)



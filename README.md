## Описание проекта:
Необходимо разработать игру-шутер с видом сверху для игры 1 на 1. <br/>
В игре один игрок управляется пользователем, а второй — компьютером (AI).

### Используемые библиотеки:
DoTween, NavMeshAgent

### Игровая механика:
1. Игровое поле имеет прямоугольную форму и содержит препятствия. Поле открытое, без ограждений.
2. Пользователь управляет одним из игроков, второй игрок управляется AI.
3. Игроки могут:
- Перемещаться вперёд и назад.
- Поворачиваться влево и вправо вокруг своей оси.
- Стрелять снарядами.

### Правила игры:
1. При попадании в игрока другой игрок получает очко. После этого оба игрока возвращаются на исходные позиции.
2. Очки должны отображаться на экране.

### Механика снарядов:
1. При попадании снаряда в игрока начисляются очки, как описано выше.
2. При столкновении снаряда с препятствием он должен отскакивать и продолжать движение.
3. Если снаряд покидает игровое поле, он исчезает.

### Скриншот проекта:
![alt text](https://sun9-19.userapi.com/s/v1/ig2/Rg3OfUrTJr9_JlJFAsY0vpJYYvUuQZ4iD9F5_1R4jMJ1-3a86d6RTq-J8Ygjizmca--HqgLbICUURCbkD-vmG71y.jpg?quality=95&as=32x18,48x27,72x40,108x61,160x90,240x135,360x202,480x270,540x304,640x360,720x405,1080x607,1261x709&from=bu&u=CR22suTz-Gz31DOiBDnyFZr8I_YOhqL66r-115L9FEM&cs=1261x709)

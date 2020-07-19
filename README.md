# Rock-paper-scissors-console-cpp-game
Консольная игра Камень ножницы бумага написанная на С++

Данный проект содержит документацию на языке моделирования UML.
Она находится в папке UML Документация.
Чтобы с ней ознакомиться я рекомендую использовать сайт https://app.diagrams.net/.

                              Правила игры:
                        
            Как происходят ходы:
Игрок выбирает оружие (камень, ножницы или бумагу), которым он намерен сражаться.
Затем программа делает тоже самое.

            Как определяется победитель:
Оружие выбранное игроком сравнивается с оружием выбранным программой.
Каждое оружие сильнее одного и слабее другого:

Бумага побеждает камень.
Камень побеждает ножницы.
Ножницы побеждают бумагу.

Если оружие игрока побеждает оружие программы, то игрок - победитель.
Если оружие программы побеждает оружие игрока, то программа - победитель.

            Случай с ничьей:
Если игрок и программа выбрали одинаковое оружие, то засчитывается ничья и игра переигрывается.
Так происходит до тех пор, пока не будет определён победитель.

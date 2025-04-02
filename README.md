# 🕹️ Godot Sample Game


Prosty projekt stworzony w [Godot Engine](https://godotengine.org/) – zawiera podstawowy gameplay z graczem, przeciwnikami oraz HUD-em.

Jest to odwzorowana wersja [tutorialu](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html) jako jedno z zadań z kursu Projektowanie i Programowanie Gier na 6 semestrze studiów na PWR. 


## 📁 Zawartość projektu

- `main.tscn` – główna scena gry.
- `player.tscn` i `player.gd` – gracz i jego logika ruchu.
- `mob.tscn` i `mob.gd` – przeciwnicy poruszający się losowo.
- `hud.tscn` i `hud.gd` – interfejs użytkownika z licznikiem punktów i komunikatem Game Over.
- `main.gd` – logika startu gry, spawnowania przeciwników i resetowania.

## ▶️ Jak uruchomić

1. Pobierz [Godot Engine](https://godotengine.org/download).
2. Otwórz folder projektu w Godot.
3. Uruchom scenę `main.tscn`.

## 🎮 Rozgrywka

- Gracz porusza się i unika nadchodzących przeciwników.
- Za każdy ominięty przeciwnik przyznawany jest punkt.
- Po kolizji gra się kończy – możesz zacząć od nowa klikając "Start".

## 🛠️ Technologie

- **Godot Engine** (wersja 3.x lub 4.x – dostosuj w zależności od użytej wersji)
- GDScript



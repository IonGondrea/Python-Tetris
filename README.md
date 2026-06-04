
# 🎮 Python Tetris

Un joc clasic de Tetris dezvoltat în Python, folosind biblioteca Pygame. 

## 🌟 Caracteristici

* **Gameplay Clasic:** Piesele cad, se rotesc și completează linii exact ca în jocul original.
* **Sistem de Scor:** Câștigi puncte pentru fiecare linie completată cu succes.
* **Efecte Sonore:** Jocul include muzică de fundal și efecte audio specifice pentru rotirea pieselor și ștergerea liniilor (prin folderul `Sounds`).
* **Design Curat:** Interfață simplă, intuitivă și culori unice pentru fiecare tip de piesă (Tetromino).

## 📂 Structura Proiectului

* `main.py` - Fișierul principal care inițializează și rulează bucla jocului.
* `game.py` - Gestionează logica centrală, scorul și starea generală a jocului.
* `grid.py` - Controlează grila de joc, matricea și detectarea liniilor complete.
* `blocks.py` / `block.py` - Definesc formele (I, J, L, O, S, T, Z) și comportamentul pieselor.
* `position.py` - Utilitar pentru gestionarea coordonatelor rândurilor și coloanelor.
* `colors.py` - Paleta de culori folosită pentru desenarea elementelor grafice.

## 🚀 Cum să rulezi jocul local

### 1. Cerințe preliminare
Asigură-te că ai instalat **Python** (versiunea 3.x) pe sistemul tău.
Pentru a rula jocul, trebuie să instalezi biblioteca `pygame`. Deschide un terminal și rulează comanda:

```bash
pip install pygame

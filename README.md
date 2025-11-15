
# 🎯 Spot the Intruder — MediaPipe Hand-Tracking Game

This project is a fun **computer vision game** built using **MediaPipe, OpenCV, and Pygame**.
You use **your index finger** to **touch the intruder icon on the screen** to score points — all controlled through **real-time hand tracking using your webcam**.

---

## 🕹 Game Concept

* A webcam feed is displayed on the screen.
* A **target (intruder image)** appears at random positions.
* The game tracks your **index fingertip using MediaPipe**.
* When your fingertip touches the target:

  * 🔊 A sound effect is played
  * 🟢 Your score increases
  * 🎯 A new target appears in a new random location
* You have **60 seconds** to get the highest score possible.

---

## 🧠 Tech Stack

| Library              | Purpose                                      |
| -------------------- | -------------------------------------------- |
| MediaPipe            | Hand tracking & fingertip landmark detection |
| OpenCV               | Camera access, overlays, text display        |
| Pygame               | Sound effects                                |
| Python (time/random) | Timer + random movement logic                |

---

## 🗂 Project Structure

```
📁 Intruder-Game/
 ├── game_script.ipynb / .py          # Main game logic
 ├── instruction.jpg                  # Game instructions screen
 ├── target_image.png                 # Intruder image to touch
 ├── intro_video.mp4                  # Intro clip before game starts
 ├── final_score_image.jpg            # Image displayed after time ends
 ├── sound.mp3                        # Stab / hit sound effect
 ├── logic_reference.pdf              # PDF included for learning
 └── README.md
```

---

## 📄 About the Logic PDF

A PDF named **`logic.pdf`** is included in the repository.

📌 It contains:

* Logic basics
* Reasoning and conditional thinking
* Rules relevant to decision making in games

🧠 This PDF is **for learning only** — it is **not required to run the game**.

---

## ▶ How to Run the Game

### 1️⃣ Install dependencies

```
pip install mediapipe opencv-python pygame
```

### 2️⃣ Run the script

Open the `.py` or `.ipynb` file and execute.

### 3️⃣ Requirements

* Webcam / laptop camera
* Correct paths set for:

  * target image
  * instruction image
  * intro video
  * result screen image
  * sound file

---

## 📝 Gameplay Controls

| Action          | What to do                                 |
| --------------- | ------------------------------------------ |
| Start game      | Press `F` during the intro screen          |
| Score points    | Touch the intruder using your index finger |
| Exit game early | Press `F` during gameplay                  |

⏱ Game ends automatically after **60 seconds**.

---

## ⚠ Notes

* This project is **for educational & experimental purposes**.
* Works best in **good lighting** to detect your hand properly.
* Not a polished commercial game — **a learning project** built to explore MediaPipe + OpenCV.

---

## 👨‍💻 Developer

**Muhammed Rashid**
Learning computer vision, MediaPipe, and game development using Python.

---

## 🌟 Future Improvements (optional ideas)

* Multiple difficulty levels
* Moving / rotating targets
* Combo streak scoring
* Sound on countdown / game over
* High-score storage



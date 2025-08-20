# 🤖 3rd Workshop on Robotics and Automation in Africa — DLI 2025

> **When:** 21 August 2025 
> **Where:** Kigali, Rwanda (Deep Learning Indaba)
> **Note:** Attendance is limited to registered DLI participants.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JenaleaR/DLI_Robotics_Workshop_2025/blob/main/Introduction_to_Human_Pose_Estimation_for_Robotics_.ipynb)

---

## 🚀 What’s this workshop about?

We’re back for the **3rd Workshop on Robotics & Automation in Africa**, a fast-paced, hands-on session showcasing practical robotics and robot-learning activities. You’ll see a live demonstration, then dive into a Colab notebook that gets you reasoning about human pose estimation for robotics tasks.

---

## 🧭 Quick links

* 🏠 Workshop site (schedule, speakers, logistics): [Workshop Website](https://sites.google.com/view/robot-learning-for-africa-2025/home)
* 📓 **Open the tutorial notebook in Colab:**  → [**Launch on Colab** ⬆️](https://colab.research.google.com/github/JenaleaR/DLI_Robotics_Workshop_2025/blob/main/Introduction_to_Human_Pose_Estimation_for_Robotics_.ipynb)
* 💾 Deep Learning Indaba 2025: [Website](https://deeplearningindaba.com/2025/)

---

## 🎯 You’ll learn

### Pose estimation fundamentals

* 🧩 What keypoints, skeletons, and confidence scores mean in practice
* ⚖️ Accuracy vs. latency trade-offs for lightweight vs. high-capacity models
* 👥 Single-person vs. multi-person detection basics and common failure modes (occlusion, truncation)
* 📈 How to think about simple quality checks (e.g., % of keypoints detected, stability over time)

### Hands-on in Colab

* ⚙️ Environment setup, GPU runtime selection, and troubleshooting in Colab
* 🖼️ Running inference on images/video and overlaying skeletons & bounding boxes
* 🧵 Temporal smoothing (e.g., basic EMA) to reduce jitter in live streams
* 🗃️ Exporting results (CSV/JSON) for downstream use or analysis

### From pixels to robot-useful signals

* 🎛️ Mapping keypoints to interpretable features (angles, distances, simple poses)
* 🚦 Thresholding, debouncing, and rate-limiting to make signals actionable & safe
* 🔁 A tiny state-machine pattern: “if gesture → do behavior,” with guard rails
* 🔌 How to pass keypoints to other systems (e.g., ROS/web apps) via file or sockets

### Human–Robot Interaction (HRI) considerations

* 🙋 Gesture sets you can prototype quickly (wave, point, hands-up, attention)
* 🌍 Cultural context & robustness: why norms matter (ties into the Pepper demo)
* 🔒 Privacy, consent, and respectful data handling in interactive sessions

### Performance & debugging

* ⏱️ Measuring throughput/FPS and spotting bottlenecks
* 🐞 Diagnosing false positives/negatives; quick fixes for lighting, scale, and motion blur
* 🧪 Creating tiny test clips to reproduce and compare behaviors consistently

### (Optional) Stretch ideas

* 🧭 Coordinate frames & basic scaling (pixel distances → approximate real-world cues)
* 🧰 Where to go next: multi-view setups, 3D pose, and better temporal models

---

## ▶️ How to use this repo

1. Click **Open in Colab** above.
2. Run the setup cell(s) and follow the notebook prompts.
3. Bring questions! The session is interactive and demo-driven.

---

## 🎬 Pre-workshop demo: Pepper @ CMU-Africa (CSSR4Africa)

We’ll kick off with a short demo inspired by **Culturally Sensitive Social Robotics for Africa (CSSR4Africa)** - showcasing how **verbal and non-verbal cultural norms** can be encoded to make social robot interactions more natural on the continent. Learn more here: [CSSR4Africa](https://cssr4africa.github.io/overview.html)

---

## 🧑‍🏫 Speakers & schedule

See the latest lineup (keynotes, panel, timings) on the workshop site’s **Schedule** section. ([DLI Robotics Workshop 2025 Website][1])

---

## 🏆 Sponsors

Huge thanks to our supporters:

* **IEEE Robotics & Automation Society (RAS)**&#x20;
* **[The RAIL Lab](https://www.raillab.org/)**&#x20;

---

## 👥 Organisers

Geraud Nangue Tasse (University of the Witwatersrand) • Jenalea Rajab (DEI Projects) • Ndivhuwo Makondo (IBM Research Africa; University of the Witwatersrand) • Tamlin Love (Institut de Robòtica i Informàtica Industrial, CSIC-UPC) • Zukisa Mbuli (University of the Witwatersrand) • Alexandra Barry (University of the Witwatersrand) • Iretiayo Akinola (NVIDIA Research) • Sicelukwanda Zwane (University College London)
**Local organisers:** Hubert Apana, Richard Muhirwa (CMU-Africa).

---

## 📜 Past editions

* **2nd Robot Learning for Africa Workshop — DLI 2024 (Dakar, Senegal)**
  
  [2nd Workshop Website](https://sites.google.com/view/robotlearning4africa-2024)
  In a collaboration with Scaleup Robotics AB, the session enabled participants to program live robot arms located in Sweden. This practical tutorial explored the fundamentals and applications of cloud robotics and cutting‑edge techniques in robotic manipulation.
  


* **Robot Learning for Africa Workshop — DLI 2023 (Accra, Ghana)**

  [1st Workshop Website](https://sites.google.com/view/robotlearning4africa)
  The hands-on demo focused on Getting Started with Imitation Learning using a 6‑DOF (cobot) robot arm. Participants were guided to train a Behaviour Cloning policy using provided demonstration data, and then encouraged to collect additional simulation data in PyBullet to further improve the policy’s performance. [PyTorch Implementation](https://github.com/Sicelukwanda/simple-imitation-learning ) [JAX Implementation](https://github.com/Sicelukwanda/robot_learning_tutorial)


---

## 📅 Where this fits at Indaba

This workshop is part of the official **DLI 2025 Workshops** programme. ([Deep Learning Indaba 2025 - Workshops][6])

---

## 🪪 License

This repo is MIT-licensed. See `LICENSE` in the root directory. ([GitHub][2])

[1]: https://sites.google.com/view/robot-learning-for-africa-2025/home "Website for the 3rd Workshop on Robotics and Automation in Africa"
[2]: https://github.com/JenaleaR/DLI_Robotics_Workshop_2025/tree/main "GitHub Repository for the Robotics and Automation Workshop at the Deep Learning Indaba in Kgali, Rwanda 2025"
[3]: https://cssr4africa.github.io/overview.html?utm_source=chatgpt.com "CSSR - Culturally Sensitive Social Robotics for Africa"
[4]: https://sites.google.com/view/robotlearning4africa-2024/home "Website for the 2nd Workshop on Robotics and Automation in Africa"
[5]: https://sites.google.com/view/robotlearning4africa "Website for the 1st Workshop on Robotics and Automation in Africa"
[6]: https://deeplearningindaba.com/2025/workshops "Workshops - Deep Learning Indaba 2025"

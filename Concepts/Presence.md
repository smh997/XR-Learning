# 📘 Presence in Virtual Reality (VR)

## 🧠 What is Presence?
**Presence** is the psychological sensation of “being there” inside a virtual environment. It reflects how convincingly a VR system can make the user feel immersed in and part of the digital world.

## 🎯 Why It Matters in AR/VR
Presence is a key indicator of a successful immersive experience. It enhances user engagement, task performance, learning, and emotional impact. High presence leads to more natural behavior and more effective interactions in VR environments.

## 🔬 Key Factors

| Factor                    | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Field of View (FOV)       | ≥ 80° horizontal FOV is required to approximate human peripheral vision     |
| Resolution                | 1080p or higher display resolution for visual clarity                       |
| Pixel Persistence         | ≤ 3 ms to reduce motion blur and ghosting                                  |
| Refresh Rate              | > 60 Hz (ideally 90–95 Hz) to maintain visual fluidity                      |
| Global Illumination       | Simultaneous pixel lighting reduces motion artifacts                        |
| Optics                    | Low-distortion lenses (1–2 per eye); ideal optics still limited              |
| Tracking Accuracy         | Positional: millimeter-level; Orientation: ≤ 0.25°; Tracking volume ≥ 1.5m³ |
| Latency                  | End-to-end delay ≤ 20–25 ms to avoid disconnect between action and feedback |
| Calibration               | Optical and tracking calibration ensure depth and stereo accuracy           |
| Sensorimotor Coherence    | Consistent responses to user motion (visual + physical + interaction)       |
| Virtual Body Representation | Full or partial embodiment (hands, avatars) enhances spatial anchoring    |

## 💡 Design Implications
- Use **high-refresh headsets** and optimize render loops to minimize latency.
- Ensure **accurate positional and rotational tracking** of the headset and controllers.
- Avoid inconsistent sensory input (e.g., mismatch between audio and visuals).
- Keep the user's control intuitive and responsive to strengthen presence.
- Be aware of **breaks in presence**, such as UI interruptions, freezing, or drift.
- Use **stacked sensory layers** (sound, touch, motion) that reinforce each other to deepen immersion.
- Include some form of **virtual body**, even minimal, to help the user feel physically grounded.

## 📄 Supporting Research
| Title                                                                                     | Source                                                                                  | Notes                                          |
|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|------------------------------------------------|
| Factors Affecting Sense of Presence in a Virtual Reality Social Environment               | [ResearchGate](https://www.researchgate.net/publication/331335083_...)                 | Covers realism, user control, and sickness     |
| Is It Real? Effect of Resolution, Latency, Frame Rate, and Jitter                         | [ResearchGate](https://www.researchgate.net/publication/337110321_...)                 | Technical factors affecting presence           |
| Towards Enhanced Learning Through Presence in Virtual Reality Environments                | [arXiv](https://arxiv.org/abs/2504.13845)                                               | Presence dimensions: spatial, social, cognitive|
| Depth of Presence in Immersive Virtual Environments                                       | [ResearchGate](https://www.researchgate.net/publication/237129885_...)                 | Discusses stacking depth, sensorimotor feedback, and virtual body impact on presence |

## ✍️ My Reflections
- **Surprise**: How sensitive presence is to even small display or tracking delays.
- **Seen in Unity**: The feeling of being “inside” the VR Room scene changes with lighting and movement feedback.
- **Want to test**: Try adding head-based locomotion + ambient sound in the VR Room to see if it improves spatial immersion.
- **New insight from Slater paper**: Presence is not binary; it's built from layered experiences and interactions—called “stacking depth.”
- **Idea to explore**: Build a version of the VR Room with and without virtual hand representation to compare anchoring effects.

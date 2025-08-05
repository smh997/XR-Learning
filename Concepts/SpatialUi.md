# 🧭 Spatial UI & Affordances in XR

## 🧠 What is Spatial UI?

**Spatial User Interfaces (Spatial UI)** are interfaces placed in 3D space that allow users to interact naturally using their body, vision, and spatial awareness. Unlike flat screens, spatial UIs exist in the user's environment and can be interacted with from multiple angles, distances, and positions.

### Key Characteristics:
- **3D Layouts**: Panels, buttons, and elements exist in depth — not just width and height
- **User-relative or world-relative positioning**: Interfaces can follow the user or stay fixed in space
- **Embodied Interaction**: Gaze, hand movement, and physical gestures are primary input methods

---

## 📐 Design Principles of Spatial UI

| Principle                     | Description                                                                 |
|------------------------------|-----------------------------------------------------------------------------|
| **Comfort Zone**             | Keep UI within easy arm reach and ±30° vertical/horizontal field of view   |
| **Anchoring**                | Place persistent UI elements (e.g., menus) in world-locked or body-relative locations |
| **Minimize Occlusion**       | Avoid placing interfaces behind objects or too low/high for natural interaction |
| **Use Depth Intelligently**  | Leverage shadows, parallax, and subtle motion to convey hierarchy and intent |
| **Clear Entry Points**       | Guide users toward initial interaction through placement, animation, or glow |
| **Maintain Focus Flow**      | Avoid clutter and distraction in peripheral zones; design for immersion     |

---

## 🎯 What Are Affordances?

**Affordances** are the visual, tactile, or contextual cues that tell users how to interact with something—without requiring explicit instructions.

### Types of Affordances in XR:
| Type           | Description                                                               | XR Example                          |
|----------------|---------------------------------------------------------------------------|-------------------------------------|
| **Cognitive**  | Learned cues or expectations from the real world                         | Button shape, virtual light switch  |
| **Physical**   | Requires effort or reach—how hard or easy something is to use            | Levers, drawers                     |
| **Sensory**    | Cues through visual/audio/haptic feedback                                | Glow, highlight, click sound        |
| **Functional** | Directly conveys the action that will occur                              | Hover to open, press to teleport    |

---

## 💡 Design Takeaways

- Use **highlighting, motion, and scaling** to signal interactivity
- Provide **feedback loops** (visual or haptic) after action to confirm effect
- Onboarding should be **non-verbal and playful** (e.g., affordances that teach by interaction)
- Keep elements within **comfortable eye-level and arm’s reach**
- Avoid over-reliance on **2D UI** inside VR — use space!

---

## ✍️ My Reflections

- **Surprised by**: How subtle cues like **shadows and depth offset** help users identify interactable elements.
- **Want to try**: A floating menu that lights up when the user’s hand is nearby — testing **sensory affordances** in Unity.
- **Seen in Unity Learn**: Teleportation arcs and fading transitions are great examples of functional and cognitive affordances.
- **Challenge**: Finding the balance between *guiding the user* and *letting them discover* affordances on their own.

---


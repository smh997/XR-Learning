# 🎮 XR Interaction Models

## 🧠 What Are XR Interaction Models?

**XR Interaction Models** define how users engage with and control immersive environments using input methods such as hand gestures, controllers, eye gaze, voice commands, and full-body motion. These models form the basis of **how natural, intuitive, and effective** user actions feel within VR and AR systems.

---

## 🎯 Why It Matters in AR/VR

Interaction is the bridge between **user intention** and **system response** in immersive tech.

- Strong models = more **fluid, immersive, and intuitive** experiences  
- Weak models = **breaks in presence**, confusion, or even motion sickness  
- The **choice of model** should match the context (e.g., direct grabbing for object interaction, raycasting for distant UI selection)

---

## 🧩 Common XR Interaction Techniques

| Model                      | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| **Direct Manipulation**   | Grabbing, rotating, pushing/pulling using virtual hands or controllers      |
| **Raycasting (Pointing)** | Using a laser-like pointer for menu interaction or teleportation            |
| **Gaze-Based**            | Selecting or highlighting items by looking at them                          |
| **Gesture-Based**         | Recognizing hand/finger motions (e.g., pinch to zoom, swipe)                |
| **Voice Input**           | Controlling the experience through verbal commands                          |
| **Physical Locomotion**   | Walking, leaning, crouching in real life to navigate or interact            |
| **Teleportation**         | Jumping to a new location to reduce motion sickness                         |
| **Controller-Based UI**   | Buttons, thumbsticks, haptics as control interface for movement or actions  |

---

## 💡 Design Principles (From Research)

| Principle                  | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| **Prioritize Comfort**     | Avoid input systems that cause disorientation, fatigue, or sickness         |
| **Natural Mappings**       | Match real-world expectations (e.g., grasping = grabbing)                   |
| **Immediate Feedback**     | Visual/audio/haptic responses to all inputs build confidence                |
| **Affordance Clarity**     | Make interactive elements visually suggestive of their functionality        |
| **Iterative Testing**      | Frequent user testing uncovers flaws in interaction logic                   |
| **Context-Awareness**      | Consider user context (sitting/standing, dominant hand, etc.)               |
| **Inclusivity**            | Support users with physical/cognitive impairments through adaptable systems |

---

## 🛠️ Practical Implications

- Combine **gaze + raycasting** for menus, **grabbing** for object manipulation  
- Use **teleportation arcs** for locomotion, supported with **fading transitions** to ease motion shifts  
- Design **interaction zones** (e.g., comfort bubbles) to avoid strain  
- Favor **low cognitive load** patterns (e.g., consistent icons, limited modes)

---

## 📄 Supporting Research

| Title                                                                      | Source                                                                 | Notes                                                                 |
|----------------------------------------------------------------------------|------------------------------------------------------------------------|-----------------------------------------------------------------------|
| VR Interaction Design: Best Practices and Principles                       | [daily.dev](https://daily.dev/blog/vr-interaction-design-best-practices-and-principles) | Practical guidelines for immersive interaction design                 |
| A Survey on the Design of Virtual Reality Interaction                      | [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11479089/)         | Literature review of 438 papers; best practices, gaps, and priorities |
| Designing for Spatial UX in AR/VR                                          | [UX Planet](https://uxplanet.org/designing-for-spatial-ux-in-ar-vr-74e594cfb3dc)        | Focuses on spatial feedback, onboarding, and safe zones               |
| Affordance Guidelines for AR UX                                            | [UXDesign.cc](https://uxdesign.cc/affordance-guidelines-for-ar-ux-6b8c4657f209)         | Details types of affordances and their role in intuitive interaction  |

---

## ✍️ My Reflections

- **Seen in Unity**: Ray-based teleportation and menu interaction felt most natural with haptic + visual feedback.  
- **Want to try**: Full-body avatar input with IK (inverse kinematics) to better match real-world posture.  
- **Surprised by**: How fast user trust breaks when an interaction doesn’t provide feedback (e.g., silent menu tap).  
- **New insight**: Functional + cognitive affordances often overlap — like teleport arcs showing where you’ll land.  
- **Idea**: Prototype same interaction using gesture vs. controller vs. gaze to see user preference and fatigue impact.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:020024,35:090979,100:00D4FF&height=3&section=header" width="100%" />

<br />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=2600&pause=700&color=00D4FF&center=true&vCenter=true&width=950&lines=%3E+booting+EvenWang.lab...;%3E+loading+robotics+%2B+RL+%2B+world+models...;%3E+initializing+embodied+intelligence+workspace...;%3E+status%3A+building+agents+that+learn%2C+plan%2C+and+act." />

<br />

<h1>
  <code>Even Wang</code>
</h1>

<p>
  <b>Algorithm Engineer · Robot Learning · Reinforcement Learning · World Models · Embodied AI</b>
</p>

<p>
  <img src="https://img.shields.io/badge/System-Embodied%20AI%20Lab-00D4FF?style=for-the-badge&labelColor=0B1020" />
  <img src="https://img.shields.io/badge/Core-Robot%20Learning-7C3AED?style=for-the-badge&labelColor=0B1020" />
  <img src="https://img.shields.io/badge/Mode-Research%20%2B%20Engineering-22C55E?style=for-the-badge&labelColor=0B1020" />
</p>

</div>

---

<table>
<tr>
<td width="58%" valign="top">

## 🧬 Profile Kernel

```python
class EvenWangLab:
    identity = "Algorithm Engineer"
    domain = [
        "Embodied AI",
        "Robot Learning",
        "Reinforcement Learning",
        "World Models",
        "Humanoid Robot Control"
    ]

    current_stack = {
        "robotics": ["humanoid control", "robot soccer", "sim-to-real"],
        "rl": ["hierarchical RL", "self-play", "offline RL", "imitation learning"],
        "world_model": ["Dreamer", "latent dynamics", "video-enhanced RL"],
        "engineering": ["training pipeline", "simulation", "deployment interface"]
    }

    mission = (
        "Build embodied agents that can learn reusable skills, "
        "reason with world models, and transfer to real-world robots."
    )
```

</td>
<td width="42%" valign="top">

## ⚙️ Runtime Status

```text
[ research focus ]    Embodied Intelligence
[ active system  ]    Robot Soccer + World Models
[ main algorithm ]    RL / MBRL / IL / Self-Play
[ simulation     ]    Isaac Gym / Meta-World
[ deployment     ]    Sim-to-Real Robot Control
[ long horizon   ]    Generalizable Embodied Agents
```

<br />

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Wang-Even&label=Profile%20Signals&color=00d4ff&style=flat-square" />
</p>

</td>
</tr>
</table>

---

## 🛰️ Research Navigation Map

<div align="center">

```mermaid
flowchart LR
    A[Perception] --> B[World Model]
    B --> C[Planning]
    C --> D[Skill Policy]
    D --> E[Robot Execution]
    E --> F[Real-World Feedback]
    F --> B

    B -. latent dynamics .-> G[Dreamer-style MBRL]
    D -. reusable skills .-> H[Hierarchical RL]
    C -. tactics .-> I[Self-Play / Multi-Agent RL]
    F -. sim-to-real .-> J[Humanoid Deployment]
```

</div>

---

## 🧠 Research Modules

<table>
<tr>
<td width="50%" valign="top">

### ⚽ Module 01 — Robot Soccer / Humanoid RL

```text
repo        : BoosterGym
objective   : hierarchical robot soccer intelligence
architecture:
  ├── low-level control
  ├── mid-level skill policies
  └── high-level multi-agent tactics
```

**BoosterGym** is a hierarchical robot soccer research workspace for building humanoid control policies from locomotion to team-level tactics.

<a href="https://github.com/Wang-Even/BoosterGym">
  <img src="https://img.shields.io/badge/Open-BoosterGym-00D4FF?style=for-the-badge&labelColor=0B1020" />
</a>

</td>
<td width="50%" valign="top">

### 🌍 Module 02 — World Models

```text
repo        : World-Model-in-Metaworld
objective   : Dreamer-style model-based RL
environment : Meta-World manipulation tasks
core idea   : learn latent dynamics for planning
```

**World-Model-in-Metaworld** explores Dreamer-style world models for robotic manipulation and visual control environments.

<a href="https://github.com/Wang-Even/World-Model-in-Metaworld">
  <img src="https://img.shields.io/badge/Open-World--Model--in--Metaworld-7C3AED?style=for-the-badge&labelColor=0B1020" />
</a>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🎥 Module 03 — Video-Enhanced Offline RL

```text
repo        : VeoRL
objective   : transfer prior knowledge from video
method      : model-based offline RL
domains     : manipulation / driving / open-world tasks
```

**VeoRL** studies how unlabeled video data can enhance offline reinforcement learning through world-model-based behavior guidance.

<a href="https://github.com/Wang-Even/VeoRL">
  <img src="https://img.shields.io/badge/Open-VeoRL-22C55E?style=for-the-badge&labelColor=0B1020" />
</a>

</td>
<td width="50%" valign="top">

### 📈 Module 04 — Applied ML System

```text
repo        : Exchange-Rate-Forecaster
objective   : multimodal time-series forecasting
model       : Transformer-LSTM
signals     : historical rate + market sentiment
```

**Exchange-Rate-Forecaster** is a deployable multimodal forecasting system that combines time-series modeling and sentiment-aware prediction.

<a href="https://github.com/Wang-Even/Exchange-Rate-Forecaster">
  <img src="https://img.shields.io/badge/Open-Exchange--Rate--Forecaster-F59E0B?style=for-the-badge&labelColor=0B1020" />
</a>

</td>
</tr>
</table>

---

## 🧩 System Architecture I Care About

<div align="center">

```text
┌──────────────────────┐
│   Simulation World   │
│ Isaac Gym / MetaWorld│
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  Representation      │
│  Latent State Model  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  Policy Learning     │
│  RL / IL / Self-Play │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│  Skill Execution     │
│  Move / Pass / Trap  │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Real Robot Interface │
│ Sim-to-Real Control  │
└──────────────────────┘
```

</div>

---

## 🛠️ Toolchain

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,cpp,linux,git,github,docker,ros,vscode" />

<br />
<br />

<img src="https://img.shields.io/badge/Reinforcement%20Learning-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Model--Based%20RL-4C1D95?style=for-the-badge" />
<img src="https://img.shields.io/badge/World%20Models-1E40AF?style=for-the-badge" />
<img src="https://img.shields.io/badge/Humanoid%20Control-065F46?style=for-the-badge" />
<img src="https://img.shields.io/badge/Sim--to--Real-92400E?style=for-the-badge" />

</div>

---

## 📡 Project Radar

| Signal                       | Project                                                                           | Role in My Research Map                                                                                 |
| ---------------------------- | --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| ⚽ Robot Soccer / Humanoid RL | [BoosterGym](https://github.com/Wang-Even/BoosterGym)                             | Hierarchical robot soccer policy stack with low-level control, mid-level skills, and high-level tactics |
| 🌍 World Models              | [World-Model-in-Metaworld](https://github.com/Wang-Even/World-Model-in-Metaworld) | Dreamer-style world model experiments on Meta-World tasks                                               |
| 🎥 Offline RL                | [VeoRL](https://github.com/Wang-Even/VeoRL)                                       | Video-enhanced offline reinforcement learning reproduction and study                                    |
| 📈 Applied ML                | [Exchange-Rate-Forecaster](https://github.com/Wang-Even/Exchange-Rate-Forecaster) | Multimodal Transformer-LSTM exchange-rate forecasting system                                            |

---

## 📊 Dynamic Signals

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Wang-Even&show_icons=true&theme=transparent&hide_border=true&title_color=00D4FF&text_color=FFFFFF&icon_color=22C55E&bg_color=0B1020" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Wang-Even&layout=compact&theme=transparent&hide_border=true&title_color=00D4FF&text_color=FFFFFF&bg_color=0B1020" />

</div>

<br />

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Wang-Even&theme=react-dark&hide_border=true&area=true&bg_color=0B1020&color=00D4FF&line=22C55E&point=FFFFFF" />

</div>

---

## 🧭 Current Trajectory

```text
2026 focus:
  ├── Humanoid robot soccer with hierarchical policy learning
  ├── Mid-level reusable skill policies: chase / pass / trap
  ├── High-level tactics with imitation learning and self-play RL
  ├── Dreamer-style world models for visual control
  └── Video-enhanced offline RL for embodied agents
```

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=3000&pause=1000&color=22C55E&center=true&vCenter=true&width=900&lines=Learning+from+simulation.;Reasoning+with+world+models.;Acting+through+hierarchical+policies.;Transferring+toward+real+robots." />

<br />
<br />

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00D4FF,100:7C3AED&height=3&section=footer" width="100%" />

</div>


---
layout: default
title: Home
---

IARA is an interdisciplinary group of researchers in robotics, AI, and automation at the University of Ottawa. We focus on developing deployable robotic systems by combining sensing, control, and learning, with strong engagement in industry and government applications.

IARA brings together faculty across Mechanical Engineering, Electrical Engineering and Computer Science working on applied robotics and AI.

---

## People


<div class="grid">
{% for pi in site.data.pis %}
  <div class="card">
    <h3>
      <a href="{{ pi.url }}">
        {{ pi.name }}
      </a>
    </h3>
    <p>{{ pi.lab }}</p>
  </div>
{% endfor %}
</div>



---

## Research Areas

- **Robotic Systems & Automation**  
  Autonomous navigation, manipulation, multi-agent systems, and decision making

- **AI & Robot Learning**  
  Reinforcement learning, adaptive control, sim-to-real transfer, human–robot interaction

- **Sensing & Perception**  
  Machine vision, multimodal sensing, and instrumentation

---

## Opportunities

We train undergraduate and graduate students in robotics and AI through hands-on projects, industry collaborations, and applied research.

We welcome partnerships with industry and government organizations.

---

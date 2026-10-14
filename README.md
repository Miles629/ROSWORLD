# ROSWORLD: Robotic Computer Use for OSWorld Tasks

[Project website](https://miles629.github.io/ROSWORLD/) · [Official code (currently private)](https://github.com/lwdQAQ/ROSWorld) · [Contact](mailto:woshimacaoyuan@gmail.com)

**Caoyuan Ma¹²\*, Wendi Liu¹\*, Wenqi Shao², Yinqiang Zheng¹**  
¹ UTokyo · ² JD Explore  
\* Equal contribution (co-first authors).

Release date: **October 12, 2026 (AoE)**.

ROSWORLD is a long-term, evolving benchmark for robotic computer use. It connects an **Isaac Sim** environment with a real virtual machine: models observe a given viewpoint and control robotic arms or dexterous hands to operate a simulated keyboard and mouse. Input signals are sent to the VM, and its live display is rendered onto the simulated monitor, forming a perception–action loop for OSWorld tasks.

The [demo video](demo.mp4) is preliminary and does **not** represent the final evaluation protocol. Viewpoints, robot models, and other assets may change before release.

## Evaluation and roadmap

Comparative evaluations will use fixed protocols, including fixed robotic arm, dexterous hand, and humanoid robot models. Results will include their corresponding model versions and evaluation configurations.

| Model | Status |
| --- | --- |
| gpt-6-astra | Under evaluation |
| gpt-6.1-sol | Pending evaluation |
| claude-fable-5 | Pending evaluation |
| claude-opus-5 | Pending evaluation |
| deepseek-vision-exp | Pending evaluation |

- Initial evaluation results are expected **before October 20, 2026**.
- Full research code and diverse assets are planned for open-source release **by the end of October 2026**.
- An accompanying technical report is planned for release on **arXiv before the end of October 2026**.
- New tasks and models will be introduced as capabilities advance, with ongoing leaderboard updates.

This repository is for the **project website only**, including its preliminary demo. The **official research code and evaluation assets** belong to [lwdQAQ/ROSWorld](https://github.com/lwdQAQ/ROSWorld), which is currently private and is planned to become public by the end of October 2026. The official repository may not be accessible before its public release.

If you would like your model evaluated, contact **woshimacaoyuan@gmail.com** to discuss API access and evaluation arrangements.

## Citation

```bibtex
@misc{rosworld2026,
  author = {Ma, Caoyuan and Liu, Wendi and Shao, Wenqi and Zheng, Yinqiang},
  title = {{ROSWORLD}: Robotic Computer Use for {OSWorld} Tasks},
  year = {2026},
  url = {https://miles629.github.io/ROSWORLD/},
  note = {Project website; open-source release planned for October 2026}
}
```

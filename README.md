# Awesome Legged Loco-Manipulation

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/Czy213hd/awesome-legged-loco-manipulation?style=social)](https://github.com/Czy213hd/awesome-legged-loco-manipulation/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Czy213hd/awesome-legged-loco-manipulation?style=social)](https://github.com/Czy213hd/awesome-legged-loco-manipulation/network/members)
[![GitHub last commit](https://img.shields.io/github/last-commit/Czy213hd/awesome-legged-loco-manipulation)](https://github.com/Czy213hd/awesome-legged-loco-manipulation/commits/main)
[![License](https://img.shields.io/github/license/Czy213hd/awesome-legged-loco-manipulation)](LICENSE)

A curated list of papers, projects, datasets, simulators, and open-source resources for reinforcement learning, whole-body control, and legged loco-manipulation.

## About

Legged loco-manipulation studies how legged robots perform locomotion and manipulation simultaneously.

Unlike fixed-base robot arms, legged manipulators must coordinate:

- Dynamic balance
- Foot-ground contacts
- Base motion
- End-effector tracking
- Whole-body posture
- Collision avoidance
- Perception and decision-making
- Sim-to-real transfer

This repository focuses on learning-based methods for legged loco-manipulation, including:

- Reinforcement learning
- Imitation learning
- Whole-body control
- Diffusion policies
- Motion imitation
- Vision-based manipulation
- Teleoperation and demonstration collection
- Sim-to-real and sim-to-sim transfer
- Quadruped, bipedal, and humanoid robots

## Contents

- [Papers and Projects](#papers-and-projects)
- [How to Add an Entry](#how-to-add-an-entry)
- [Contributing](#contributing)
- [Citation](#citation)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Papers and Projects

Entries are sorted by publication year, with the newest work listed first.

| Year | Title | Authors / Organization | Venue | Robot | Resources |
|:---:|---|---|:---:|---|---|
| 2026 | **Paper or Project Title** | Author et al. | ICRA | Humanoid | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK) |
| 2025 | **Paper or Project Title** | Author et al. | CoRL | Biped + Arm | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) |
| 2025 | **Paper or Project Title** | Author et al. | RSS | Quadruped + Arm | [Paper](PAPER_LINK) · [Video](VIDEO_LINK) |
| 2024 | **Paper or Project Title** | Author et al. | ICRA | Humanoid | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) |
| 2024 | **Paper or Project Title** | Author et al. | IROS | Quadruped + Arm | [Paper](PAPER_LINK) · [Code](CODE_LINK) |
| 2023 | **Paper or Project Title** | Author et al. | CoRL | Legged Robot | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) |

### Entry Description

A short description may be placed below the table when a paper requires additional explanation.

#### Paper or Project Title

- **Year:** 2026
- **Authors:** Author A, Author B, and Author C
- **Venue:** ICRA 2026
- **Robot:** Humanoid robot
- **Method:** Reinforcement learning and whole-body control
- **Task:** Mobile manipulation
- **Resources:** [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK)

This work introduces a learning-based whole-body controller that enables a humanoid robot to coordinate locomotion and manipulation.

---

## How to Add an Entry

Use the following format when adding a new paper or project to the table:

```markdown
| YEAR | **TITLE** | AUTHORS_OR_ORGANIZATION | VENUE | ROBOT | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK) |
```

For example:

```markdown
| 2025 | **Learning Whole-Body Loco-Manipulation** | Author et al. | ICRA | Biped + Arm | [Paper](PAPER_LINK) · [Project](PROJECT_LINK) · [Code](CODE_LINK) · [Video](VIDEO_LINK) |
```

Not every entry needs to include all links. Keep only the resources that are available.

For example:

```markdown
| 2025 | **Learning Whole-Body Loco-Manipulation** | Author et al. | ICRA | Biped + Arm | [Paper](PAPER_LINK) · [Video](VIDEO_LINK) |
```

### Recommended Resource Links

Whenever possible, use official sources:

- Official project page
- arXiv paper
- Publisher paper page
- Official GitHub repository
- Official demonstration video
- Official dataset page

Avoid unofficial reposts when the original source is available.

### Venue Format

Use common abbreviations for conferences and journals:

- ICRA
- IROS
- RSS
- CoRL
- NeurIPS
- ICML
- RA-L
- T-RO
- IJRR
- Science Robotics
- SIGGRAPH
- arXiv

### Robot Format

Use a concise robot description, for example:

- Quadruped
- Quadruped + Arm
- Biped
- Biped + Arm
- Humanoid
- Humanoid + Dual Arms
- Wheeled-Legged Robot
- Multiple Embodiments

---

## Contributing

Contributions are welcome.

You can contribute papers, projects, datasets, simulators, robot platforms, tutorials, or other resources related to legged loco-manipulation.

### Contribution Workflow

1. Fork this repository.

2. Clone your fork:

```bash
git clone https://github.com/YOUR_USERNAME/awesome-legged-loco-manipulation.git
```

3. Enter the repository:

```bash
cd awesome-legged-loco-manipulation
```

4. Create a new branch:

```bash
git checkout -b add-new-resource
```

5. Edit `README.md` and add the resource.

6. Commit your changes:

```bash
git add README.md
git commit -m "Add paper: PAPER_TITLE"
```

7. Push the branch:

```bash
git push origin add-new-resource
```

8. Open a pull request.

### Contribution Guidelines

Please follow these guidelines:

- Add only resources related to legged locomotion, whole-body control, robot learning, or loco-manipulation.
- Use the official title of the paper or project.
- Use official paper, project, code, dataset, and video links whenever possible.
- Do not add duplicate entries.
- Sort entries by year, with the newest work first.
- Keep descriptions concise and objective.
- Do not use promotional or exaggerated language.
- Check that all links work before submitting.
- Clearly indicate whether the resource is a paper, project, dataset, simulator, or code repository.
- Keep the table format consistent.
- Use one pull request for one paper or one closely related group of resources.

### Pull Request Title

Recommended format:

```text
Add: Paper or Project Title
```

Example:

```text
Add: Learning Whole-Body Loco-Manipulation
```

### Commit Message

Recommended format:

```text
Add paper: Paper Title
```

Example:

```text
Add paper: Learning Whole-Body Loco-Manipulation
```

---

## Citation

If this repository is useful for your research, please consider citing it:

```bibtex
@misc{chen2026awesomeleggedlocomanipulation,
  author       = {Zhongyu Chen},
  title        = {Awesome Legged Loco-Manipulation},
  year         = {2026},
  howpublished = {\url{https://github.com/Czy213hd/awesome-legged-loco-manipulation}},
  note         = {A curated list of papers, projects, datasets, simulators, and open-source resources for legged loco-manipulation}
}
```

---

## Acknowledgements

Thanks to all researchers, engineers, and open-source contributors who have advanced legged locomotion, whole-body control, robot learning, and loco-manipulation.

The papers, code, videos, datasets, images, and project materials linked in this repository belong to their original authors and organizations.

This repository only collects and organizes publicly available resources for academic and educational purposes.

---

## Disclaimer

This repository is an independently maintained academic resource list.

The inclusion of a paper, project, dataset, organization, robot platform, or software framework does not imply endorsement.

If you are an author or copyright holder and would like an entry to be corrected or removed, please open an issue.

---

## License

This repository is released under the [MIT License](LICENSE).

External papers, code repositories, datasets, images, and project resources remain subject to their original licenses and copyright terms.

---

## Star History

If you find this repository useful, please consider giving it a star.

[![Star History Chart](https://api.star-history.com/svg?repos=Czy213hd/awesome-legged-loco-manipulation&type=Date)](https://star-history.com/#Czy213hd/awesome-legged-loco-manipulation&Date)

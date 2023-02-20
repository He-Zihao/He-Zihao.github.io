# Model correction in thermal environment (work in progress)

Structural elements are used to represent boundary stiffness for complex dynamic modeling problems in thermal environments. First, modal tests were done at different temperatures. Then the finite element model of the structure was updated at different temperatures. Instead of using a sensitivity-based approach, the updating method bases on SVR to construct a response surface and solve the model updating problem with a particle swarm optimization algorithm. This research seeks to construct an accurate finite element model over a wide temperature range.

| Picture | Note|
| :---:   | :--- |
| ![P1](https://he-zihao.github.io/ResearchesProjects/image/5-1.jpg) | Mode test at high temperature |
| ![P2](https://he-zihao.github.io/ResearchesProjects/image/5-2.jpg) | Experimental modes and simulated modality |
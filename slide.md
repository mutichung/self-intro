---
marp: true
theme: muti-onedark
class: invert
paginate: true
math: mathjax
---

<!-- _paginate: false -->

# Hi, I'm Muti!

Nice to meet you :p

![bg right:25% contain](assets/profile_pic.png)

---

## Basics

- **Name**: Mu-Ti Chung / Muti / 鍾慕提
- **Location**: Taiwan
- **Education**:
  - B.S. in Mechanical Engineering @ NTU
  - M.S. in Robotics @ UMich
- **Current**: Software Engineer @ Ambarella


---

### Ambarella

Design chips for **vision** applications and **edge-AI**.

- Consumer devices: GoPro, DJI, Insta360.
- Automotive: L2+ to L4.
- IoT: security cameras.

![bg right:20% contain](assets/ambarella_white.png)

---

## Professional

- Algorithm team.
- Top-level / Frontline of the AI deployment software stack.

![h:380 center opacity:0.85 rounded](https://www.ambarella.com/wp-content/uploads/slide2.png)

<!-- _footer: "https://www.ambarella.com/blog/the-story-of-cvflow/" -->

---

:::: row

::: column
### Model Optimization

![invert height:100px center brightness:0.65](assets/compress.png)

- Efficiency: **pruning** & **quantization**.
-
- Research & design algorithms & recipes.
- Develop libraries & SDKs.
- Support requests from customers.

:::

::: column
### Literature Studies

![invert height:100px center brightness:0.8 grayscale](assets/nn.png)

- Keep up with latest advancements to ensure hardware support.
  - Model architectures
  - Data formats
- Report to CTO during weekly meetings.
:::

::::

---

### Projects

::::: matrix

:::: row

::: column
#### Pruning Library

- First end-to-end project.

:::

::: column
asdf
:::

::::

:::: row

::: column
asdf
:::

::: column
asdf
:::

::::
:::::

---

### 1. Model optimization w.r.t. hardware prior to compilation

- Adjust weights, do fine-tuning, make architectural changes.
- Study, experiment, and design compression algorithms & recipes, e.g., pruning, quantization, etc.
- Develop compression libraries and SDKs.
- Support requests from important customers and internal teams on challenging model compression tasks.

---

### 2. Architectural Studies

- Make sure new architectures can be run efficiently on our chips.
- Understand what specialized operations need to be supported on next-gen design.
- Reports directly to CTO via weekly meetings.

---

## Projects Overview

- Pruning library: first end-to-end project.
  - Software development & python skills.
  - System design.
  - Document & example.
  - CI/CD
- Compression-aware training for LLMs
  - `transformers` ecosystem.
  - Distributed training, DeepSpeed, FSDP.
- Activation Sparsity
  - Research project
  - Literature study, algorithm implementation, experiment design & execution
  - PoC, MVP
- Post-Training Compression
  - Develop quantization recipe.
  - Transformation-based quantization.

---

---

- Muti Chung (鍾慕提), software engineer at Ambarella.
- Ambarella products: video applications, AI acceleration, e.g., CNN, VLM.
    - Consumer devices: GoPro, DJI, Insta360.
    - Automotive: L2+ to L4.
    - IoT applications: security cameras.
- Top-level/Frontline of the AI deployment software stack.

    > Maybe use official diagram?

    1. Architectural studies: make sure the architectures can be run efficiently on our chips, or understand what specialized operations need to be supported on next-gen design.
        - My team reports directly to CTO via weekly meetings.
    2. Optimize model w.r.t. hardware prior to any compilation, i.e., at the python/pytorch level.
        - Adjust weights, do fine-tuning, make architectural changes.
        - Study, experiment, and design compression algorithms & recipes, e.g., pruning, quantization, etc.
        - Develop compression libraries and SDKs.
        - Support requests from important customers and internal teams on challenging model compression tasks.
- Past projects overview
    - Pruning library: first end-to-end project.
        - Software development & python skills.
        - System design.
        - Document & example.
        - CI/CD
    - Compression-aware training for LLMs
        - `transformers` ecosystem.
        - Distributed training, DeepSpeed, FSDP.
    - Activation Sparsity
        - Research project
        - Literature study, algorithm implementation, experiment design & execution
        - PoC, MVP
    - Post-Training Compression
        - Develop quantization recipe.
        - Transformation-based quantization.
- Personal
    - Motivation
    - Interests

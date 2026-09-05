<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0C0F,100:F5A623&height=180&section=header&text=Mithil%20Maske&fontSize=54&fontColor=E8E6E1&animation=fadeIn&fontAlignY=36&desc=neural%20networks%20%E2%80%A2%20vision-language%20%E2%80%A2%20agentic%20systems&descSize=14&descAlignY=58&descColor=F5A623" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=19&pause=1200&color=F5A623&center=true&vCenter=true&width=680&lines=Training+multimodal+models+on+a+single+8GB+GPU;Vision-language+models%2C+from+scratch;Forgery+%26+watermark+detection;Agentic+systems+and+dev+tooling+on+LLMs" alt="Typing SVG" />
</p>

<p align="center">
  <b>I build neural networks from scratch and write down exactly how they work.</b><br/>
  <sub>Research prototypes to production pipelines. Most of it runs on hardware you probably already own.</sub>
</p>

<p align="center">
  <a href="https://www.mithilmaske.com/"><img src="https://img.shields.io/badge/Portfolio-1F2430?style=for-the-badge&logo=vercel&logoColor=F5A623" /></a>
  <a href="https://medium.com/@mithilmaske"><img src="https://img.shields.io/badge/Medium-1F2430?style=for-the-badge&logo=medium&logoColor=F5A623" /></a>
  <a href="https://www.youtube.com/@mithilmaske"><img src="https://img.shields.io/badge/YouTube-1F2430?style=for-the-badge&logo=youtube&logoColor=F5A623" /></a>
  <a href="https://www.linkedin.com/in/mithil-maske/"><img src="https://img.shields.io/badge/LinkedIn-1F2430?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI0Y1QTYyMyI+PHBhdGggZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMDEtMi4wNjMtMi4wNjUgMi4wNjQgMi4wNjQgMCAxMTIuMDYzIDIuMDY1em0xLjc4MiAxMy4wMTlIMy41NTVWOWgzLjU2NHYxMS40NTJ6TTIyLjIyNSAwSDEuNzcxQy43OTIgMCAwIC43NzQgMCAxLjcyOXYyMC41NDJDMCAyMy4yMjcuNzkyIDI0IDEuNzcxIDI0aDIwLjQ1MUMyMy4yIDI0IDI0IDIzLjIyNyAyNCAyMi4yNzFWMS43MjlDMjQgLjc3NCAyMy4yIDAgMjIuMjI1IDB6Ii8+PC9zdmc+" /></a>
  <a href="https://huggingface.co/Mithil-AI"><img src="https://img.shields.io/badge/Hugging%20Face-1F2430?style=for-the-badge&logo=huggingface&logoColor=F5A623" /></a>
</p>

<p align="center">
  <a href="https://www.mithilmaske.com/"><img src="https://img.shields.io/badge/%20-Talk%20to%20my%20AI%20%E2%86%92-1F2430?style=for-the-badge&logo=chatbot&logoColor=0B0C0F&labelColor=F5A623" /></a>
</p>

---

## ◆ Selected work

<table>
<tr>
<td width="50%" valign="top">

### [QuadEmbed](https://github.com/mithilai/QuadEmbed)

Text, image, audio and video in **one shared 768-dim embedding space**, trained end to end on a single RTX 4060 (8GB). An independent from-scratch reproduction of the GELATO architecture from Jina AI.

`PyTorch` · `multimodal` · `contrastive`

[![PyPI](https://img.shields.io/pypi/v/quadembed?style=flat-square&color=F5A623&labelColor=0B0C0F&label=pypi)](https://pypi.org/project/quadembed/)
[![HF](https://img.shields.io/badge/%F0%9F%A4%97-quadembed--nano-F5A623?style=flat-square&labelColor=0B0C0F)](https://huggingface.co/Mithil-AI/quadembed-nano)

</td>
<td width="50%" valign="top">

### [SEAL](https://github.com/mithilai/SEAL)

Self-Adapting Language Models in a **single readable file**. The model writes its own fine-tuning data, tests whether it actually helped, and reinforces the habit. ReST-EM on 8GB, degrades gracefully to CPU.

`LoRA` · `QLoRA` · `PEFT` · `ReST-EM`

[![Paper](https://img.shields.io/badge/arXiv-2506.10943-F5A623?style=flat-square&labelColor=0B0C0F)](https://arxiv.org/abs/2506.10943)
[![Write-up](https://img.shields.io/badge/write--up-Medium-F5A623?style=flat-square&labelColor=0B0C0F)](https://medium.com/@mithilmaske/how-i-implemented-self-adapting-language-models-with-lora-and-qlora-on-an-rtx-4060-3d7e16a4d19e)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [VisionCore-MCP](https://github.com/mithilai/visioncore-mcp)

Gives Claude Desktop **eyes through your webcam**. Local vision via Ollama, temporal memory of the last five minutes, no cloud vision APIs. An MCP server that installs in three steps.

`MCP` · `Ollama` · `local-first`

[![Write-up](https://img.shields.io/badge/write--up-Medium-F5A623?style=flat-square&labelColor=0B0C0F)](https://medium.com/@mithilmaske/giving-claude-eyes-building-a-world-aware-agent-with-model-context-protocol-and-local-vision-5c1ecedc01c4)

</td>
<td width="50%" valign="top">

### [GForge](https://github.com/mithilai/gforge-python)

Engineering governance at the one place every change passes through: the commit. A **managed global Git hook** that stops credentials entering history, across every repo on a team.

`Python` · `git-hooks` · `secret-scanning`

[![PyPI](https://img.shields.io/pypi/v/gforge-python?style=flat-square&color=F5A623&labelColor=0B0C0F&label=pypi)](https://pypi.org/project/gforge-python/)

<sub>Python port. Original design and detection engine by Gaurang Joshi, Shrey Tandel and Dwij Acharya.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Spread-Spectrum Watermarking](https://github.com/mithilai/spread-spectrum-watermark)

The invisible fingerprinting technique Netflix and music labels use to catch pirates, implemented cleanly in Python. Embed, detect, and everything that breaks it.

`DSP` · `watermarking` · `NumPy`

[![Write-up](https://img.shields.io/badge/write--up-Medium-F5A623?style=flat-square&labelColor=0B0C0F)](https://medium.com/@mithilmaske/spread-spectrum-watermarking-the-invisible-signature-in-your-audio-video-7f3f5805cba7)

</td>
<td width="50%" valign="top">

### [YOLOv8 License Plate](https://github.com/mithilai/YOLOv8-License-Plate)

An end-to-end edge detection pipeline: train, optimise, deploy to a Raspberry Pi. Native Keras and KerasCV, **no Ultralytics licence required**.

`KerasCV` · `TFLite` · `CoreML` · `edge`

[![Write-up](https://img.shields.io/badge/write--up-Medium-F5A623?style=flat-square&labelColor=0B0C0F)](https://medium.com/@mithilmaske/i-built-a-license-plate-detector-that-runs-on-a-raspberry-pi-no-ultralytics-license-required-7b1d15eaa069)

</td>
</tr>
</table>

<p align="center"><a href="https://github.com/mithilai?tab=repositories">All repositories &rarr;</a></p>

---

## ◆ Stack

<table>
<tr>
<td align="right" width="120"><b><sub>MODELLING</sub></b></td>
<td><img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow&theme=dark" height="36" /> &nbsp;<sub>Transformers · PEFT · KerasCV · ONNX</sub></td>
</tr>
<tr>
<td align="right"><b><sub>AGENTS</sub></b></td>
<td><img src="https://skillicons.dev/icons?i=fastapi,docker&theme=dark" height="36" /> &nbsp;<sub>MCP · CrewAI · LangChain · Ollama · n8n</sub></td>
</tr>
<tr>
<td align="right"><b><sub>PRODUCT</sub></b></td>
<td><img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,firebase&theme=dark" height="36" /> &nbsp;<sub>Vercel · Supabase</sub></td>
</tr>
</table>

---

## ◆ Writing

<!-- BLOG:START -->- **[I Built a Multimodal Embedding Model From Scratch on an RTX 4060 &lpar;Text, Image, Audio, and Video…](https://medium.com/@mithilmaske/i-built-a-multimodal-embedding-model-from-scratch-on-an-rtx-4060-text-image-audio-and-video-ab1fef04f1cd?source=rss-8d19d7c20101------2)**<br/><sub>August 22, 2026</sub>
- **[How I implemented Self-Adapting Language Models with LoRA and QLoRA on an RTX 4060](https://medium.com/@mithilmaske/how-i-implemented-self-adapting-language-models-with-lora-and-qlora-on-an-rtx-4060-3d7e16a4d19e?source=rss-8d19d7c20101------2)**<br/><sub>July 25, 2026</sub>
- **[How to Build a Vision Language Model from Scratch Using Q-Former, Contrastive Learning, and LoRA](https://medium.com/@mithilmaske/how-to-build-a-vision-language-model-from-scratch-using-q-former-contrastive-learning-and-lora-feeaa42af0b0?source=rss-8d19d7c20101------2)**<br/><sub>June 27, 2026</sub>
- **[Spread-Spectrum Watermarking: The Invisible Signature in Your Audio &amp; Video](https://medium.com/@mithilmaske/spread-spectrum-watermarking-the-invisible-signature-in-your-audio-video-7f3f5805cba7?source=rss-8d19d7c20101------2)**<br/><sub>June 20, 2026</sub>
<!-- BLOG:END -->

<sub><a href="https://medium.com/@mithilmaske">Everything on Medium &rarr;</a></sub>

---

## ◆ From the channel

<table><tr><!-- YOUTUBE:START --><td align="center" width="33%"><a href="https://www.youtube.com/watch?v=eBeUKFJUwGk"><img src="https://img.youtube.com/vi/eBeUKFJUwGk/hqdefault.jpg" width="100%"/></a><br/><a href="https://www.youtube.com/watch?v=eBeUKFJUwGk"><b>n8n Beginner Tutorial Build Your First Automation Workflow</b></a></td><td align="center" width="33%"><a href="https://www.youtube.com/watch?v=j5ncEWpeVd4"><img src="https://img.youtube.com/vi/j5ncEWpeVd4/hqdefault.jpg" width="100%"/></a><br/><a href="https://www.youtube.com/watch?v=j5ncEWpeVd4"><b>How to Self Host n8n on Your Computer Using Docker Beginner Guide | Part - 2</b></a></td><td align="center" width="33%"><a href="https://www.youtube.com/watch?v=a07_8acSG-M"><img src="https://img.youtube.com/vi/a07_8acSG-M/hqdefault.jpg" width="100%"/></a><br/><a href="https://www.youtube.com/watch?v=a07_8acSG-M"><b>How to Self Host n8n on Your Computer Using Docker Beginner Guide | Part - 1</b></a></td><!-- YOUTUBE:END --></tr></table>

<sub><a href="https://www.youtube.com/@mithilmaske">Subscribe on YouTube &rarr;</a></sub>

---

## ◆ Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mithilai/mithilai/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mithilai/mithilai/output/github-contribution-grid-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/mithilai/mithilai/output/github-contribution-grid-snake.svg" />
  </picture>
</p>

<p align="center">
  <sub>Open to research collaborations and applied AI work &mdash; <a href="https://www.linkedin.com/in/mithil-maske/">reach me on LinkedIn</a>.</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:F5A623,100:0B0C0F&height=100&section=footer" />
</p>

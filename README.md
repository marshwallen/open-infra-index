<!-- markdownlint-disable first-line-h1 -->
<!-- markdownlint-disable html -->
<!-- markdownlint-disable no-duplicate-header -->

<div align="center">
  <img src="https://github.com/deepseek-ai/DeepSeek-V2/blob/main/figures/logo.svg?raw=true" width="60%" alt="DeepSeek-Open-Infra" />
</div>
<hr>

# hello deepseek open infra

## Open-Source Week 20250224-20250228
We're a small team @deepseek-ai pushing our limits in AGI exploration.

Starting next Monday, we'll open-source 5 repos – one daily drop – not because we've made grand claims, 
but simply as developers sharing our small-but-sincere progress with full transparency.

These are humble building blocks of our online service: documented, deployed and battle-tested in production. 
No vaporware, just code that moved our tiny moonshot forward.

Why? Because every line shared becomes collective momentum that accelerates the journey.
Daily unlocks begin in 72 hours. No ivory towers - just pure garage-energy and community-driven innovation 🔧
Stay tuned – let's geek out in the open together.

## 2024 AI Infrastructure Paper (SC24)   
### Fire-Flyer AI-HPC: A Cost-Effective Software-Hardware Co-Design for Deep Learning
The rapid progress in Deep Learning (DL) and Large Language Models (LLMs) has exponentially increased demands of computational power and bandwidth. This, combined with the high costs of faster computing chips and interconnects, has significantly inflated High Performance Computing (HPC) construction costs. To address these challenges, we introduce the **Fire-Flyer AI-HPC** architecture, a synergistic hardware-software co-design framework and its best practices. For DL training, we deployed the Fire-Flyer 2 with 10,000 PCIe A100 GPUs, achieved performance approximating the DGX-A100 while reducing costs by half and energy consumption by 40%. We specifically engineered HFReduce to accelerate allreduce communication and implemented numerous measures to keep our Computation-Storage Integrated Network congestion-free. Through our software stack, including HaiScale, 3FS, and HAI-Platform, we achieved substantial scalability by overlapping computation and communication. Our system-oriented experience from DL training provides valuable insights to drive future advancements in AI-HPC.  
<a href="https://dl.acm.org/doi/10.1109/SC41406.2024.00089"><b>📄 Paper Link</b></a>
<a href="https://arxiv.org/abs/2408.14158"><b>📄 Arxiv Paper Link</b></a>
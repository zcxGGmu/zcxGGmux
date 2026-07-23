<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/zcxGGmu/zcxGGmu/main/assets/system-trace-dark.gif">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/zcxGGmu/zcxGGmu/main/assets/system-trace-light.gif">
    <img alt="animated systems trace" src="https://raw.githubusercontent.com/zcxGGmu/zcxGGmu/main/assets/system-trace-light.gif">
  </picture>
</p>

<p align="center">
  <sub>animated systems trace - real contribution data remains unmodified</sub>
</p>

<div align="center">

<pre><code>zcxGGmu@github:~$ ./boot

target     : hypervisor / linux kernel / llm systems
runtime    : C | Rust | Python | TypeScript
working_on : RISC-V KVM | Ferrovisor | code agents

keep the stack small, the feedback loop tight,
and the abstractions honest.
</code></pre>

</div>

---

<details open>
<summary><code>kernel.log</code></summary>

<pre><code>current focus
|- RISC-V KVM: perf, extensions, dirty logging, nested virtualization
|- Ferrovisor: memory-safe type-1 hypervisor experiments in Rust
|- Linux internals: guests, VMIDs, gstage mapping, IOMMU paths
\\- AI agents: code understanding, open-source workflows, tool use
</code></pre>

</details>

<details open>
<summary><code>selected work</code></summary>

- [Ferrovisor](https://github.com/zcxGGmu/Ferrovisor) - memory-safe, high-performance type-1 hypervisor built in Rust
- [linux-riscv](https://github.com/zcxGGmu/linux-riscv) - Linux kernel source tree and RISC-V exploration
- [kvm-riscv](https://github.com/zcxGGmu/kvm-riscv) - Linux KVM RISC-V workspace
- [Astraeus](https://github.com/zcxGGmu/Astraeus) - platform for autonomous AI agents
- [CodeInsights](https://github.com/zcxGGmu/CodeInsights) - LLM-powered multi-agent platform for open-source contributions
- [TinyLLMInfer-rs](https://github.com/zcxGGmu/TinyLLMInfer-rs) - small Rust inference engine experiment

</details>

<details>
<summary><code>patch trail</code></summary>

- [riscv: Add perf support to collect KVM guest statistics from host side](https://lore.kernel.org/all/cover.1728980031.git.zhouquan@iscas.ac.cn/)
- [RISC-V: perf/kvm: Add reporting of interrupt events](https://lore.kernel.org/all/9693132df4d0f857b8be3a75750c36b40213fcc0.1726211632.git.zhouquan@iscas.ac.cn/)
- [RISC-V: KVM: Enable ring-based dirty memory tracking](https://lore.kernel.org/all/cover.1749810735.git.zhouquan@iscas.ac.cn/)
- [RISC-V: KVM: Add Zicfiss/Zicfilp support](https://lore.kernel.org/all/cover.1764509485.git.zhouquan@iscas.ac.cn/)
- [KVM: riscv: Support enabling dirty log gradually in small chunks](https://lore.kernel.org/all/20251103062825.9084-1-dayss1224@gmail.com/)

</details>

<p align="center">
  <sub>systems at the bottom, agents at the edge</sub>
</p>

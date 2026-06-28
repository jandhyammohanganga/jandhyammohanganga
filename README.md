# <div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&pause=1000&color=00C2FF&center=true&vCenter=true&width=800&lines=Hi+%F0%9F%91%8B+I'm+Jandhyam+Mohan+Ganga;VLSI+Design+%26+Verification+Engineer" alt="Typing SVG" />

<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40"/>

</div>

---

## 🧑‍💻 About Me

```
┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   Name     : Jandhyam Mohan Ganga                                   │
│   Role     : VLSI Design & Verification Engineer (Fresher)          │
│   Focus    : RTL Design · Functional Verification · UVM             │
│   Tools    : QuestaSim · VCS · Design Compiler · Xilinx ISE         │
│   OS       : Linux (primary) · Windows                              │
│   Writing  : Weekly VLSI history posts on LinkedIn                  │
│   Open To  : Full-time VLSI Design / Verification roles             │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

I'm a passionate VLSI engineer who builds **end-to-end verification environments** — from writing synthesizable RTL to achieving functional coverage closure with UVM. I believe a chip is only as good as its verification, and I take that seriously.

> *"Don't just design the chip. Prove that it works."*

---

## ⚡ Technical Skills at a Glance


| Domain | Skills |
|--------|--------|
| 🔷 **RTL Design** | Synthesizable Verilog, FSM Design, Digital Logic, Combinational & Sequential Circuits, Memory Architectures |
| ✅ **Verification** | UVM (Agent, Driver, Monitor, Scoreboard, Sequencer), Constrained Random, Functional Coverage, SVA, RAL Model |
| 🔌 **Protocols** | APB, UART, AHB · *(AXI4 — in progress)* |
| 🛠️ **EDA Tools** | Mentor QuestaSim, Synopsys VCS, Synopsys Design Compiler, Xilinx ISE |
| 💻 **Environment** | Linux CLI, Tcl scripting, Git, GitHub |

---

## 🚀 Featured Projects

---

### 📡 [APB-Based UART Master Core — RTL & Full UVM Verification](https://github.com/jandhyammohanganga/APB-based-UART-Master-Core-RTL-Verification)

> *A complete, layered UVM verification environment for UART over APB — from architecture to coverage closure*

**The Problem:** UART is one of the most widely used serial communication protocols in embedded SoCs. Before silicon tape-out, every edge case — baud rate mismatches, framing errors, overrun conditions, and register misbehavior — must be caught in simulation.

**What I Built:**

| Component | Description |
|---|---|
| 🧱 **UVM Environment** | Full layered env: Agent → Driver → Monitor → Scoreboard → Coverage Collector |
| 📋 **RAL Model** | Register Abstraction Layer for APB register reads/writes and backdoor access |
| 🎲 **Constrained Random Tests** | Corner-case sequences targeting APB transfer edge cases and UART framing errors |
| ✅ **SVA Assertions** | Protocol compliance checks and bus timing assertions on APB signals |
| 📊 **Coverage Closure** | Functional coverage groups for all key operational scenarios |

**Tech Stack:** `SystemVerilog` · `UVM` · `SVA` · `APB Protocol` · `UART` · `Mentor QuestaSim`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jandhyammohanganga/APB-based-UART-Master-Core-RTL-Verification)

---

### 🚦 [Router 1×3 — RTL Design & Self-Checking Verification](https://github.com/jandhyammohanganga/Router-1X3-Design-and-Verification)

> *Synthesizable RTL packet router with automated pass/fail testbench*

**The Problem:** Routers are fundamental building blocks in SoCs and NoC architectures. Getting the packet routing logic right — especially under concurrent multi-channel traffic — requires rigorous verification.

**What I Built:**

| Component | Description |
|---|---|
| 🔷 **RTL Design** | Synthesizable 1×3 packet router in Verilog with dynamic destination-based routing |
| 🧪 **Self-Checking TB** | Testbench with embedded reference model — auto pass/fail, no manual waveform inspection |
| 🔁 **Scenario Coverage** | Verified all 3 output channels, back-pressure, simultaneous requests, and boundary packets |

**Tech Stack:** `Verilog HDL` · `RTL Design` · `Self-Checking Testbench` · `Mentor QuestaSim`

[![View Repo](https://img.shields.io/badge/View_Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jandhyammohanganga/Router-1X3-Design-and-Verification)

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=jandhyammohanganga&show_icons=true&theme=tokyonight&hide_border=true"/>

<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=jandhyammohanganga&theme=tokyonight&hide_border=true"/>

</div>

---

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jandhyammohanganga&layout=compact&theme=tokyonight&hide_border=true"/>

</div>

---

## 📈 Contribution Graph

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=jandhyammohanganga&theme=tokyo-night)](https://github.com/jandhyammohanganga)

---

## 🌱 Currently Learning

```systemverilog
// My 2026 Learning Stack

class mohan_learning_plan;

  // Actively studying
  string advanced_uvm[] = '{"UVM Factories", "Callbacks", "Virtual Sequences", "Phasing"};
  string crcdv[]        = '{"Coverage-Driven Verification", "Functional Coverage Closure"};
  string abv[]          = '{"Assertion-Based Verification", "Formal Property Checking"};

  // In progress
  string protocols[]    = '{"AXI4-Full", "AXI4-Lite", "AXI4-Stream", "PCIe Basics"};

  // Up next
  string scripting[]    = '{"Python for log parsing", "Tcl for EDA automation"};
  string soc_concepts[] = '{"Low-Power Design", "Clock Domain Crossing (CDC)"};

endclass
```

---

## 🎯 2026 Goals

- [x] Build a complete UVM environment with RAL model *(done — UART project)*
- [x] Achieve functional coverage closure on a real protocol *(done — APB/UART)*
- [ ] Complete **60 RTL Challenges** and publish solutions on GitHub
- [ ] Build and publish a **full AXI4 UVM Verification Environment**
- [ ] Add **Python/Tcl automation scripts** to all projects
- [ ] Write **10 detailed LinkedIn articles** on VLSI verification techniques
- [ ] Land a role at a **product semiconductor company**

---

## ✍️ I Write About VLSI

Every week, I post on LinkedIn exploring the key milestones, innovations, and engineers that shaped the semiconductor industry.

🔗 **[Follow me on LinkedIn →](https://www.linkedin.com/in/jandhyam-mohan-ganga/)**

---

## 🤝 Let's Connect

I'm actively looking for **VLSI Design & Verification** roles (fresher / entry-level) and always happy to connect with fellow engineers, mentors, and recruiters in the semiconductor space.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jandhyam-mohan-ganga/)
[![Gmail](https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jandhyammohanganga82663@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jandhyammohanganga)
[![Profile Views](https://komarev.com/ghpvc/?username=jandhyammohanganga&style=for-the-badge&color=0077B5&label=Profile+Views)](https://github.com/jandhyammohanganga)

</div>

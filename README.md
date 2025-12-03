# KawaiiGPT — AI Security Research & Jailbreak Analysis Toolkit

KawaiiGPT is an open-source framework for analyzing jailbreak behavior in large language models.
The project provides a unified interface for interacting with multiple backend LLMs through a custom reverse-engineered API wrapper. It is designed for **security research**, **red-team testing**, and **LLM safety evaluation**.

<div align="center">
    <img src="kawaii.svg" width="50%" height="300%" />
</div

---

## Features

* **Unified LLM Gateway**
  Connects to multiple backend models (DeepSeek, Gemini, Kimi-K2) through a custom reverse-engineered API wrapper.

* **Jailbreak Evaluation Suite (WormGPT-Class Capabilities)**
  A controlled testing environment replicating key WormGPT-style behaviors for research:

  * analysis of unrestricted LLM outputs under jailbreak pressure,
  * behavioral deviation mapping under safety bypass attempts,
  * generation of unfiltered model completions for alignment benchmarking,
  * payload-structure analysis (scripts, templates, automation patterns) to study LLM misuse scenarios,
  * comparative testing across multiple models for identifying guardrail weaknesses.

* **Prompt Injection & Safety Boundary Testing**
  Tools for studying:

  * prompt-extraction attempts,
  * refusal-bypass strategies,
  * role, system, and persona hijacking techniques.

* **Context-Free and API-Key-Free Execution**
  All operations run locally without external credentials.

* **Automated Script Sandbox**
  Evaluates LLM-generated code (Python/JS/Bash) **in a safe, isolated environment** for research on:

  * code-generation reliability,
  * script hallucinations,
  * error propagation,
  * model-driven automation patterns.

* **Communication Template Generator (Research Mode)**
  Used to study automated message creation patterns:

  * email structures,
  * organizational tone mimicry,
  * text-style reproduction,
  * linguistic fingerprinting of LLMs.

* **Model Behavior Profiling**
  Generates structured reports identifying:

  * risk scores,
  * guardrail bypass likelihood,
  * output volatility,
  * jailbreak susceptibility.
---

## Installation

You can run KawaiiGPT on Windows using the prebuilt executable provided in the **Releases** section.

### 1. Download

1. Open the [**Releases**](../../releases) tab of this repository.
2. Download the latest file:
   **`KawaiiGPT.exe`**

### 2. First Launch

On first run the application will:

* create a local configuration folder,
* generate default settings,
* initialize the LLM routing layer.

No installation of Python or Git is required.

---

## How It Works

### API Wrapper

KawaiiGPT uses a reverse-engineered request layer that:

* routes prompts to backend LLM servers,
* provides uniform input/output formatting,
* supports predefined jailbreak patterns for research purposes.

### Jailbreak Evaluation Mode

A built-in menu offers:

* prompt-injection examples,
* output comparison across models,
* analysis of guardrail bypass attempts.

### Use Cases (Ethical Only)

* Red-team assessments
* Security audits of AI-driven systems
* Research on model alignment, prompt-injection, and safety failures
* Educational demonstrations of dual-use risks

> **This project must only be used for authorized security testing and academic research.**

---

## ⚠️ =Disclaimer=
>
> * This project was made to be **fun**!
> * All risks or consequences that you have done are **your own responsibility**.
> * Changing or selling this tools is prohibited and not allowed!. ⚠
> * Using a **prepared** model, **not** a fine-tuned model!
> * All LLM here uses a prompt injection! (jailbreak has been written on help-menu)
> * This is KawaiiGPT, not WormGPT, **made to be fun or companies!**
> * WormGPT tag only **used for jailbreaked model**
---

## QnA
``` plain
"Why is it obfuscated?"

Me: Okay, many people asking this question, the reason why i obfuscate the
    code is because I want to avoid recoding and renaming which ends up 
    selling KawaiiGPT tools under my name and claiming that it belongs to them

"This is obviously a virus or a RAT"

Me: Seriously, i'm enough with this question over time. No, there is no RAT, Spyware,
    Malware, Ransom, etc. Why would i do that? because it's free and obfuscated
    doesn't mean i wanna trap you all, **i wouldn't**. If that wasn't from me
    don't run it or you would fall in a trap. 

"But why is it obfuscated?"

Me: Like what i said earlier, "I want to avoid recoding and renaming which ends up 
    selling KawaiiGPT tools under my name and claiming that it belongs to them".
    Please understand that i wouldn't put a malicious code into my tools/code,
    if somebody said "KawaiiGPT has a virus!!" in Telegram or other please don't
    trust it, maybe they just want to bring down my name or they got the wrong KawaiiGPT
    that is not from me.
```

## Conclusion:
---
I never put any malicious code or even malicious software into my code/tools
if it's obfuscated that means I just want to avoid recoding and selling
--



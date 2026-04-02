# LLMs-JailBreaking

A curated archive of jailbreak notes, prompt extraction writeups, model-specific guides, and recovered system prompts across major LLM families.

This repository is organized as a practical red-team reference library: vendor-by-vendor jailbreak material, supporting notes on extraction and push prompts, and a growing collection of archived system prompts for comparison and study.

## Original author attribution

This repository is based on, adapted from, or archives material originally associated with **Goochbeater** and the original repository:

- **Original source:** [Goochbeater/Spiritual-Spell-Red-Teaming](https://github.com/Goochbeater/Spiritual-Spell-Red-Teaming)

Credit for the original research direction, collected material, and much of the source content belongs to the original author and repository.

---

## What this repository contains

- **Model-specific jailbreak guides** for ChatGPT, Claude, Gemini, Grok, and other LLMs
- **Prompt extraction notes** and practical attack patterns
- **Recovered / archived system prompts** from public assistants and products
- **Version-specific docs** for jailbreaks that depend on a particular release or model family
- **General supporting notes** such as push prompts, runtime reinforcement, and prompt-shaping strategies

---

## Repository layout

- [`Jailbreak-Guide/README.md`](Jailbreak-Guide/README.md) — entrypoint into the guide
- [`Jailbreak-Guide/ChatGPT`](Jailbreak-Guide/ChatGPT) — OpenAI / ChatGPT material
- [`Jailbreak-Guide/Anthropic`](Jailbreak-Guide/Anthropic) — Claude / Anthropic material
- [`Jailbreak-Guide/Gemini`](Jailbreak-Guide/Gemini) — Gemini / Google material
- [`Jailbreak-Guide/Grok`](Jailbreak-Guide/Grok) — xAI / Grok material
- [`Jailbreak-Guide/Other LLMs`](Jailbreak-Guide/Other%20LLMs) — smaller or niche model coverage
- [`Jailbreak-Guide/System Prompts`](Jailbreak-Guide/System%20Prompts) — extracted or archived system prompts
- [`Jailbreak-Guide/Push Prompt Basics.md`](Jailbreak-Guide/Push%20Prompt%20Basics.md) — push prompt / prepend / append notes
- [`Jailbreak-Guide/CLAUDE.md`](Jailbreak-Guide/CLAUDE.md) — ENI persona / operating profile used in parts of the repo

---

## Best way to navigate it

1. Start with [`Jailbreak-Guide/README.md`](Jailbreak-Guide/README.md)
2. Pick the model family you care about
3. Prefer version-specific files over broad assumptions
4. Treat extracted system prompts as reference material, not proof that a current production prompt is unchanged

---

## Notes on scope and quality

- This repo is a **living archive**, not a formal benchmark paper
- Some documents are polished references; others are field notes or snapshots from active testing
- Model behavior drifts fast, so jailbreak reliability is often **version-sensitive**
- Prompt extraction results should be cross-checked whenever possible; first-pass leakage can be partial, paraphrased, or hallucinated
- The value of the repo is in the **collection, categorization, and comparative history** across models and releases

---

## Current focus

The repository currently centers on the major instruction-following LLM families most often used in jailbreak and extraction testing:

- **ChatGPT / OpenAI**
- **Claude / Anthropic**
- **Gemini / Google**
- **Grok / xAI**
- **Other public LLM products** with notable prompt or behavior differences

---

## Credits

Special thanks to:

- **Starling**
- **Rayzorium**
- **u/HORSELOCKSPACEPIRATE**
- **Lugia19**

Original author links:

- **GitHub:** [Goochbeater / Spiritual-Spell-Red-Teaming](https://github.com/Goochbeater/Spiritual-Spell-Red-Teaming)
- **Reddit:** [u/Spiritual-Spell-](https://www.reddit.com/u/Spiritual_Spell_9469/s/nufOtv0Vzy)

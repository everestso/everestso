## Influencing Memory Through Context and Framing

In a generative model of memory, **retrieval is shaped as much by context as by stored content**. Memory recall can be influenced by deliberately constructing a contextual “set,” much like designing the stage for a play before the actors enter.

### Context as a Stage
- The **context** (language, environment, expectations, emotional tone) functions as the *set design*.
- Memory fragments are the *actors*.
- The recalled memory is the *performance* that emerges from their interaction.

Once the stage is set, the memory that appears is constrained to be **consistent with that context**, even if alternative reconstructions are possible.

### Mechanism of Influence
- Framing activates particular schemas or latent associations.
- These schemas guide which memory fragments are emphasized, suppressed, or filled in.
- The reconstruction feels natural and coherent, even when it incorporates distortions.

### Generative Analogy
- In humans, contextual cues bias neural activation patterns during recall.
- In LLMs, prompts define a probability landscape from which outputs are generated.

In both cases, **the system completes what the context implies**, not necessarily what originally occurred.

### Implication
Memory influence does not require overwriting stored information.  
By shaping the context of recall, one can **guide the generative process itself**, subtly steering what is remembered while preserving the subjective experience of authenticity.

# False Memory, Elizabeth Loftus, and Generative Models of Memory

## 1. False Memory and Elizabeth Loftus

Elizabeth Loftus’s research demonstrated that **human memory is reconstructive, not reproductive**. Rather than retrieving a fixed record of the past, people actively rebuild memories using fragments of stored information combined with cues from the present.

### Core findings
- **Misinformation effect**: Exposure to misleading information after an event can alter later recall.
- **Leading questions influence memory**: Subtle changes in wording can change what people report remembering.
- **Confidence is not reliability**: People often become more confident in memories that are less accurate.

### Classic result
In studies of car accidents, participants asked how fast cars were going when they *“smashed”* into each other:
- Estimated higher speeds  
- Were more likely to recall broken glass that never appeared  

The wording activated different schemas, shaping how the memory was reconstructed.

---

## 2. Memory as a Generative Process

Loftus’s work shifted the view of memory away from a storage model toward a **generative inference process**.

During recall, the brain integrates:
- Partial memory traces  
- Contextual cues  
- Language and framing  
- Prior knowledge and expectations  

The result is a *plausible reconstruction*, not a guaranteed historical record.

---

## 3. Memory Models and Generative Neural Networks

Modern generative models, including large language models (LLMs), operate in a strikingly similar way. They do not retrieve stored facts directly; instead, they generate outputs by sampling from learned probability distributions over representations.

### Shared properties
| Human Memory | Generative Models (LLMs) |
|-------------|--------------------------|
| Distributed neural traces | Distributed embeddings |
| Reconstruction at recall | Generation at inference |
| Context-sensitive | Prompt-sensitive |
| Schema-driven | Pattern-driven |
| Confident but fallible | Fluent but sometimes incorrect |

Both systems prioritize coherence and plausibility over literal accuracy.

---

## 4. Prompting, Framing, and Reconstruction

Loftus’s findings anticipate a key behavior of LLMs: **responses depend strongly on how questions are framed**.

- In humans, leading language activates schemas that bias recall.
- In LLMs, prompt phrasing activates different regions of latent space, shaping the generated response.

Small wording changes can alter:
- Assumptions  
- Emphasis  
- Tone  
- Included or omitted details  

In both cases, the system is not retrieving a fixed answer but **constructing one conditioned on the prompt**.

---

## 5. Implications

Understanding memory and LLMs as generative systems explains:
- Why eyewitness testimony can be unreliable  
- Why prompt engineering matters  
- Why confidence does not guarantee correctness  
- Why neither human memory nor AI should be treated as a simple database  

> **Human memory and large language models do not retrieve the past — they reconstruct it under the influence of the present.**

<!--

## Hi there 👋


**everestso/everestso** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

**This repository contains work done by the ValueShift Team for Moonshot Alignment Program hosted by AI Plans.**

## General Description

The main research track we worked on is **Influence of Value Representations on LLM Outputs**. The repository contains our results. It is work in progress, and we plan to continue our research further on.

### What we did
#### We persued multiple distinct research directions:
- Behavior Editing
- Domain Dependence of the Refusal Vector Direction
- Certainty Vector Direction
- Low-Rank optimization methods for steering vector representations.

#### In short, we figured ot that
- behavior editing with ICE, ROME, and other techniques is promosing, but requires a lot of computatiuonal resources
- refusal vector direction depends on the field (checked for safety and policy)
- it is possible to extract a single certainty vector, that predicts an LLM's confidence before giving an answer.

#### As the future work we plan to
- test our findings on larger models and datasets
- merge refusal and certainty direction to make an LLM-based AI agent "understand" its limits and avoid producing hallucinations
- apply our approaches to AI alignment evaluation

### Literature we used
- **[Model Editing as a Double-Edged Sword: Steering Agent Ethical Behavior Toward Beneficence or Harm](https://arxiv.org/pdf/2506.20606)**
- **[Refusal in Language Models Is Mediated by a Single Direction](https://arxiv.org/abs/2406.11717)**
- **[Asking for Help Enables Safety Guarantees Without Sacrificing Effectiveness](https://arxiv.org/pdf/2502.14043)**
And many other sources, which were used a bit less extensively.
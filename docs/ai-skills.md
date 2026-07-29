# AI skills

Fabric AI skills let users ask natural-language questions against selected data. They should be treated as governed analytical capabilities: choose the dataset deliberately, define the intended audience, and validate how prompts are interpreted before wider use.

```mermaid
flowchart LR
  U[Business user question] --> S[Fabric AI skill]
  S --> M[Selected data model]
  M --> A[Answer with governed context]
```

## Workshop focus

The source workshop introduces AI skill concepts and the creation flow. Use it to understand the feature, then adapt the configuration to your own workspace, data model, and governance controls.

## Operating guidance

- Select data that has clear ownership, appropriate permissions, and understandable business definitions.
- Restrict access using workspace and item permissions; an AI skill must not become a path around data governance.
- Test representative questions for accuracy, ambiguity, and confidential-data exposure.
- Document expected answers, unsupported questions, and a support owner before broad rollout.

Read the source [AI Skills guide](https://github.com/Cloud2BR-MSFTLearningHub/MS-Fabric-Essentials-Workshop/blob/main/AzurePortal/3_AISkills.md) alongside [Microsoft's AI skill documentation](https://learn.microsoft.com/fabric/data-science/concept-ai-skill) for current feature status and limitations.
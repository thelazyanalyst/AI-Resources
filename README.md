# AI Resources

A curated, searchable collection of 78 resources for cybersecurity consultants building AI fluency — from foundational concepts through to advanced agentic architectures and AI coding harnesses.

**Live site:** [thelazyanalyst.github.io/AI-Resources](https://thelazyanalyst.github.io/AI-Resources/)

## Learning Progression

Resources follow a structured path designed for associate-to-senior consultants (1-5 years in GRC roles):

1. **AI Fluency Baseline** (Beginner) — AI taxonomy, OWASP Top 10 for LLMs, MITRE ATLAS, NIST AI RMF
2. **Machine Learning Principles** (Beginner) — How models learn, training data risks, bias, data poisoning
3. **Generative AI** (Beginner–Intermediate) — Transformers, prompt engineering, deepfakes, content authenticity
4. **LLM Internals** (Intermediate) — Tokenization, attention, prompt injection, jailbreaking, data leakage
5. **Knowledge & RAG** (Intermediate) — Embeddings, vector databases, RAG security, access control
6. **Agent Tool Calling** (Intermediate–Advanced) — Function calling, tool abuse, privilege escalation
7. **Agentic Swarms & ReAct** (Advanced) — Multi-agent orchestration, trust boundaries, governance
8. **AI Harnesses** (Intermediate–Advanced) — Claude Code, OpenAI Codex, Copilot, Cursor security

## Filtering

The site supports filtering by:
- **Category**: Standards & Regulations, Generative AI, Machine Learning, Secure AI & Security, Education & Learning, Articles & Whitepapers, Models & Tools, and more
- **Difficulty**: Beginner, Intermediate, Advanced
- **Search**: Full-text search across titles, descriptions, owners, and difficulty levels

## Resource Count by Category

| Category | Count |
|---|---|
| Secure AI & Security | 28 |
| Models & Tools | 19 |
| Education & Learning | 14 |
| Generative AI | 10 |
| Machine Learning | 6 |
| Articles & Whitepapers | 3 |
| Standards & Regulations | 1 |

## Contributing

To add a resource, edit the `resources` array in `index.html`:

```javascript
{
    title: "Resource Name",
    url: "https://example.com",
    description: "2-3 sentences about what it is and why it's valuable",
    owner: "Organization",
    category: "Category Name",
    difficulty: "Beginner|Intermediate|Advanced"
}
```

---

Created with Claude Code

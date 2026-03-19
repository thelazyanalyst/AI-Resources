# AI Resources

A curated, searchable collection of 78 resources for cybersecurity consultants building AI fluency — from foundational concepts through to advanced agentic architectures and AI coding harnesses.

**Live site:** [thelazyanalyst.github.io/AI-Resources](https://thelazyanalyst.github.io/AI-Resources/)

## Two-Section Layout

The site is split into two tabs:

### Resources Tab
Reference materials: OWASP guides, NIST frameworks, vendor documentation, security articles, tools, whitepapers, and reports. Filterable by category and difficulty.

### Learning Track Tab
Structured curriculum organized into 8 progressive modules:

1. **AI Fluency Baseline** (Beginner) — AI taxonomy, cloud AI certifications, foundational courses
2. **ML Principles** (Beginner) — How models learn, training data risks, bias, data poisoning
3. **Generative AI** (Beginner–Intermediate) — GenAI fundamentals, prompt engineering, responsible AI
4. **LLM Internals** (Intermediate) — Tokenization, attention, fine-tuning, prompt injection
5. **Knowledge & RAG** (Intermediate) — Embeddings, vector databases, RAG pipelines
6. **Agent Tool Calling** (Intermediate–Advanced) — Function calling, agent frameworks, tool integration
7. **Agentic Swarms & ReAct** (Advanced) — Multi-agent orchestration, trust boundaries, governance
8. **AI Harnesses** (Intermediate–Advanced) — Claude Code, OpenAI Codex, Copilot, Cursor security

## Filtering

Both tabs support:
- **Difficulty**: Beginner, Intermediate, Advanced
- **Search**: Full-text search across titles, descriptions, owners, and difficulty levels

The Resources tab additionally supports:
- **Category**: Standards & Regulations, Generative AI, Machine Learning, Secure AI & Security, Education & Learning, Articles & Whitepapers, Models & Tools, and more

## Contributing

To add a resource, edit the `resources` array in `index.html`:

```javascript
{
    title: "Resource Name",
    url: "https://example.com",
    description: "2-3 sentences about what it is and why it's valuable",
    owner: "Organization",
    category: "Category Name",
    difficulty: "Beginner|Intermediate|Advanced",
    section: "resources|learning",
    module: "1. AI Fluency Baseline"  // only for learning track resources
}
```

---

Created with Claude Code

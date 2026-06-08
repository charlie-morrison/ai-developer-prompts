# AI Developer Prompts

A curated collection of battle-tested prompts for software developers working with AI coding assistants and APIs. Each prompt has clear placeholders — fill in your specifics and go.

Covers: code generation, debugging, refactoring, architecture, documentation, DevOps, AI integration, data processing, frontend, and advanced patterns.

## Code Generation

### Function from Description
```
Write a [language] function that [description].
Requirements:
- Input: [types and descriptions]
- Output: [expected return type]
- Edge cases: [list edge cases to handle]
- No external dependencies
Include type hints and a brief docstring.
```

### Generate Unit Tests
```
Write comprehensive unit tests for this function using [framework]:

[function code]

Cover:
- Happy path (2-3 cases)
- Edge cases (empty input, null, boundary values)
- Error cases (invalid input, expected exceptions)
- Use descriptive test names that explain the scenario
```

### REST API Endpoint
```
Create a [framework] REST API endpoint:
- Method: [GET/POST/PUT/DELETE]
- Path: [/api/v1/resource]
- Request body: [schema]
- Response: [expected response schema]
- Auth: [auth method]
- Validation: validate all input fields
- Errors: return appropriate HTTP status codes with messages
```

## Debugging

### Root Cause Analysis
```
This code produces [wrong output / error]:

[code]

Expected: [expected behavior]
Actual: [actual behavior]

Steps so far: [what you've already checked]

Find the root cause. Show the fix. Explain WHY it went wrong.
```

### Performance Profiling
```
This [language] code is too slow ([current time] for [input size]):

[code]

Analyze:
1. Time complexity of each section
2. Bottlenecks (nested loops, redundant calls, memory allocation)
3. Specific optimization with expected speedup
4. Benchmark comparison approach
```

## Refactoring

### Simplify Complex Conditional
```
Simplify this conditional logic while preserving behavior:

[code with nested if/else, complex boolean expressions]

Show the simplified version and explain each transformation.
```

### Modernize Legacy Code
```
Modernize this [language] code to use current best practices:

[old code]

Target: [language version / framework version]
Preserve: all existing behavior and test compatibility
Show a diff-style comparison of old vs new.
```

## Architecture

### System Design
```
Design a [type] system:
- Scale: [users/requests/data volume]
- Requirements: [latency, availability, consistency trade-offs]
- Constraints: [budget, team size, existing tech stack]
- Key flows: [list 2-3 critical user flows]

Include: component diagram, data flow, tech stack choices with rationale.
```

### Database Schema
```
Design a database schema for [domain]:
- Entities: [list main entities]
- Key queries: [list 3-5 most common queries]
- Scale: [expected row counts per table]
- Engine: [PostgreSQL / MySQL / MongoDB / etc.]

Include: table definitions, indexes, foreign keys.
Explain normalization decisions and query optimization.
```

## Documentation

### Technical README
```
Write a README for this project:

[project description or main file]

Include:
- One-sentence description
- Quick start (install + first command)
- Configuration table
- API reference (if applicable)
- Contributing guidelines
- License

Tone: direct, no filler. Developer audience.
```

## DevOps

### Dockerfile
```
Write an optimized Dockerfile for this [language] application:

[application structure / entry point]

Requirements:
- Multi-stage build (minimize image size)
- Non-root user
- Health check
- .dockerignore suggestions
- Security: no secrets in image layers
```

### CI/CD Pipeline
```
Write a [GitHub Actions / GitLab CI / etc.] pipeline for:
- Language: [language/framework]
- Steps: lint → test → build → deploy
- Deploy target: [where]
- Secrets needed: [list]
- Trigger: [push to main / PR / tag]
Include caching for dependencies.
```

## AI Integration

### Prompt Engineering
```
Optimize this prompt for [model]:

Current prompt: [your prompt]
Current output quality: [what's wrong]
Desired output: [example of ideal response]

Rewrite with:
- Clear role/context setting
- Specific output format instructions
- Few-shot examples if needed
- Constraints to prevent common failures
```

### RAG Pipeline
```
Design a RAG (Retrieval-Augmented Generation) pipeline:
- Documents: [type and volume]
- Queries: [example user questions]
- Response format: [how answers should look]
- Budget: [API budget constraints]

Include: chunking strategy, embedding model choice,
vector store, retrieval approach, prompt template.
```

## Data Processing

### ETL Pipeline
```
Write a [Python/Node/etc.] ETL script:
- Source: [CSV/API/database]
- Transform: [cleaning rules, calculations, mappings]
- Destination: [database/file/API]
- Volume: [row count]
- Schedule: [frequency]
Handle: errors, duplicates, schema changes, logging.
```

## Frontend

### React Component
```
Build a React component for [description]:
- Props: [list props with types]
- State: [what state it manages]
- Events: [user interactions to handle]
- Style: [CSS modules / Tailwind / styled-components]
- Accessibility: keyboard navigation, ARIA labels, focus management
```

## Advanced Patterns

### Rate Limiter
```
Implement a rate limiter in [language]:
- Algorithm: [token bucket / sliding window / fixed window]
- Limit: [N requests per time window]
- Scope: [per-user / per-IP / global]
- Storage: [in-memory / Redis / database]
Include: thread safety, distributed support, graceful degradation.
```

### WebSocket Server
```
Build a WebSocket server in [language/framework]:
- Events: [list events to handle]
- Auth: [how clients authenticate]
- Rooms/channels: [grouping logic]
- Reconnection: [client retry strategy]
- Scale: [expected concurrent connections]
Include: heartbeat/ping-pong, error handling, graceful shutdown.
```

---

## Full Toolkit

This repo contains **20 free prompts**. The full **AI Developer Toolkit** includes:

- **108 prompts** across 10 categories
- **Interactive AI Cost Calculator** (compare 30+ models, estimate monthly bills)
- **Model Selection Guide** (decision matrix, provider comparison, optimization strategies)
- **API Quick-Start Templates** (Python, JavaScript, cURL for OpenAI, Anthropic, Google)
- **One-Page Cheat Sheet** (endpoints, auth, token limits, pricing, retry strategies)

Updated for 2026 with GPT-4.1, Claude 4, Gemini 2.5, o3/o4-mini, and more.

**[Get the Full Toolkit ($19)](https://charliemorrison.lemonsqueezy.com/checkout/custom/f5dfc7d7-2d06-4550-970f-8c715dd05f48?signature=424e547c5d2dab672ebb46c0e9f6de2467c8a2bf2f0d64952cc7108a43b41df0)**

> 💸 **15% off** with code `GH15` at checkout.

---

## Other Resources

- [Freelancer's AI Business Kit ($24)](https://charliemorrison.lemonsqueezy.com/checkout/custom/a68cd84a-7d2e-437c-b219-d1d3df0ffcb0?signature=69594f47c47ba1faee6786b13f68507f7f6f6ce4c9427c305a259fad727d39ea) — client templates, pricing calculators, proposal generators
- [Social Media AI Mastery ($17)](https://charliemorrison.lemonsqueezy.com/checkout/custom/6ad32981-0524-4fb9-a98a-05639f3508ba?signature=a189206c1516b4f55c48c6584a72832bd692d334e79dbb916a990161cd6b68f7) — content calendars, engagement prompts, analytics templates
- [Content Creator's AI Toolkit ($15)](https://charliemorrison.lemonsqueezy.com/checkout/custom/d3f9ea94-8a53-470f-968b-f3d8ceb24074?signature=8737c6cd3a7ab7afca1d5fe8e558976f13ddac58be06ca28c74fba428d032b9d) — writing prompts, SEO templates, repurposing workflows

## License

MIT License. Use these prompts however you want.

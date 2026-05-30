## Evaluation

I evaluated two versions of my FAQ agent:

- `faq_agent_v1`: simple helpful assistant prompt
- `faq_agent_v2`: stricter prompt requiring search usage and citations

I used manual questions and AI-generated questions. Each answer was logged and then evaluated with an LLM judge using a checklist.

The checklist evaluated:

- instruction following
- relevance
- clarity
- citation/source usage
- completeness
- search tool usage

### Results

| Agent | Overall Score |
|---|---:|
| `faq_agent_v1` | replace-after-running |
| `faq_agent_v2` | replace-after-running |

The better prompt was `replace-after-running` with an overall score of `replace-after-running`.

# HLD Case Studies

A collection of high-level system design case studies covering requirements, architecture, data models, scaling, and trade-offs.

## Case Studies

| Case Study | Summary | Design Document |
| --- | --- | --- |
| [News Feed](#news-feed) | Design a personalized, scalable news feed system. | [Open in browser](https://softcodeln.github.io/HLD-Case-Studies/NewsFeed-HLD_Case_Study.html) |

## News Feed

- **Difficulty:** Intermediate
- **Focus areas:** Feed generation, fan-out on write/read, caching, ranking, and scalability
- **Design document:** [News Feed HLD Case Study](https://softcodeln.github.io/HLD-Case-Studies/NewsFeed-HLD_Case_Study.html)

## Adding a Case Study

Use the following structure for each new HLD case study:

1. Add one row to the **Case Studies** table.
2. Add a dedicated section below the table with the difficulty, focus areas, and design document link.
3. Add or publish the HTML or Markdown design document in the repository.
4. Keep the case name consistent in the table, section heading, and document link.

### Template

```markdown
## Case Studies

| Case Study | Summary | Design Document |
| --- | --- | --- |
| [News Feed](#news-feed) | ... | [Open in browser](...) |
| [Case Name](#case-name) | Brief description | [Open in browser](...) |

## Case Name

- **Difficulty:** Beginner / Intermediate / Advanced
- **Focus areas:** Relevant scalability and architecture topics
- **Design document:** [Case Name HLD Case Study](...)
```

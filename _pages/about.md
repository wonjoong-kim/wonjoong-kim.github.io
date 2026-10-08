---
layout: about
title: Home
permalink: /
subtitle: Ph.D. student at <a href='https://www.kaist.ac.kr/en/'>KAIST</a>

# To show a profile photo: add it as assets/img/prof_pic.jpg, then uncomment the four lines below.
profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular

selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: false # adds a vertical scroll bar if there are more than 3 news items
  limit: # leave blank to include all the news in the `_news` folder
  collapse_after: 5 # show this many items, then a "Show N more" button. Leave blank to show all

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Ph.D. student in the [Graduate School of Data Science](https://gsds.kaist.ac.kr/) at [KAIST](https://www.kaist.ac.kr/en/), where I am fortunate to be advised by [Prof. Chanyoung Park](https://dsail.kaist.ac.kr/professor/).

I do research with my awesome colleagues at [DSAIL](https://dsail.kaist.ac.kr) (Data Science and Artificial Intelligence Lab).

---

🔬 Core Research Focus

**Self-Evolving LLM Agents**

I work on **how LLM agents can be evaluated and improved from their own experience**, so that an agent becomes more reliable on long, multi-step tasks without a person hand-tuning it after every failure.

`Keywords: Agentic AI, Tool-Use Agents, Multi-Agentic System, Self-Evolving Agents, Harness Optimization`

**Key Focus:**

- **Trajectory Evaluation**: Judging the whole reasoning trajectory of a tool-using agent, not only whether its final answer is correct.
- **Multi-Turn Agent Optimization**: Step-level reward signals that tell an agent which intermediate steps helped, instead of a single outcome reward at the end.
- **Harness Optimization**: Automatically improving the harness around the model (its prompts, tool configurations, and control logic) from the agent's execution traces.

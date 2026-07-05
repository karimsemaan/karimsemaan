## Hey, I'm Karim 👋

I build machine learning models and the products that ship them. I'm the founder of SSS Tech, an applied-AI studio in Boston, where I take models from a first notebook all the way to a deployed product: the data and architecture, the agent pipelines, the evals and guardrails, the infra, and the interface on top.

Before SSS Tech I led AI delivery for enterprise clients, and got my start in cloud and DevOps at Harvard, Orna Therapeutics, and Vocadian. I'm finishing an MS in AI at Northeastern and hold the AWS Machine Learning – Specialty certification.

Most of what I work on comes back to one question: does the model actually work, and can you prove it? That's why a good chunk of my open-source is about measuring LLMs, not just shipping them.

## What I'm building at SSS Tech

- **Bastion** is a multi-tenant SaaS that runs cybersecurity-maturity assessments through a staged Claude pipeline, scored against NIST CSF 2.0, CIS, ISO 27001, SOC 2, and CMMC. Every finding cites its evidence, and a human signs off before anything ships. Built on Next.js, Supabase (row-level tenant isolation), and Pinecone.
- **Birthday Buddy** is an AI concierge over WhatsApp that plans and runs birthdays start to finish.
- **[karimnsemaan.me](https://karimnsemaan.me)** is my site. You can talk to Kirby there, a grounded chatbot that runs against honesty checks in CI so it doesn't make things up.

## Open-source: measuring LLMs

- **[agent-tool-eval](https://github.com/karimsemaan/agent-tool-eval)** tests whether giving an LLM a calculator actually helps it on grade-school math, and whether the smaller models even use it. Plain CoT vs a ReAct agent, across Llama 3B/8B/70B.
- **[llm-confidence-calibration](https://github.com/karimsemaan/llm-confidence-calibration)** checks whether models mean it when they state a confidence. When it says 80%, is it right 80% of the time? MMLU, Llama 1B to 70B.
- **[calibration-kit](https://github.com/karimsemaan/calibration-kit)** is a small toolkit for measuring and fixing calibration: log-loss, Brier, ECE, plus Platt and isotonic scaling.
- **[kickcast-worldcup](https://github.com/karimsemaan/kickcast-worldcup)** predicts World Cup matches with a 7-model ensemble and a PyTorch net over a leakage-safe, 21k-match dataset. Comes with a [live dashboard](https://kickcast-dashboard.vercel.app).

I'm open to AI/ML roles and the occasional outside project. Reach me at [karimnsemaan.me](https://karimnsemaan.me), on [LinkedIn](https://www.linkedin.com/in/karimnsemaan), or at semaankarim1@gmail.com.

## Hi, I’m Akash Mittal

I work on research-shaped AI engineering problems in optimal transport, multimodal learning, and reliable AI systems.

My strength is naive, stubborn questioning. I question assumptions even when they are stated confidently or treated as given. I like translating technical concepts into language I can actually reason with, then testing whether the idea still survives in code.

My thesis work focused on warm-start algorithms for bipartite matching and optimal transport. Here are the projects I'm currently working on in my personal time:

**[State-Conditioned Synthetic Supervision (SCSS)](https://github.com/akashm776/otco)**, formerly OTCO, asks: can we store reusable functions that generate useful training signals, rather than relying only on stored examples? The key is the learner’s state: what helps one model at one point in learning may hurt it at another. I started with OT-based synthetic hard negatives; the current experiments use matched CLIP continuations to separate geometric hardness, immediate update effects, and sustained learning outcomes. The broader goal is to learn when and how to use generated supervision—not to assume that more synthetic data is better. Reduced data requirements and reliable downstream gains remain open questions. [Research program](https://github.com/akashm776/otco/blob/main/docs/research-program.md) · [Experiments and results](https://github.com/akashm776/otco/blob/main/docs/experiment-ledger.md).

**exactness-triage** comes from a similar instinct. Agent memory and context compaction often lean on summarization because LLMs are good at it. I wanted to test the assumption behind that move: some tool outputs may contain exact, load-bearing details (a key name, a failing diff, a specific error string) that should be preserved before compression, not reconstructed after summarization.

The common thread: I like questioning the default interpretation of a technique, then building the smallest experiment I can to see whether the idea survives contact with reality.

You can reach me at [akashmit28@gmail.com](mailto:akashmit28@gmail.com).

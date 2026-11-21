# MultiDems Shared Task at EACL 2027: Summarization of Citizen Consultations

The MultiDems Shared Task involves generating summaries from multilingual citizen proposals and associated votes from real-world consultations across Europe. Generated summaries will be evaluated using democratically grounded criteria. 

## Data

The dataset is based on the **Eurhope citizen consultation** and contains:
- **393 citizen proposals** across **9 languages**.
- **934 participants** and their preferences over the proposals.
- A complete **934 × 393 voting matrix**, combining observed and inferred votes.

Two files are provided:

- **`proposals.csv`**: Contains the proposal IDs, original texts, and languages.
- **`participants_proposals_matrix.csv`**: Contains participants' preferences for every proposal, encoded as +1 (support) or −1 (oppose). Missing votes have been inferred using a [preference inference model](https://arxiv.org/pdf/2609.02990).

The dataset has been completely anonymized to protect participants' privacy.

## Task

The objective is to generate **concise, coherent summaries** of citizen proposals and their associated voting data.

Participants are free to use any summarization approach.

Further details on the task and instructions for submitting generated summaries will be **announced soon**.

## Evaluation & Baselines

Generated summaries will be evaluated using democratically grounded criteria, examining how well they represent citizens' preferences and perspectives.

The **exact evaluation metrics will be described here soon**, alongside the release of the evaluation scripts and baseline implementation.

For more information on the MultiDems Workshop, visit the [website](https://multidems.github.io/).

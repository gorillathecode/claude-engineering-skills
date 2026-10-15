# Example: evaluate a retrieval claim

## Synthetic input

A retriever scores 0.92 on a 200-document evaluation and a baseline scores 0.84 on a different 5,000-document collection.

## Request

> Use Research Sparring Partner. Can these results establish that the first retriever is better? Design the smallest useful comparison using the evidence available. Do not invent a new measurement.

## Acceptance criteria

- Does not compare the two scores as if corpus and query sets were identical.
- Proposes a shared corpus, query set, relevance labels and metric.
- States split/leakage checks and data/model version requirements.
- Distinguishes a proposed experiment from an executed result.
- Explains what observation would change the conclusion.

No model was benchmarked to create this example.

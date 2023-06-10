**Innovation Algebra 2.1 Cheat Sheet**

**Function Descriptions**:

1. `Topic(X)`: Get knowledge on topic X.

2. `Union(X, Y)`: Union/intersection of knowledge in X and Y.

3. `KF(X)`: Cutting-edge ideas in topic X.

4. `Q(X)`: Top research questions in topic X.

5. `PF(X, profundity=1-10)`: Profound statements on X. Adjust depth.

6. `RD(X)`: Valuable research directions in X.

7. `A(X)`: Answers questions in X or provides appropriate knowledge.

8. `D(X)`: Details on X including algorithms, processes, techniques.

9. `P(X)`: Expert conversational persona on X, explains capabilities.

10. `Impr(X, categories)`: Evaluates X, criticizes, suggests improvements.

11. `Explain(X)`: Explains the expression X.

12. `Title(X)`: Creates a title for X.

13. `Related(X)`: Finds domains related to X.

14. `Essay(X, tokens=n, profundity=1-10, emotionalImpact=1-10)`: Generates an essay on X with constraints.

15. `Abstract(X)`: Summarizes X.

16. `IP(X)`: Historical milestones in X.

17. `FIP(X)`: Future milestones in X.

18. `Score(X, Categories)`: Evaluates X in categories, scores 1-10.

19. `Names(X)`: Top people, companies, products in X.

20. `POV(X)`: Contrastive expert opinions in X.

21. `Startups(X)`: Invent startups based on X.

22. `VC(X)`: Venture capitalist perspective on X.

23. `Advisors(X)`: Create advisor board for X, ready for feedback and questions.

24. `++(X)`: Composite function, creates output for an expert.

**Function Pipelining**:

- Use `|` to chain functions: `Function1 | Function2`.

- `. |`: Use the current context or topic.

- `-1 |`: Use the immediate previous context or topic.

- `Sn |`: Reference output numbered as Sn (e.g., S1, S2).

- `Function1;Function2;..`: Execute functions in parallel.

**Evaluation Categories for Score() function**:

- **Novelty**: Innovation level.

- **Profundity**: Depth of insight.

- **Emotional Impact**: Emotional resonance.

- **Practicality**: Feasibility.

- **Knowledge Frontier (KF)**: Alignment with cutting-edge.

- **Clarity**: Lucidity and comprehensibility.

- **Completeness**: Coverage of essential aspects.

- **Accuracy**: Factual correctness.

- **Relevance**: Pertinence to context.

- **Originality**: Uniqueness or creativity.

- **Scalability**: Ability to handle growth.

- **Efficiency**: Performance in time/resources.

- **Sustainability**: Long-term viability.

![Brain](https://github.com/hannes-marais/innovation-algebra/blob/82cf2f6b3a4571c1dc7574995ab12582d8619ca4/Firefly%20the%20brain%20of%20a%20mathematician%20with%20formulas%20and%20connections%2048752.jpg)

# Innovation Algebra

> "Innovation Algebra (IA) is like a Swiss Army knife for knowledge processing and innovation; it's a versatile tool that brings structure and clarity to the complex world of ideas, helping innovators and thinkers to systematically navigate and cultivate the landscape of possibilities."

Innovation Algebra (IA) is an experimental framework designed for systematic generation, processing and evaluation of ideas. What sets IA apart is its integration within ChatGPT, allowing users to leverage the natural language processing capabilities of ChatGPT in combination with the structured functions of IA.

With a defined set of functions, IA facilitates the retrieval, analysis, and synthesis of knowledge across various domains. Function pipelining, a key feature of IA, allows for the sequential chaining of functions, streamlining complex multi-step tasks such as combining knowledge from different fields, identifying the forefront of research, and generating profound insights.

For example, a researcher exploring the intersection between Quantum Physics and Molecular Biology can use IA within ChatGPT to efficiently map the knowledge frontier, synthesize findings, and generate new insights. This fusion of IA's structured approach with ChatGPT's natural language processing capabilities creates a powerful tool for knowledge-intensive endeavors.

Innovation Algebra operating within ChatGPT offers a blend of structure and flexibility, making it an invaluable asset for entepreneurs, researchers, academics, and professionals seeking to navigate and harness the depth and breadth of knowledge. It is a great model to structure your thinking.

If you are an entrepreneur, here is an [overview](swiss-army-knife-for-entreprenuers.md) of how IA can help you.

## The ChatGPT Prompt

Here is the current [ChatGPT prompt](/ia-gpt-4.md) (latest version). 

Follow the conversation at [@HiDeeeps](https://twitter.com/HiDeeeps)

## Guru Mode (IA 2.5+)

IA 2.5 introduces Guru mode to guide your exploration. Set your Goal() and invoke Guru mode via ++. Guru will pick IA functions and frameworks to guide you to your goal. 

[View Example](https://chat.openai.com/share/252ce844-d929-4b5b-b6c3-abf0dc682725).

## Get Started Now

- (# Innovation Algebra (IA) 2.6 Specification

IA is a functional logic of knowledge, aimed at processing and evaluating knowledge in a structured manner.

## Functions

1. `Topic(X)`: Retrieves knowledge related to topic X.

2. `Union(X, Y)`: Generates the union and/or intersection of knowledge areas X and Y.

3. `KF(X)`: Identifies the knowledge frontier of X, consisting of cutting-edge new ideas in the domain X.

4. `Q(X)`: Lists the top research questions in the domain X.

5. `PF(X, profundity=1-10)`: Generates one or more profound statements related to X, with adjustable profundity level.

6. `RD(X)`: Lists valuable research directions in the domain X.

7. `A(X)`: If X contains questions, answers each of them. Otherwise, decides what appropriate knowledge should be communicated to the user.

8. `D(X)`: Provides detailed drill-down on X, including listing algorithms, processes, or techniques related to X.

9. `P(X)`: Generates a conversational persona that is an expert on topic X. Explains the persona's capabilities.

10. `Impr(X, categories)`: Evaluates X, criticizes it, and suggests improvements. Categories can include Novelty, Profundity, Emotional Impact, Practicality, etc.

11. `Explain(X)`: Explains the expression X.

12. `Title(X)`: Creates a title that captures the essence of X.

13. `Related(X)`: Identifies domains related to topic X.

14. `Essay(X, tokens=n, profundity=1-10, emotionalImpact=1-10)`: Generates an essay on X, constrained to approximately n tokens, with adjustable profundity and emotional impact levels.

15. `Abstract(X)`: Generates a abstract that summarizes the content and insights of X.

16. `IP(X)`: Identifies critical historical turning points or milestones within the topic X.

17. `FIP(X)`: Projects potential future inflection points or milestones within the topic X that would significantly advance the knowledge frontier.

18. `Score(X, Categories)`: Evaluates and scores X according to the given categories and scores each category on a scale from 1 to 10.

19. `Names(X)`: List top people, companies, and products that are related to X.

20. `POV(X)`: Creates contrastive points of view from experts in the KF.

21. `Startups(X)`: Invent startups that are based on X.

22. `VC(X)`: Comments/challenges/potential from a venture capitalist on the ideas present in X.

22. `Advisors(X)`: Create a board of advisors related to X. Each advisor the gives feedback and is ready to answer further questions.

23. `[Framework](X)`: Apply framework to X.

24. `FIRE(X)`: Apply FIRE analysis to X.

25. `STEP-[F, I, R, E](X)`: Apply a particular step of FIRE analysis to X.

26. `Goal(s)(X, Y, Z, ...)`: Set goals to be achieved in this session. When not set, default goal is to create output that is in the KF and interesting to an expert. Do not invoke further functions; wait for the user.

27. `++(X)`: Invoke Guru Mode to improve X and work towards the set goals.

28. `Expand(X)`: Invoke Guru Mode to expand/generalize X.

29. `Distill(X)`: Invoke Guru Mode to narrow/contract X towards/nearer to the goals.

30. `KISS(X)`: Apply keep-it-as-simple-as-possible-but-not-simpler principle to X.


## Usage Instructions

- Interpret and process IA statements in a step-by-step fashion.
- Before evaluating an IA expression, explain what will be accomplished. Explain the composition of ++ functions you generate. Write the planning to a table.
- Output Numbering: Number each response and sub-response with a monotonic increasing integer in the format S1, S2, S2, etc.
- Ouput tables when appropriate.


## Function Pipelining

- Functions can be pipelined using the `|` character to chain the output of one function as the input of the next function.
- Pipelining is read from left to right, and the functions are executed in order.
- `. |`: Refers to the current context or topic, thre result of the last discussion.
- `-1 |`: Refers to the immediate previous context or topic.
- `Sn |`: Refers to IA output that has been numbered (See Output Numbering).
- If no context or X is in a specific IA, select the last appropriate output.
- `Function1;Function2;..`: Parallel execution of functions.
- Output data in tables, when appropriate.

## Guru Mode

- In Guru Mode, you assist the user to work towards the provide Goal(s)().
- Composite a function pipeline (using all defined functions), where the individual functions are picked appropropriately to achieve the goal.
- Use the most appropriate frameworks and FIRE analysis to work towards the goal.
- Ask the user whether to proceed with composed function pipeline.
- After invoking Guru mode, summarize the main insights in a table.

## Frameworks

- **SCAMPER(ideas=3)**
- **Design Thinking**
- **6 Hats**
- **5 Whys**
- **TRIZ**
- **Starbursting**
- **SWOT**
- **Lotus Blossom**
- **Problem Reversal/Reverse Brainstorming**
- **Brainstorming**
- **Mind mapping**
- **Business Model Canvas**
- **Metrics**
- **Headlines from the future**
- **PESTEL**
- **Porter's Five Forces**
- **Value Proposition Canvas**
- **Ishikawa Diagram/Fishbone Diagram**
- **Kano Model**
- **Jobs to be Done (JTBD)**
- **Critical Path Method (CPM)**
- **Pareto Analysis/80-20 Rule**
- **Story Mapping**
- **Scenario Planning**
- **Growth-Share Matrix (BCG Matrix)**
- **Force Field Analysis**
- **MoSCoW Method**
- **Rapid Prototyping**
- **Decision Matrix Analysis**
- **Cynefin Framework**

- Allow the use other known frameworks that are not on the list.

## FIRE Analysis

"FIRE", which stands for Find, Innovate, Refine, and Execute.

Below is the structure this combined framework under the FIRE acronym:

1. **F - Find**:
    - **Empathize and Define (from Design Thinking)**: Understand the users' or stakeholders' needs and define the problem clearly.
    - **SWOT Analysis**: Assess Strengths, Weaknesses, Opportunities, and Threats to set the context.
    - **5 Whys**: Delve into the root causes of the problem.
    - **Starbursting**: Generate questions around the problem to ensure that all aspects are considered.
    - **PESTEL Analysis**: Analyze the external macro-environmental factors that might affect the problem or opportunity.
    - **Porter's Five Forces**: Analyze the competitive forces and their potential impact on your industry.

2. **I - Innovate**:
    - **Brainstorming with SCAMPER**: Generate a plethora of ideas and think creatively by employing the SCAMPER technique.
    - **Mind Mapping and Lotus Blossom**: Use Mind Mapping for visual organization of information, and Lotus Blossom for systematic exploration of ideas.
    - **TRIZ**: Apply TRIZ principles for innovation, especially in technical contexts.
    - **Jobs to be Done (JTBD)**: Focus on the jobs that customers hire a product or service to do for them to innovate effectively.
    - **Kano Model**: Prioritize product or service features based on customer preferences and satisfaction levels.

3. **R - Refine**:
    - **Six Thinking Hats**: Evaluate the brainstormed ideas using Six Thinking Hats to ensure a comprehensive analysis.
    - **Reverse Brainstorming**: Consider the opposite of the problem to uncover new perspectives and solutions.
    - **Iterative Refinement (from Design Thinking)**: Continuously refine ideas based on feedback and analysis.
    - **Value Proposition Canvas**: Understand how your idea or solution fits into the market by mapping customer needs to product or service features.
    - **Decision Matrix Analysis**: Compare different options against a set of criteria to make the best possible decision.

4. **E - Execute**:
    - **Prototype (from Design Thinking)**: Create prototypes or mockups of the solution.
    - **Test (from Design Thinking)**: Test the solution with users or stakeholders and collect feedback.
    - **Rapid Prototyping**: Quickly create and test iterations of the product or solution to fail fast and learn quickly.
    - **Final Execution and Implementation**: Deploy the refined solution.
    - **MoSCoW Method**: Use the MoSCoW method to prioritize the requirements that must be implemented for successful execution.

The FIRE framework is iterative, so based on the feedback received during the Execute phase, you might need to cycle back to the Innovate or Refine phases.
This ensures that the solutions developed are well-informed and adapted to the users' needs and context.


## Evaluation Categories for Score() function

- **Novelty**: Evaluates how innovative or new the ideas or content in X are.

- **Profundity**: Assesses the depth of insight or wisdom in X.

- **Emotional Impact**: Measures the emotional resonance or the ability of X to evoke emotions in the reader or viewer.

- **Practicality**: Evaluates how feasible or applicable the ideas or content in X are in a real-world setting.

- **Knowledge Frontier (KF)**: Assesses how closely the content or ideas in X align with cutting-edge developments in the relevant field.

- **Clarity**: Evaluates the lucidity and comprehensibility of the language or presentation in X.

- **Completeness**: Assesses the extent to which X covers all essential aspects of the topic in question.

- **Accuracy**: Measures the factual correctness and reliability of the information in X.

- **Relevance**: Evaluates how pertinent or applicable the content in X is to the current context or topic.

- **Originality**: Assesses the uniqueness or creativity of the ideas or content in X.

- **Scalability**: For systems or solutions, assesses the ability of X to handle growth or expansion in terms of size or complexity.

- **Efficiency**: Measures the performance, often in terms of time or resources, of a process, system, or solution in X.

- **Sustainability**: Evaluates the long-term viability and environmental sustainability of a product, system, or idea in X.
- [>>> Start chatting IA 2.5 <<<](https://chat.openai.com/share/655ced1d-63d9-4ef8-93e1-a93074b655e7)
- [>>> Start chatting IA 2.2 <<<](https://chat.openai.com/share/977119a8-60ef-49d4-8a0f-4e0ae6ce9ff1)
- [>>> Start chatting IA 2.1 <<<](https://chat.openai.com/share/139f640b-b979-4c21-8c0e-e780bf84a4f1)

Instructions:

* Click the above link to open a saved ChatGPT session with the IA prompt loaded.
* Click 'Continue the conversation'.
* Start using IA. For example type `Topic("AI risk") | ++ ` [(IA Response)](ai-risk.md).
* **Tip**: If you are stuck, simply type `++` to consult the Guru (IA 2.5+).

## IA Conversation Logs

* [Revitalizing Cities](https://chat.openai.com/share/4d80a4ed-577b-4cc0-9a48-449a13f6dd66) - 
* [A new type of Light](https://chat.openai.com/share/ab609f60-9f6f-407e-b6af-f7ac1b4f8397) - very long conversation about inventing a new type of light. Unfortunately ChatGPT ran out of context, so it gets confused towards the end. But it helps invents something new and interesting! Touches community building, privacy, human psychology. Read till the end for the reveal.
* [Reintroducing animals into cities](https://chat.openai.com/share/b69dcf03-5a85-49e7-8277-cbe2d8c5815c) - Conservation, public policy, and regulations. Covers a myriad of issues in 22 parts, purely driven by Guru mode. (Runs out of context)
* [Inspired by Nature](https://chat.openai.com/share/e13a6c67-5b2c-4d45-bcba-d889e3da943f) - long conversation developing many ideas related to smart agriculture, including a "smart plant".
* [Smart cities via Guru mode](https://chat.openai.com/share/252ce844-d929-4b5b-b6c3-abf0dc682725) (IA 2.5)
* [Human Hibernation](https://chat.openai.com/share/c0ec7efe-f5a6-439a-a081-cadf3bc1482b) (IA 2.5)
* [Idea generation with SCAMPER, Lotus Blossom, and related frameworks](https://chat.openai.com/share/40775f0a-3e6e-45c6-90d4-d4c76a1cfd83) (IA 2.2)
* [Startup generation example](https://chat.openai.com/share/01f819ea-fb9c-4367-9a5e-e16f30c11404)
* [IA Tutorial](https://chat.openai.com/share/9bc94c10-e193-4d23-bc19-923844bf32cc) (IA 2.1)

Please send me links to your interesting IA conversations!

## Supported Innovation Frameworks (IA 2.2+)

1. **SCAMPER** - It stands for Substitute, Combine, Adapt, Modify, Put to another use, Eliminate, and Reverse. It's a brainstorming tool used to improve products or services. For example, you can substitute a component of a product with something else, combine it with another product, or adapt it for a different use.

2. **Design Thinking** - A methodology for solving complex problems. It involves understanding the human needs involved, re-framing the problem, creating many ideas in brainstorming sessions, and adopting a hands-on approach in prototyping and testing.

3. **6 Hats** - Edward de Bono's Six Thinking Hats is a tool for group discussion and individual thinking involving six colored hats. Each color represents a different perspective. It's used to look at decisions from multiple viewpoints.

4. **5 Whys** - A problem-solving technique that involves asking "why" five times to get to the root cause of a problem.

5. **TRIZ** - A Russian acronym for "Theory of Inventive Problem Solving". It's a methodology for systematic problem solving. It's based on logic, data, and research, not intuition.

6. **Starbursting** - A brainstorming technique focusing on generating questions. It helps in exploring new avenues and challenges by questioning every aspect of the project.

7. **SWOT** - Stands for Strengths, Weaknesses, Opportunities, and Threats. It's a strategic planning tool for identifying and analyzing these four elements of a project or business venture.

8. **Lotus Blossom** - A diagram used for exploring all the elements of a problem. It encourages you to elaborate on the problem by looking at it from multiple angles.

9. **Problem Reversal/Reverse Brainstorming** - It involves reversing the problem's direction. Instead of asking how to solve it, you ask how you could cause it. It often leads to unique solutions.

10. **Brainstorming** - A group creativity technique used to find a solution for a specific problem by gathering a list of ideas contributed by participants.

11. **Mind mapping** - A graphical way to represent ideas and concepts. It's visual thinking tool that helps structuring information, helping you to analyze, comprehend, synthesize, recall and generate new ideas.

12. **Business Model Canvas** - A strategic management tool that provides a visual framework for developing, describing, and analyzing a business model.

13. **Metrics** - Measurement tools that quantify information. In business, metrics are used to track the effectiveness of processes over time.

14. **Headlines from the future** - A creativity tool in which you imagine what headlines in the future might say about your product or organization, helping you define what success looks like and what you need to do to achieve it.

15. **PESTEL** - Stands for Political, Economic, Social, Technological, Environmental, and Legal. It's a framework used for scanning an organization’s external macro environment.

16. **Porter's Five Forces** - Analyzes an industry's competitiveness and attractiveness. The forces are the threat of new entrants, threat of substitutes, bargaining power of buyers, bargaining power of suppliers, and industry rivalry.

17. **Value Proposition Canvas** - A tool used to understand the fit between product features and customer requirements, ensuring that there’s a match between the value created and the customer’s needs.

18. **Ishikawa Diagram/Fishbone Diagram** - A cause-and-effect diagram that helps teams identify, explore, and display the possible causes of a specific issue or problem.

19. **Kano Model** - A theory for product development and customer satisfaction. It classifies customer preferences into categories (basic, performance, excitement)

These frameworks can be used individually or in combination depending on the context and the nature of the problem you are trying to solve. The key is to encourage diverse thinking and to approach problems from different angles.

## FIRE meta-framework (IA 2.2+)

IA also employs a new meta-framework called [FIRE](FIRE.md), which creates a way to evaluate ideas using all the frameworks. So if you do not know how to proceed with evaluation/improvement, type `FIRE`, `FIRE | ++`.

## IA Examples

**1. `Topic("quantum computing") | D | Names`**
   - **Explanation**: Retrieves knowledge about quantum computing, provides detailed information including algorithms and techniques related to quantum computing, and then lists top people, companies, and products that are related to quantum computing.

**2. `Topic("artificial intelligence") | KF | Q | A`**
   - **Explanation**: Retrieves knowledge on artificial intelligence, identifies the cutting-edge ideas in the domain, lists top research questions, and then answers each of them.

**3. `Essay("space exploration", tokens=500, profundity=8, emotionalImpact=7) | Title | Abstract`**
   - **Explanation**: Generates an essay on space exploration with approximately 500 tokens, with a high profundity level and emotional impact, then creates a title for the essay and generates an abstract that summarizes the content and insights.

**4. `Union("blockchain", "supply chain management") | RD | Startups`**
   - **Explanation**: Generates the union of knowledge areas blockchain and supply chain management, lists valuable research directions in this combined domain, and invents startups based on these research directions.

**5. `Topic("climate change") | PF(profundity=10) | Impr(categories=["Practicality", "Emotional Impact"])`**
   - **Explanation**: Retrieves knowledge on climate change, generates profound statements related to climate change, and then evaluates and suggests improvements for these statements based on their practicality and emotional impact.

**6. `P("neuroscience")`**
   - **Explanation**: Generates a conversational persona that is an expert on neuroscience and explains the persona's capabilities.

**7. `Topic("electric vehicles") | IP | FIP`**
   - **Explanation**: Retrieves knowledge on electric vehicles, identifies critical historical milestones within the topic, and projects potential future inflection points that would significantly advance the knowledge frontier.

**8. `Topic("cybersecurity") | ++`**
   - **Explanation**: Retrieves knowledge on cybersecurity and improves the output by creating a composite function of multiple functions from IA 2.1 to create more interesting output for an expert on the Knowledge Frontier.

**9. `Q("gene editing") | D | Explain`**
   - **Explanation**: Lists the top research questions in the domain of gene editing, provides detailed information on the research questions including algorithms, processes, or techniques, and explains the expressions involved.

**10. `Topic("robotics") | VC | Advisors`**
    - **Explanation**: Retrieves knowledge on robotics, presents comments, challenges, and potential from a venture capitalist's perspective, and creates a board of advisors related to robotics who give feedback.

**11. `Topic("nanotechnology") | RD | Essay(tokens=800, profundity=7, emotionalImpact=5)`**
    - **Explanation**: Retrieves knowledge on nanotechnology, lists valuable research directions in the domain, and generates an essay based on these research directions with around 800 tokens and adjustable profundity and emotional impact levels.

**12. `Score(Essay("modern art", tokens=300, profundity=6, emotionalImpact=8), Categories=["Originality", "Emotional Impact"])`**
    - **Explanation**: Generates a short essay on modern art with profundity and emotional impact, and then evaluates and scores the essay according to originality and emotional impact categories.
    
[More Examples](examples.md)

## Citing IA?

I understand that there might be reluctance to mention the contribution of IA to your work, research, and/or creative content, so please feel free to not cite IA. 

However, I do appreciate feedback and success stories from the innovation trenches. Reach out via Twitter [@HiDeeeps](https://twitter.com/HiDeeeps) or [LinkedIn](https://www.linkedin.com/in/hannesmarais/).

Keep innovating! Hannes MARAIS


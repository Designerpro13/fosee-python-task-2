# Research Plan

My approach to identifying and evaluating models begins with a comprehensive landscape analysis focused on open-source, code-specialized large language models (LLMs) that are instruction-tuned, as this design aligns perfectly with the goal of generating pedagogical prompts. Promising candidates such as CodeLlama Instruct and Mistral Codestral will be selected over base models like StarCoder, which are primarily optimized for code completion rather than dialogue. The suitability of these models will be assessed using a multi-dimensional set of criteria, including their ability to discern conceptual depth from a student's code, their pedagogical alignment in encouraging deeper learning without providing solutions, and their capacity for generating fluent, coherent, and contextually relevant natural language.

To test and validate the models' applicability, I would implement a hybrid evaluation framework that combines the scalability of automated metrics with the irreplaceable nuance of human judgment. An open-source "LLM-as-a-Judge" framework like DeepEval or RAGAS would be used to quantitatively score the models' outputs against a custom G-Eval rubric that measures pedagogical criteria, such as whether a prompt effectively encourages critical thinking. This automated process will be complemented by a human-in-the-loop validation, where subject-matter experts review and compare the AI-generated prompts against a "gold standard" to ensure the outputs are reliable, safe, and pedagogically sound for high-stakes educational applications. My decision-making process is guided by a clear understanding of the trade-offs, recognizing that while open-source models are "free" from licensing fees, they carry significant costs in infrastructure, maintenance, and skilled human capital-an investment that must be weighed against their superior customizability for this specific, nuanced task.

## Breakdown of Research Plan Questions

**What makes a model suitable for high-level competence analysis?**

The plan explains that suitable models must be instruction-tuned and code-specialized, enabling them to generate pedagogical prompts instead of just completing code. It also outlines a multi-dimensional set of criteria for suitability, including the model's ability to assess conceptual depth and its pedagogical alignment with learning goals.

**How would you test whether a model generates meaningful prompts?**

The plan details a hybrid evaluation framework that combines automated and human-in-the-loop methods. It proposes using an "LLM-as-a-Judge" framework like DeepEval with a custom G-Eval rubric for quantitative scoring, complemented by a human validation process where experts review prompts against "gold standards".

**What trade-offs might exist between accuracy, interpretability, and cost?**

The plan addresses the primary trade-off regarding cost. It clarifies that while open-source models are "free" of licensing fees, they require significant investment in infrastructure, maintenance, and skilled human capital, which must be carefully weighed against the benefits of customization. The two-paragraph summary focuses on this core cost trade-off, which is a major point of the full report.

**Why did you choose the model you evaluated, and what are its strengths or limitations?**

The plan explains the reasoning behind the selection of models like CodeLlama Instruct and Mistral Codestral over models like StarCoder. The primary reason given is that the selected models are instruction-tuned for dialogue, which is a better fit for the task than a model optimized for code completion. The two-paragraph format does not go into the detailed strengths and limitations of a single model but provides the high-level justification for the model choice.

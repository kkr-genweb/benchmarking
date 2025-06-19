# 4. Berkeley Function Calling Leaderboard: LLM Tool Calling Evaluation Quick Start
## 4.1. Overview and Purpose
The Berkeley Function Calling Leaderboard V3, also known as the Berkeley Tool Calling Leaderboard V3, is specifically designed to rigorously evaluate the capability of Large Language Models (LLMs) to accurately invoke functions, often referred to as tools. This leaderboard operates with real-world data and is updated periodically, reflecting its commitment to maintaining relevance and providing ongoing assessment in the rapidly evolving field of LLM development. 

The evolution of the Berkeley Function Calling Leaderboard from its initial version (V1) through V2 and to the current V3 is noteworthy. V1 introduced Abstract Syntax Tree (AST) as an evaluation metric, focusing on the structural correctness of function calls. V2 expanded this by incorporating enterprise and open-source contributed functions, shifting towards more practical, real-world scenarios. V3 further advanced by introducing multi-turn interactions. This progression reflects a clear trend in LLM development: moving beyond simple, single-turn function calls to more complex, interactive, and agentic scenarios. This indicates the increasing sophistication and practical capabilities expected from LLMs in real-world applications, where models must engage in sustained, conversational, and iterative problem-solving. 

## 4.2. Understanding the Leaderboard Metrics
The leaderboard provides several key metrics that enable a comprehensive comparison of different LLM models:

FC (Function Calling): This metric indicates a model's native support for function or tool calling.   

Prompt: This refers to a workaround approach for function calling, where the model's standard text generation capabilities are leveraged to simulate tool invocation.   

Cost: An estimated cost per 1000 function calls, expressed in USD, providing an economic perspective on model usage.   

Latency: Measured in seconds, this metric quantifies the response time of the models.   

Overall Accuracy: This represents the unweighted average across all sub-categories of evaluation. More detailed information regarding the composition of this score is available in their dedicated blog.   

The leaderboard interface allows for sorting by clicking on column headers, facilitating quick comparisons. Additionally, a "Wagon Wheel" chart offers a visual comparison of selected models across various metrics. The inclusion of "Cost" and "Latency" alongside accuracy metrics highlights that the practical deployment of LLM function calling is not solely about correctness, but also about economic viability and responsiveness. This implies a critical trade-off that developers must consider when selecting models for real-world applications, where a highly accurate model might be impractical if its cost or latency is prohibitive.   

## 4.3. Usage and Reproduction
To engage with the Berkeley Function Calling Leaderboard, users can sort the displayed data by clicking on any column header to rearrange the models based on specific metrics. The "Wagon Wheel" chart provides a visual means to compare models by allowing users to select and deselect models for tailored comparisons.   


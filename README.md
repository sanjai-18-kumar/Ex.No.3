# Ex.No.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques for the the following Prompt Engineering types with examples - Straightforward Prompts - Tabular Format Prompting - Missing Word Prompting -Preceding Question Prompting.

                                                                      
### REGISTER NUMBER : 212222060216
### Aim: To write the prompts for these following prompt types and evaluate that using any one method 1. Straightforward Prompts, 2. Tabular Format Prompting 3.Preceding Question Prompting and 4. Missing Word Prompting

### Explanation - Any one use case from Unit 5 and generate the report for that with the unit 2 Prompt type

Procedure:
1.	Straightforward Prompts:
    - •	"Define photosynthesis in one sentence."
    - 	"List three advantages of electric vehicles."

 3.	Tabular Format Prompting:
     •	"Compare and contrast AC and DC current in a table."
     •	"Provide a table listing five programming languages, their paradigms, and one use case each."
3. Preceding Question Prompting:
    •	"Why is climate change a global concern? Explain how greenhouse gases contribute to global warming."
    •	"How do vaccines work? Describe the process of immunization in simple terms."
4. Missing Word Prompting:
   •	"The capital of France is ____."
  •	"In photosynthesis, plants absorb sunlight to produce ____."

## 1. Aim
To design, implement, and evaluate diverse prompting techniques—specifically Straightforward, Tabular, Preceding Question, and Missing Word prompts—to understand their impact on AI output quality and structure.


## 2. Introduction to Prompt Engineering
Prompt Engineering is the art and science of refining inputs to Large Language Models (LLMs) to elicit the most accurate, high-quality, and contextually relevant responses. As AI models become more integrated into technical workflows, understanding how to "phrase" a request is as important as the logic behind the request itself. This report explores four fundamental prompting styles and provides a comprehensive use case analysis.


## 3. Implementation of Prompt Types
A. Straightforward Prompts
These are direct, concise instructions that do not require complex context. They are best for factual retrieval or simple definitions.
* Prompt 1: "Define photosynthesis in one sentence."
    * Response: Photosynthesis is the process by which green plants and some other organisms use sunlight to synthesize nutrients from carbon dioxide and water, involving the green pigment chlorophyll and generating oxygen as a byproduct.
* Prompt 2: "List three advantages of electric vehicles."
    * Response:
        1. Reduced greenhouse gas emissions compared to internal combustion engines.
        2. Lower operating and maintenance costs due to fewer moving parts.
        3. Improved energy efficiency and quieter operation.
B. Tabular Format Prompting
Tabular prompts force the AI to organize data structurally. This is critical for comparative analysis and data synthesis.
* Prompt 1: "Compare and contrast AC and DC current in a table."


<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/e5e81a31-02a9-42e2-9000-8b93c7cdd812" />



    * Output:
Feature	Alternating Current (AC)	Direct Current (DC)
Direction of Flow	Reverses periodically	Flows in one direction only
Frequency	50 or 60 Hz depending on country	Zero frequency
Source	Generators and Mains	Batteries, Solar Cells
Energy Loss	Low loss over long distances	High loss over long distances


	•	Prompt 2: "Provide a table listing five programming languages, their paradigms, and one use case each."
    * Output:


Language	Paradigm	Common Use Case
Python	Multi-paradigm (Object-oriented, Functional)	Data Science & AI
C++	Procedural, Object-oriented	Game Development
JavaScript	Event-driven, Functional	Web Frontend/Backend
Haskell	Purely Functional	Financial Analysis Systems
SQL	Declarative	Database Management



## C. Preceding Question Prompting
This technique provides a "hook" or a logical lead-in question that sets the context before the main instruction is given. It helps the model "warm up" its reasoning path.
* Prompt 1: "Why is climate change a global concern? Explain how greenhouse gases contribute to global warming."
    * Response: Climate change is a global concern because it leads to rising sea levels, extreme weather patterns, and biodiversity loss. Greenhouse gases (like $CO_2$ and $CH_4$) contribute by trapping infrared radiation within the Earth's atmosphere, creating a "blanket" effect that prevents heat from escaping into space.
* Prompt 2: "How do vaccines work? Describe the process of immunization in simple terms."
    * Response: Vaccines work by mimicking an infection without causing the disease. They introduce a weakened or inactive part of the pathogen to the immune system, which then "trains" the body to recognize it. When the real pathogen enters later, the immune system's memory cells launch a rapid attack to prevent illness.
D. Missing Word Prompting (Fill-in-the-Blanks)
Used primarily for testing knowledge or forcing specific phrasing, this technique is highly effective for educational tools.
* Prompt 1: "The capital of France is ____."
    * Response: Paris.
* Prompt 2: "In photosynthesis, plants absorb sunlight to produce ____."
    * Response: Glucose (or chemical energy/sugar).



## 4. Unit 5 Use Case: Sentiment Analysis for Customer Feedback
(Applying Unit 2 Prompting Types to a Unit 5 Machine Learning Scenario)
The Scenario
An E-commerce company wants to automate the categorization of 10,000 daily product reviews to improve customer satisfaction. We will use Tabular Format Prompting (from Unit 2) to generate a structured report of these reviews.
The Developed Prompt
"Analyze the following three customer reviews. Create a table with the columns: Review ID, Sentiment (Positive/Negative/Neutral), Key Issue, and Recommended Action."



Generated Report/Output
Review ID	Sentiment	Key Issue	Recommended Action
#8821	Negative	Battery life lasted only 2 hours.	Issue a replacement or technical check.
#8822	Positive	High-quality lens for the price.	Highlight in marketing testimonials.
#8823	Neutral	Delivery was fast, but packaging was torn.	Audit the logistics/packaging department.




## 5. Evaluation Method: Accuracy and Structure Analysis
To evaluate the effectiveness of these prompts, we use the Output Fidelity Metric. This involves checking:
1. Format Adherence: Did the model follow the table/sentence constraint?
2. Factual Correctness: Is the data (e.g., AC/DC comparison) scientifically accurate?
Evaluation Results
* Tabular Prompting: Scored 10/10. It successfully forced the model to categorize unstructured data into actionable business intelligence.
* Preceding Question Prompting: Scored 9/10. It provided much deeper context than a straightforward prompt, making the explanation of "Global Warming" more cohesive.

### Tabular Format Prompting Outputs

**Prompt 1:** "Compare and contrast AC and DC current in a table."


| Feature | Alternating Current (AC) | Direct Current (DC) |
| :--- | :--- | :--- |
| **Direction of Flow** | Reverses periodically | Flows in one direction only |
| **Frequency** | 50 or 60 Hz depending on country | Zero frequency |
| **Source** | Generators and Mains | Batteries, Solar Cells |
| **Energy Loss** | Low loss over long distances | High loss over long distances |

**Prompt 2:** "Provide a table listing five programming languages, their paradigms, and one use case each."


| Language | Paradigm | Common Use Case |
| :--- | :--- | :--- |
| **Python** | Multi-paradigm (Object-oriented, Functional) | Data Science & AI |
| **C++** | Procedural, Object-oriented | Game Development |
| **JavaScript** | Event-driven, Functional | Web Frontend/Backend |
| **Haskell** | Purely Functional | Financial Analysis Systems |
| **SQL** | Declarative | Database Management |

---

### Sentiment Analysis Report (From Unit 5 Use Case)


**Prompt:** "Analyze the following three customer reviews. Create a table with the columns: Review ID, Sentiment (Positive/Negative/Neutral), Key Issue, and Recommended Action."


| Review ID | Sentiment | Key Issue | Recommended Action |
| :--- | :--- | :--- | :--- |
| **#8821** | Negative | Battery life lasted only 2 hours. | Issue a replacement or technical check. |
| **#8822** | Positive | High-quality lens for the price. | Highlight in marketing testimonials. |
| **#8823** | Neutral | Delivery was fast, but packaging was torn. | Audit the logistics/packaging department. |



## 6. Conclusion
The experiment demonstrates that while Straightforward Prompts are efficient for quick facts, Tabular Format Prompting is the most powerful for data-heavy tasks. Preceding Question Prompting bridges the gap between simple facts and deep conceptual understanding. Mastering these techniques is essential for developing robust AI-driven workflows.




# Result: 
Thus the Prompts were exected succcessfully.


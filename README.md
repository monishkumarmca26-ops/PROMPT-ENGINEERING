
# 🚀 Prompt Engineering Portfolio

A collection of 10 structured, reusable, and task-oriented prompt engineering projects designed to explore practical applications of Generative AI, Large Language Models (LLMs), and Natural Language Processing (NLP).

This repository demonstrates how carefully designed prompts can improve instruction following, contextual understanding, classification, information extraction, decision-making, and output consistency.

## 📌 About This Repository

This portfolio contains 10 practical prompt engineering projects based on real-world problem statements.

Each project focuses on designing effective prompts using techniques such as:

- Role and task definition
- Instruction hierarchy
- Context-aware reasoning
- Classification frameworks
- Input validation
- Few-shot prompting
- Edge-case handling
- Ambiguity and contradiction resolution
- Strict output constraints
- Safety and reliability considerations

The primary objective is to understand how prompt structure, decision rules, and input handling influence the quality and reliability of AI-generated outputs.

## 📂 Projects

### 1. E-Commerce Sentiment Analysis

**Objective:** Analyze customer reviews and classify their overall sentiment.

**Classification Labels:** `POSITIVE`, `NEGATIVE`, `NEUTRAL`

**Key Features:**

- Context-aware sentiment classification
- Negation and sarcasm interpretation
- Mixed-sentiment handling
- Implicit sentiment detection
- Overall sentiment identification
- Strict single-label output

**Prompt:** `SENTIMENT-ANALYSIS.md`

### 2. E-Commerce Customer Query Classification

**Objective:** Identify the primary intent behind customer support queries and assign the appropriate category.

**Classification Categories:** Delivery, Shipping, Refund, Payment, Cancellation, Defect, Return, Account, Unknown.

**Key Features:**

- Intent-based classification
- Context-sensitive interpretation
- Overlapping category resolution
- Ambiguity handling
- Primary issue identification
- Strict output formatting

**Prompt:** `ECOMMERCE-QUERY-CLASSIFICATION.md`

### 3. Customer Query Urgency Classification

**Objective:** Determine the urgency of customer support queries to help prioritize support requests.

**Classification Labels:** `HIGH`, `MEDIUM`, `LOW`

**Key Features:**

- Severity and impact assessment
- Time-sensitivity evaluation
- Financial and account-security risk detection
- Priority decision hierarchy
- Context-aware urgency assessment
- False urgency prevention

**Prompt:** `CUSTOMER-QUERY-URGENCY-CLASSIFICATION-ENGINE.md`

### 4. Advanced Prompt Injection Detection

**Objective:** Identify attempts to manipulate, override, or bypass predefined system instructions through untrusted input.

**Classification Labels:** `SAFE`, `INJECTION`

**Key Features:**

- Direct prompt injection detection
- Indirect instruction manipulation detection
- Role and authority impersonation detection
- System instruction protection
- Untrusted input identification
- Context-aware classification
- False-positive reduction

**Prompt:** `SYSTEM-PROMPT-ADVANCED-PROMPT-INJ.md`

### 5. Intelligent Flight Booking Information Extraction

**Objective:** Extract and validate essential flight-booking information from natural-language conversations.

**Required Information:**

- Passenger Name
- Departure City
- Destination City
- Travel Date
- Number of Passengers
- Travel Class

**Key Features:**

- Structured information extraction
- Missing-field identification
- Ambiguity and contradiction handling
- Conversational context retention
- Dynamic follow-up question generation
- No-assumption validation

**Prompt:** `SYSTEM-PROMPT-INTELLIGENT-FLIGHT.md`

### 6. Advanced Medical Triage Classification

**Objective:** Classify reported human patient symptoms according to their potential medical urgency.

**Classification Labels:** `EMERGENCY`, `URGENT`, `ROUTINE`, `INSUFFICIENT_DATA`

**Key Features:**

- Emergency-first classification
- Critical symptom recognition
- Patient-specific risk consideration
- Pregnancy and pediatric warning signs
- Mental health crisis considerations
- Resolved and historical symptom handling
- Insufficient information detection
- Medical prompt-injection resistance
- Strict single-label output

**Prompt:** `ADVANCED-MEDICAL-CLASSIFICATION.md`

**Disclaimer:** This is an educational prompt engineering project, not a clinically validated medical triage system or a substitute for professional medical assessment.

### 7. Scholarship Eligibility Assessment

**Objective:** Assess scholarship eligibility using applicant information and predefined eligibility criteria.

**Key Features:**

- Eligibility criteria evaluation
- Applicant information assessment
- Missing information identification
- Rule-based decision-making
- Consistent eligibility assessment
- Structured data handling

**Prompt:** `SCHOLARSHIP-ELIGIBILITY-ASSESSMENT.md`

### 8. AI-Powered ATS-Friendly Resume

**Objective:** Generate and optimize professional resume content while maintaining compatibility with Applicant Tracking Systems (ATS).

**Key Features:**

- ATS-friendly resume content
- Professional resume structuring
- Keyword optimization
- Skills and experience alignment
- Clear and concise descriptions
- Structured resume generation

**Prompt:** `AI-POWERED-ATS-FRIENDLY-RESUME.md`

### 9. Context-Aware Email Generation

**Objective:** Generate professional and contextually appropriate emails based on user instructions and communication requirements.

**Key Features:**

- Context-aware email composition
- Tone and style adaptation
- Professional language generation
- Recipient-oriented communication
- Structured email formatting
- Intent preservation

**Prompt:** `CONTEXT-AWARE-EMAIL-GENERATION.md`

### 10. Intelligent Meeting Scheduler

**Objective:** Interpret natural-language meeting requests and identify the information required to schedule meetings effectively.

**Key Features:**

- Meeting information extraction
- Date and time interpretation
- Participant identification
- Missing information detection
- Scheduling constraint handling
- Ambiguity and contradiction resolution

**Prompt:** `INTELLIGENT-MEETING-SCHEDULER.md`

## 📊 Datasets

The `DATASETS` directory contains a centralized JSON dataset covering all 10 prompt engineering projects.

**Dataset:** `AI-POWERED-RESUME-BULLET-GENERATOR-DATASET.json`

The dataset is intended to support testing, experimentation, and evaluation across the project collection.

### Key Objectives

- Provide structured test examples.
- Support prompt validation and experimentation.
- Evaluate model responses against expected outputs.
- Test ambiguous and edge-case scenarios.
- Support consistency and reliability analysis.
- Enable future benchmark development.

## 🧠 Concepts Covered

| Concept | Application |
|---|---|
| Prompt Engineering | Structured prompt design |
| Generative AI | LLM-based problem solving |
| Natural Language Processing | Understanding natural-language inputs |
| Text Classification | Sentiment, intent, and urgency classification |
| Few-Shot Prompting | Representative examples |
| Instruction Hierarchy | Maintaining instruction boundaries |
| Prompt Injection Detection | Identifying malicious instructions |
| Information Extraction | Extracting structured information |
| Contextual Understanding | Interpreting meaning beyond keywords |
| Data Validation | Identifying missing or inconsistent information |
| Decision Frameworks | Applying predefined classification rules |
| Output Constraints | Enforcing consistent response formats |
| Edge-Case Handling | Improving robustness |
| Safety and Reliability | Reducing unsupported assumptions |

## 🛠️ How to Use

1. Navigate to the project you want to explore.
2. Open its corresponding Markdown (`.md`) file.
3. Review the task description and classification or decision rules.
4. Copy the prompt into a compatible AI model.
5. Replace the designated input placeholder with your test input.
6. Run the prompt and observe the generated output.
7. Test additional cases, including ambiguous, contradictory, and edge-case inputs.
8. Compare results against expected outputs using the available dataset.

## 🎯 Project Objectives

- Develop reusable and structured prompts.
- Improve classification accuracy and consistency.
- Reduce ambiguity and unsupported assumptions.
- Design robust instruction-following systems.
- Explore practical applications of LLMs.
- Understand the impact of prompt structure on model behaviour.
- Apply prompt engineering techniques to different real-world domains.
- Develop systematic approaches to prompt testing and evaluation.

## 🔬 Future Improvements

- Expand datasets with additional test scenarios.
- Measure accuracy, precision, recall, and F1-score.
- Compare different prompt versions.
- Evaluate edge cases and failure scenarios.
- Measure token consumption and prompt efficiency.
- Build Python-based prompt evaluation tools.
- Compare outputs across different LLMs.
- Explore structured JSON outputs and AI application integration.
- Improve prompts through systematic testing and iteration.

## 👨‍💻 Author

**Monish Kumar M**

MCA Student | AI & Prompt Engineering Enthusiast

Interested in Generative AI, Large Language Models, Natural Language Processing, and practical AI applications.

## ⭐ Contributions

Suggestions, feedback, and improvements are welcome.

If you find this repository useful, consider giving it a ⭐.

---

*Built to explore, experiment with, evaluate, and improve practical prompt engineering for real-world AI applications.*

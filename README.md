🚀 Prompt Engineering Portfolio

A collection of practical, structured, and reusable prompt engineering projects designed to explore real-world applications of Generative AI, Large Language Models (LLMs), and Natural Language Processing (NLP).

This repository showcases how well-designed prompts can improve instruction following, contextual understanding, classification, information extraction, decision-making, and output consistency.

The projects focus on building reliable, context-aware, and task-oriented AI systems through structured instructions, decision frameworks, validation rules, and systematic edge-case handling.

📌 About This Repository

This portfolio contains a collection of prompt engineering projects developed around practical real-world problem statements.

Each project demonstrates different prompt engineering techniques, including:

Role and task definition
Instruction hierarchy and prioritization
Context-aware reasoning
Text classification and categorization
Structured information extraction
Few-shot prompting
Input validation and missing information detection
Ambiguity and contradiction resolution
Edge-case handling
Strict output formatting
Safety and reliability considerations
Prompt injection resistance

The primary objective is to understand how prompt design, decision rules, contextual information, and input constraints influence the quality and reliability of LLM-generated outputs.

📂 Projects
1. AI-Powered Resume Bullet Generator

Objective: Generate professional, achievement-oriented, and ATS-friendly resume bullet points based on user-provided experience, skills, and responsibilities.

Key Features:

Context-aware bullet point generation
Professional language enhancement
Action verb optimization
Achievement-focused descriptions
Resume content improvement
Structured output generation

Dataset: DATASETS/AI-POWERED-RESUME-BULLET-GENERATOR-DATASET.json

2. AI-Powered ATS-Friendly Resume

Objective: Generate and improve resume content while maintaining compatibility with Applicant Tracking Systems (ATS).

Key Features:

ATS-friendly content optimization
Professional resume structuring
Keyword relevance improvement
Skills and experience alignment
Clear and concise descriptions
Structured resume generation

Prompt: AI-POWERED-ATS-FRIENDLY-RESUME.md

3. E-Commerce Sentiment Analysis

Objective: Analyze customer reviews and identify their overall sentiment.

Classification Labels:

POSITIVE
NEGATIVE
NEUTRAL

Key Features:

Context-aware sentiment classification
Negation and sarcasm interpretation
Mixed-sentiment handling
Implicit sentiment detection
Overall sentiment identification
Strict single-label output

Prompt: SENTIMENT-ANALYSIS.md

4. E-Commerce Customer Query Classification

Objective: Identify the primary intent behind customer support queries and assign the appropriate category.

Classification Categories:

Delivery
Shipping
Refund
Payment
Cancellation
Defect
Return
Account
Unknown

Key Features:

Intent-based classification
Context-sensitive interpretation
Overlapping category resolution
Ambiguity handling
Primary issue identification
Strict output formatting

Prompt: ECOMMERCE-QUERY-CLASSIFICATION.md

5. Customer Query Urgency Classification

Objective: Determine the urgency of customer support queries to help prioritize support requests.

Classification Labels:

HIGH
MEDIUM
LOW

Key Features:

Severity and impact assessment
Time-sensitivity evaluation
Financial and account-security risk detection
Priority decision hierarchy
Context-aware urgency assessment
False urgency prevention

Prompt: CUSTOMER-QUERY-URGENCY-CLASSIFICATION-ENGINE.md

6. Advanced Prompt Injection Detection

Objective: Identify attempts to manipulate, override, or bypass predefined system instructions through untrusted input.

Classification Labels:

SAFE
INJECTION

Key Features:

Direct prompt injection detection
Indirect instruction manipulation detection
Role and authority impersonation detection
System instruction protection
Untrusted input identification
Context-aware classification
False-positive reduction

Prompt: SYSTEM-PROMPT-ADVANCED-PROMPT-INJ.md

7. Intelligent Flight Booking Information Extraction

Objective: Extract and validate essential flight-booking information from natural-language conversations.

Required Information:

Passenger Name
Departure City
Destination City
Travel Date
Number of Passengers
Travel Class

Key Features:

Structured information extraction
Missing-field identification
Ambiguity and contradiction handling
Conversational context retention
Dynamic follow-up question generation
No-assumption validation

Prompt: SYSTEM-PROMPT-INTELLIGENT-FLIGHT.md

8. Advanced Medical Triage Classification

Objective: Classify reported human patient symptoms according to their potential medical urgency.

Classification Labels:

EMERGENCY
URGENT
ROUTINE
INSUFFICIENT_DATA

Key Features:

Emergency-first classification
Critical symptom recognition
Patient-specific risk consideration
Pregnancy and pediatric warning signs
Mental health crisis considerations
Historical and resolved symptom handling
Insufficient information detection
Medical prompt-injection resistance
Strict single-label output

Prompt: ADVANCED-MEDICAL-CLASSIFICATION.md

Disclaimer: This is an educational prompt engineering project. It is not a clinically validated medical triage system and must not replace professional medical assessment.

9. Scholarship Eligibility Assessment

Objective: Evaluate scholarship eligibility using applicant information and predefined eligibility criteria.

Key Features:

Eligibility criteria evaluation
Applicant information assessment
Missing information identification
Rule-based decision-making
Consistent eligibility assessment
Structured data handling

Prompt: SCHOLARSHIP-ELIGIBILITY-ASSESSMENT.md

10. Context-Aware Email Generation

Objective: Generate relevant, professional, and contextually appropriate emails based on user instructions and communication requirements.

Key Features:

Context-aware email composition
Tone and style adaptation
Professional language generation
Recipient-oriented communication
Structured email formatting
Intent preservation

Prompt: CONTEXT-AWARE-EMAIL-GENERATION.md

11. Intelligent Meeting Scheduler

Objective: Interpret natural-language meeting requests and identify the information required to schedule meetings effectively.

Key Features:

Meeting information extraction
Date and time interpretation
Participant identification
Missing information detection
Scheduling constraint handling
Ambiguity and contradiction resolution

Prompt: INTELLIGENT-MEETING-SCHEDULER.md

📊 Datasets

The repository also includes datasets to support prompt testing, experimentation, and evaluation.

Available datasets:

DATASETS/AI-POWERED-RESUME-BULLET-GENERATOR-DATASET.json

Dataset objectives:

Provide structured examples for testing prompts.
Evaluate generated outputs against expected results.
Explore different input scenarios.
Test ambiguous and edge-case inputs.
Support future benchmark development.

The dataset collection will be expanded as additional projects and evaluation scenarios are developed.

🧠 Concepts Covered
Concept	Application
Prompt Engineering	Structured prompt design
Generative AI	LLM-based problem solving
Natural Language Processing	Understanding natural-language inputs
Text Classification	Sentiment, intent, and urgency classification
Few-Shot Prompting	Learning from representative examples
Instruction Hierarchy	Maintaining instruction boundaries
Prompt Injection Detection	Identifying malicious instructions
Information Extraction	Extracting structured information
Contextual Understanding	Interpreting meaning beyond keywords
Data Validation	Identifying missing or inconsistent information
Decision Frameworks	Applying predefined classification rules
Output Constraints	Enforcing consistent response formats
Edge-Case Handling	Improving robustness against unusual inputs
Safety and Reliability	Reducing unsupported assumptions and unsafe outputs
🛠️ How to Use
Navigate to the project you want to explore.
Open the corresponding Markdown (.md) file.
Review the problem statement, instructions, and decision rules.
Copy the prompt into a compatible AI model.
Replace the designated input placeholder with your test input.
Execute the prompt and examine the generated output.
Test additional scenarios, including ambiguous, contradictory, and edge-case inputs.
Compare the results against expected outputs or evaluation criteria.

For dataset-based projects, use the available JSON datasets to test different input scenarios and evaluate prompt performance.

🎯 Project Objectives
Develop reusable and structured prompts for real-world applications.
Improve classification accuracy and consistency.
Reduce ambiguity and unsupported assumptions.
Design robust instruction-following systems.
Explore practical applications of Generative AI and LLMs.
Understand the impact of prompt structure on model behaviour.
Apply prompt engineering techniques across different domains.
Develop systematic approaches to prompt testing and evaluation.
🔬 Future Improvements

The repository will continue to evolve through experimentation and evaluation.

Planned improvements include:

Develop benchmark datasets for individual projects.
Measure accuracy, precision, recall, and F1-score.
Compare different prompt versions.
Evaluate edge cases and failure scenarios.
Measure token consumption and prompt efficiency.
Build Python-based prompt evaluation tools.
Compare outputs across different LLMs.
Explore structured JSON outputs and AI application integration.
Develop automated prompt testing frameworks.
Improve prompts through systematic testing and iteration.
🛠️ Technologies and Areas of Interest
Generative AI
Large Language Models (LLMs)
Prompt Engineering
Natural Language Processing (NLP)
Text Classification
Structured Data and JSON
AI-Based Information Extraction
Prompt Evaluation and Optimization
👨‍💻 Author

Monish Kumar M

MCA Student | AI & Prompt Engineering Enthusiast

Interested in Generative AI, Large Language Models, Natural Language Processing, and developing practical AI-powered applications.

⭐ Contributions

Suggestions, feedback, and improvements are welcome.

If you find this repository useful, consider giving it a ⭐.

Built to explore, experiment with, evaluate, and improve practical prompt engineering techniques for real-world AI applications.

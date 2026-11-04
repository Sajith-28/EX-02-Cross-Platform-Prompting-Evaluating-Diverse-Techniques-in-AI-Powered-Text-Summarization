# EX-02: Cross-Platform Prompting – Evaluating Diverse Techniques in AI-Powered Text Summarization
## Name : SAJITH AHAMED F
## REG NO: 212223240144
## Dept: B.tech & AIML
## 1. Introduction

This experiment evaluates how different prompting techniques influence the quality of AI-generated summaries using two AI platforms: **ChatGPT and Google Gemini**.

A research article about digital twin applications in crop monitoring was selected. Both AI tools were given the same article and six different prompting techniques to generate summaries.

The generated responses were compared based on accuracy, coherence, simplicity, and instruction adherence.

## 2. Objective

- To evaluate the summarization capabilities of ChatGPT and Google Gemini.
- To compare six different prompting techniques.
- To understand how prompt structure influences AI-generated summaries.
- To evaluate the quality, clarity, and accuracy of generated outputs.
- To identify the strengths and limitations of both AI platforms.

## 3. Research Article Selected

**Title:** Digital twin-based applications in crop monitoring

**Author:** Tsega Y. Melesse

**Journal:** Heliyon, Volume 11 (2025), Article e42137

**DOI:** https://doi.org/10.1016/j.heliyon.2025.e42137

The selected article explores digital twin technology in crop management, including modelling methodologies, applications, architecture, challenges, and future opportunities.

### Main Topics Covered

- Digital twin technology in agriculture.
- Five modelling approaches: physics-based, data-driven, hybrid, agent-based, and spatial.
- Crop monitoring and agricultural applications.
- Benefits and challenges of digital twin implementation.
- Future opportunities for sustainable agriculture.

## 4. AI Platforms Used

| Platform | Website |
|---|---|
| ChatGPT | https://chatgpt.com/ |
| Google Gemini | https://gemini.google.com/ |

Both platforms were provided with the same research article and corresponding prompts to maintain consistent input conditions.

## 5. Prompting Techniques

Six prompting techniques were used in this experiment.

### Experiment 1: Basic Prompt

**Prompt:**

Read the attached research article titled "Digital twin-based applications in crop monitoring" and write a clear summary of the article.

Include the main objective, key concepts, important findings, applications, challenges, and conclusion.

Use simple English and keep the summary within 100 words.

Do not include information that is not present in the article.

**Purpose:** To establish a baseline and observe how both AI tools summarize an article using a simple instruction.

### Experiment 2: Role-Based Prompt

**Prompt:**

Act as an expert agricultural technology researcher with knowledge of digital twin systems.

Read the attached research article titled "Digital twin-based applications in crop monitoring" and prepare a clear summary.

Explain the article's objective, key concepts, important findings, applications, challenges, and conclusion.

Use simple English suitable for a college student. Keep the summary within 100 words.

Use only information supported by the article.

**Purpose:** To evaluate whether assigning an expert role improves the quality and relevance of the generated summary.

### Experiment 3: Context-Based Prompt

**Prompt:**

I am a college student studying Artificial Intelligence and Machine Learning. I need to understand a research article about digital twin technology in agriculture.

Read the attached article titled "Digital twin-based applications in crop monitoring" and summarize it for my academic understanding.

Cover the main objective, digital twin concepts, modelling approaches, important findings, agricultural applications, challenges, and conclusion.

Explain technical terms in simple English. Keep the summary within 100 words.

Use only information from the article and do not add external information.

**Purpose:** To evaluate whether providing background information and user context helps generate more relevant explanations.

### Experiment 4: Constraint-Based Prompt

**Prompt:**

Act as an agricultural technology researcher.

Summarize the attached research article "Digital twin-based applications in crop monitoring" by following these strict constraints:

1. Use a maximum of 80 words.
2. Include the objective, modelling approaches, applications, challenges, and conclusion.
3. Use simple and clear English.
4. Do not use bullet points or headings.
5. Do not include opinions or information from outside the article.
6. Ensure all statements are accurate and supported by the article.

Provide only the summary.

**Purpose:** To test how accurately each AI tool follows strict word limits, formatting rules, and content restrictions.

### Experiment 5: Output Format-Based Prompt

**Prompt:**

Act as an expert agricultural technology researcher.

Read the attached research article titled "Digital twin-based applications in crop monitoring" and summarize it using the following exact structure:

1. Objective:
2. Key Concepts:
3. Modelling Approaches:
4. Important Findings:
5. Applications:
6. Challenges:
7. Conclusion:

Write 1–2 simple sentences under each heading. Use clear English suitable for a college student.

Keep the entire summary within 150 words. Use only information supported by the article.

**Purpose:** To evaluate the ability of both tools to generate structured summaries according to a predefined output format.

### Experiment 6: Final User-Defined Prompt

**Prompt:**

Act as a senior agricultural technology researcher specializing in Artificial Intelligence and Digital Twin systems.

I am a college student preparing an academic review of the research article titled "Digital twin-based applications in crop monitoring" by Tsega Y. Melesse (2025).

Carefully analyze the attached article and prepare a comprehensive but concise summary.

Follow these requirements:

1. Explain the research objective and the importance of digital twins in crop monitoring.
2. Describe all five modelling approaches identified in the article.
3. Summarize the major findings and agricultural applications.
4. Explain the main technical and practical challenges.
5. Present the authors' conclusion and future research needs.

Output format:
- Objective
- Key Concepts
- Modelling Approaches
- Important Findings
- Applications
- Challenges
- Conclusion

Use simple, academically appropriate English.
Keep the summary within 150 words.
Ensure factual accuracy and do not introduce unsupported information or external assumptions.
Prioritize completeness, clarity, and faithful representation of the original article.

**Purpose:** To evaluate a carefully designed prompt combining role assignment, background context, content requirements, constraints, and structured output.

---

## 6. Experimental Results

A total of **12 AI-generated summaries** were collected: six from ChatGPT and six from Google Gemini.

### Experiment 1 – Basic Prompt

**ChatGPT Output:**

The article reviews digital twins for crop monitoring and management. A digital twin is a virtual model of a crop or farm, updated using sensor, satellite, and weather data. It discusses five approaches: physics-based, data-driven, hybrid, agent-based, and spatial models. These models support crop-health monitoring, yield prediction, irrigation planning, and pest and disease detection. The main challenges include poor data quality, integration difficulties, high costs, limited rural connectivity, cybersecurity, and privacy concerns. The article concludes that digital twins are promising but still developing. Standard methods and long-term studies are needed to understand their full potential.

**Gemini Output:**

- **Objective**: Explore digital twin use in crop management.
- **Key Concepts**: Virtual crop models built using physics-based, data-driven, or hybrid approaches.
- **Findings**: Digital twins improve farm transparency and decision-making.
- **Applications**: Used for health monitoring, yield prediction, and irrigation.
- **Challenges**: Faced with high costs, poor data quality, and cybersecurity hurdles.
- **Conclusion**: Though early-stage, digital twins offer strong potential for agricultural sustainability.

**Observation:** ChatGPT covered all five modelling approaches and provided more detail about challenges. Gemini produced a shorter, structured summary.

### Experiment 2 – Role-Based Prompt

**ChatGPT Output:**

The article explores how digital twins improve crop monitoring and management. A digital twin is a virtual model of a real crop, updated using sensor data, satellite images, and weather information. It uses physics-based, data-driven, hybrid, agent-based, and spatial models. Findings show improved crop monitoring, yield prediction, and resource management. Applications include irrigation optimization, pest and disease detection, soil health monitoring, and farm planning. Major challenges include high costs, poor data quality, data integration, internet connectivity, and security issues. The article concludes that digital twins can support smarter, more efficient, and sustainable agriculture, but further research is needed.

**Gemini Output:**

This review article explores digital twin applications in crop management.

- **Objective:** Synthesize current research on digital twin modeling methodologies, roles, architectures, and challenges in crop monitoring.
- **Key Concepts:** Digital twins use real-time sensor and satellite data to create virtual replicas of physical crop systems for continuous monitoring.
- **Findings:** Five core modeling approaches were identified: physics-based, data-driven, hybrid, agent-based, and spatial models.
- **Applications:** They optimize irrigation, predict yields, monitor crop health, and manage pests.
- **Challenges:** Barriers include poor data quality, integration complexity, cybersecurity risks, and high costs.
- **Conclusion:** Digital twins enhance sustainable agricultural productivity, though long-term performance evaluations are still needed.

**Observation:** Both tools included all five modelling approaches. ChatGPT provided more detailed application explanations, while Gemini described the review's research focus more specifically.

### Experiment 3 – Context-Based Prompt

**ChatGPT Output:**

The article reviews how digital twin technology improves crop monitoring and agricultural management. A digital twin is a virtual copy of a real crop system, continuously updated using sensor, satellite, and weather data. It identifies five modelling approaches: physics-based (simulating natural processes), data-driven (using machine learning), hybrid (combining both), agent-based (simulating individual plants), and spatial (analysing geographical variations). Key applications include crop health monitoring, yield prediction, irrigation optimization, pest detection, and resource management. Challenges include poor data quality, high costs, connectivity, cybersecurity, and model complexity. The article concludes that digital twins can improve productivity and sustainability, but further research and long-term evaluation are needed.

**Gemini Output:**

This review explores digital twins (virtual system replicas) in crop management.

- **Objective:** Synthesize research methods and roles.
- **Concepts:** Real-time data integration mirrors plant development.
- **Approaches:** Physics, data-driven, hybrid, agent-based, and spatial models.
- **Findings:** Advanced algorithms improve accuracy and prediction.
- **Applications:** Optimizes irrigation, yield forecasting, and pest control.
- **Challenges:** Poor data quality, high costs, and cybersecurity issues.
- **Conclusion:** Though early-stage, digital twins significantly enhance agricultural sustainability.

**Observation:** ChatGPT explained the modelling approaches individually and provided more technical detail. Gemini produced a concise, easy-to-read summary.

### Experiment 4 – Constraint-Based Prompt

**ChatGPT Output:**

This review examines digital twin applications in crop monitoring and their role in improving crop management. It identifies five modelling approaches: physics-based, data-driven, hybrid, agent-based, and spatial models. Applications include crop health monitoring, yield prediction, irrigation optimization, and pest and disease management. Challenges include poor data quality, high costs, data integration, cybersecurity, and privacy. The article concludes that digital twins can improve agricultural productivity, decision-making, and sustainability, but further research is needed for wider adoption.

**Gemini Output:**

This article explores digital twin applications in crop management to improve productivity and decision-making. It identifies physics-based, data-driven, hybrid, agent-based, and spatial modeling approaches. Applications include monitoring crop health, irrigation, pest management, and yield prediction. Implementation challenges involve poor data quality, integration issues, cybersecurity risks, and high costs. The conclusion states that although still in its early stages, digital twin technology holds significant potential to drive agricultural transformation, economic growth, and sustainability under climate change.

**Observation:** Both tools followed the paragraph format and generated concise summaries. ChatGPT included privacy concerns, while Gemini emphasized agricultural transformation.

### Experiment 5 – Output Format-Based Prompt

**ChatGPT Output:**

The article reviews digital twins for improving crop monitoring and management. It identifies five modelling approaches: physics-based, data-driven, hybrid, agent-based, and spatial models. Applications include crop health monitoring, yield prediction, irrigation management, and pest detection. Challenges include poor data quality, high costs, cybersecurity, data integration, and limited internet connectivity. The article concludes that digital twins can improve farming decisions, productivity, and sustainability, but further research and long-term evaluation are needed.

**Gemini Output:**

1. **Objective:** This article explores digital twin applications in crop management, focusing on modeling approaches, architecture, and challenges.

2. **Key Concepts:** A digital twin is a virtual representation of a physical crop system updated with real-time sensor and satellite data.

3. **Modelling Approaches:** The article identifies five key modeling methods: physics-based, data-driven, hybrid, agent-based, and spatial models.

4. **Important Findings:** Research interest has surged since 2018, with India, China, and the United States leading publications.

5. **Applications:** Digital twins are used for crop health monitoring, yield prediction, pest control, and smart irrigation management.

6. **Challenges:** Major hurdles include poor data quality, integration complexities, high costs, and cybersecurity risks.

7. **Conclusion:** Digital twins offer great potential for sustainable agriculture, though long-term performance studies are still required.

**Observation:** Gemini followed all seven requested headings. ChatGPT provided a paragraph instead of the requested structure. Gemini demonstrated better adherence to the specified output format in this experiment.

### Experiment 6 – Final User-Defined Prompt

**ChatGPT Output:**

### Objective

The article reviews digital twin methods, applications, architecture, challenges, and future opportunities in crop monitoring.

### Key Concepts

Digital twins are continuously updated virtual representations of crops using sensor, satellite, weather, and simulation data. They support real-time monitoring and better decision-making.

### Modelling Approaches

1. Physics-based: Simulates crop growth using physical processes.
2. Data-driven: Uses machine learning to predict yields and detect diseases.
3. Hybrid: Combines physical models and machine learning.
4. Agent-based: Simulates interactions between individual plants, insects, and their environment.
5. Spatial: Uses GIS to analyse geographical variations and manage resources.

### Important Findings

Digital twins improve monitoring, prediction, resource efficiency, and agricultural decision-making.

### Applications

Crop health monitoring, irrigation, pest and disease detection, yield prediction, farm management, and supply chain optimization.

### Challenges

Poor data quality, integration difficulties, high costs, complex modelling, cybersecurity, privacy, and limited rural internet connectivity.

### Conclusion

Digital twins offer promising sustainable farming solutions. Future research should establish standard methods, compare traditional approaches, and evaluate long-term performance across multiple growing seasons.

**Gemini Output:**

- **Objective**: Explore digital twin applications, modeling methodologies, architecture, and challenges in crop management.
- **Key Concepts**: Virtual crop representations integrating real-time sensor, satellite, and weather data for precision monitoring.
- **Modelling Approaches**: Physics-based, data-driven, hybrid, agent-based, and spatial models.
- **Important Findings**: Research publications have surged since 2018; digital twins significantly enhance operational visibility, resource efficiency, and decision-making.
- **Applications**: Crop health tracking, irrigation management, yield prediction, pest/disease control, and sustainability compliance.
- **Challenges**: Data quality and integration issues, high technology costs, cybersecurity risks, and physical-virtual synchronization difficulties.
- **Conclusion**: Digital twins hold transformative potential for sustainable agriculture. Future research requires standardized methodologies, multi-season performance evaluations, and end-user integration insights.

**Observation:** ChatGPT provided individual explanations of all five modelling approaches. Gemini included publication trends and physical–virtual synchronization challenges. Both produced structured summaries with the requested sections.

---

## 7. Comparison of All Six Experiments

| Prompt Technique | ChatGPT | Gemini |
|---|---|---|
| Basic | Detailed and comprehensive | Short and structured |
| Role-Based | Detailed applications and modelling approaches | Clear research-oriented summary |
| Context-Based | Better technical explanations | More concise presentation |
| Constraint-Based | Followed constraints | Followed constraints |
| Output Format | Did not follow requested headings | Followed all seven headings |
| Final User-Defined | Detailed modelling explanations | Included publication trends and synchronization challenges |

## 8. Evaluation Criteria

The AI-generated summaries were evaluated using four primary criteria.

| Criterion | Description | Weight |
|---|---|---:|
| Accuracy | Correctness and consistency with the research article | 40% |
| Coherence | Logical flow and organization of information | 25% |
| Simplicity | Ease of understanding and clarity of language | 15% |
| Instruction Adherence | Ability to follow the given prompt requirements | 20% |
| **Total** | | **100%** |

### Scoring Scale

| Score | Performance |
|---:|---|
| 5 | Excellent |
| 4 | Good |
| 3 | Average |
| 2 | Below Average |
| 1 | Poor |

## 9. Preliminary Evaluation Results

The following scores are reviewer-estimated based on the collected responses. They are exploratory assessments, not independently validated benchmark measurements.

| Evaluation Criteria | ChatGPT | Gemini |
|---|---:|---:|
| Accuracy | 4.5/5 | 4.2/5 |
| Coherence | 4.6/5 | 4.5/5 |
| Simplicity | 4.3/5 | 4.7/5 |
| Instruction Adherence | 4.0/5 | 4.7/5 |
| **Weighted Overall Score** | **4.40/5** | **4.45/5** |

### Overall Score

| AI Platform | Overall Score |
|---|---:|
| ChatGPT | 4.40/5 |
| Google Gemini | 4.45/5 |

**Result:** Gemini achieved a slightly higher preliminary weighted score, with a difference of 0.05 points.

Note: Response speed was not measured, and user experience was not collected through a separate user survey. Therefore, no numerical scores are assigned to these criteria.

## 10. Key Findings

### ChatGPT

- Provided detailed explanations of technical concepts.
- Explained all five modelling approaches more thoroughly in several experiments.
- Covered agricultural applications and implementation challenges in greater detail.
- Produced comprehensive academic summaries.

### Google Gemini

- Generated concise and readable summaries.
- Followed the requested output structure effectively in the output-format experiment.
- Presented information using clear headings and bullet points.
- Included publication trends and synchronization challenges in the final experiment.

### Overall Comparison

Both AI tools successfully summarized the selected research article. ChatGPT generally provided more detailed technical explanations, whereas Gemini demonstrated stronger formatting and concise presentation.

## 11. Limitations of the Experiment

- Only one research article was used.
- Only six prompting techniques were tested.
- Each prompt was tested once on each platform.
- Response speed was not systematically recorded.
- User experience was not measured using a separate survey.
- Evaluation scores were assigned through reviewer judgment rather than independent expert validation.
- Repeated trials and a standardized factual accuracy rubric are needed to strengthen the results.

## 12. Conclusion

This experiment evaluated six prompting techniques using ChatGPT and Google Gemini for technical research article summarization.

The results indicate that prompt design influences the structure, clarity, and detail of AI-generated summaries. ChatGPT generally provided more detailed technical explanations, while Gemini performed well in concise summarization and following structured output requirements.

Gemini achieved a slightly higher preliminary weighted score of 4.45/5 compared with ChatGPT's 4.40/5. However, the small difference does not establish a definitive winner.

Further experiments using multiple research articles, repeated trials, measured response times, and standardized evaluation methods are recommended for more reliable conclusions.

---

## 13. References

1. Melesse, T. Y. (2025). *Digital twin-based applications in crop monitoring*. Heliyon, 11, e42137. https://doi.org/10.1016/j.heliyon.2025.e42137
2. OpenAI ChatGPT – https://chatgpt.com/
3. Google Gemini – https://gemini.google.com/

---

**Project:** EX-02 – Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

**Experiment Type:** Comparative AI Prompt Engineering

**AI Platforms:** ChatGPT and Google Gemini

**Total Prompt Techniques:** 6

**Total Generated Outputs:** 12

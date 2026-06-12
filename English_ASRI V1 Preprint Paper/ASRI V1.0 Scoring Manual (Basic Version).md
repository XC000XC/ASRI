# ASRI V1.0 Scoring Manual (Basic Version)

## Document Positioning
This document is the basic version of the scoring manual for the AI Substitution and Reshaping Index (ASRI) V1.0. It standardizes the definition of scoring objects, the six-dimensional scoring method, the scoring process, recording requirements, and consistency control principles.

The core question this document answers is: **How should ASRI be practically scored?**

This document serves the following purposes:
- Research implementation
- Case review
- Scoring training
- Demonstration of methodological transparency
- Foundational specifications for subsequent case database construction

---

## I. Overview of Scoring Principles

The scoring object of ASRI V1.0 is not the abstract occupational label, but rather:

**The task composition structure of a specific occupation in a specific scenario.**

Therefore, the following principles must be adhered to during scoring.

### 1. Scenario-First Principle
First, define the specific work scenario in which the occupation operates, then proceed with the six-dimensional scoring.
Do not score broad occupational titles such as "doctor," "teacher," "designer," or "programmer" holistically without a scenario.

### 2. Task Composition Principle
The basis for scoring should be the primary task structure within that occupational scenario, not social impressions, occupational halos, educational thresholds, industry myths, or subjective imaginings of individual capability.

### 3. Structural Judgment Principle
What ASRI assesses is whether tasks are more susceptible to AI takeover, restructuring, or resistance to substitution. It does not evaluate occupational value, occupational dignity, occupational meaning, or the level of the practitioner.

### 4. Comprehensive Judgment Principle
The scoring for each dimension should be based on a comprehensive judgment of the primary task combination within that scenario, rather than seizing upon a marginal task to determine the entire score based on a single impression.

### 5. Explainability Principle
Each dimensional score must be accompanied by a brief written justification. A score without a written rationale should not be considered a complete scoring result.

### 6. Uniform Scale Principle
All dimensions use the same 0.0–1.0 continuous interval. However, its meaning is "the strength of that dimension within that task structure," not a measure of "goodness or badness."

### 7. Prudent Interpretation Principle
The result of ASRI is an expression of structural substitution pressure and should not be directly interpreted as an unemployment rate, elimination probability, occupational value ranking, or substitution timeline.

---

## II. Standard Format for Writing Scoring Objects

To avoid misjudgment caused by overly coarse occupational titles, it is recommended to name the scoring object using the following format:

**Occupational Title + Scenario Delimitation + Task Emphasis Description**

Examples:
- E-commerce Customer Service (Standardized After-Sales Inquiry Scenario)
- Secondary School Homeroom Teacher (Scenario Combining Classroom Teaching and Student Management)
- 3D Modeler (Game Asset Mass Production Pipeline Scenario)
- 3D Modeler (High-End Film and Television Character Customization Scenario)
- Legal Assistant (Contract Review and Document Collation Scenario)
- Psychological Counselor (Ongoing Individual Counseling Scenario)

If the internal scenarios of an occupation differ too greatly, it must be split into multiple scoring objects and scored separately. Forced merging is not permitted.

---

## III. Object Delimitation Before Scoring

Before formal scoring, the scorer should first write a description delimiting the object. This should include at least the following four items:

### 1. Occupational Title
Use a recognizable occupational title or job title from reality whenever possible.

### 2. Scenario Boundary
Describe the organizational environment, workflow, or service context in which the occupation operates. For example:
- Platform-based organization
- School system
- Medical institution
- Outsourced assembly line
- High-end customization studio
- Brick-and-mortar store
- Remote digital collaboration team

### 3. Core Tasks
List the 3–8 most important tasks within this scenario. This step is the core basis for scoring.

### 4. Tasks Not Included
Specify which marginal duties, atypical tasks, or individual high-end tasks are not included in this scoring.

If the object's boundaries are unclear, tasks are ambiguous, or the scenario is indefinite, it should not proceed to formal scoring.

---

## IV. Scoring Scale Explanation: 0.0–1.0 Continuous Scoring

ASRI V1.0 adopts **0.0–1.0 continuous scoring**, rather than 1–5 integer-tiered scoring.

### 1. Why Continuous Scoring is Used
Continuous scoring can more finely express the gradient differences in occupational task structures, avoiding the crude compression of different scenarios into a few fixed tiers.

### 2. How to Understand the Score Values
The score for each dimension represents the strength of that dimension within that task scenario:

- **0.0**: Extremely low or virtually non-existent
- **Around 0.25**: Low
- **Around 0.50**: Medium
- **Around 0.75**: High
- **1.0**: Extremely high or highly typical

### 3. Must Only Whole Numbers Be Used?
No. Decimals can be used in scoring, for example:
- 0.20
- 0.35
- 0.60
- 0.72
- 0.85

However, it is not recommended to use overly finely divided decimals to create a "sense of precision." The basic version recommends controlling precision at the level of **0.05 or 0.10** to balance differentiation and reviewability.

### 4. How to Avoid False Precision
If the scorer cannot clearly explain the difference between 0.55 and 0.60, then forced subdivision should not be applied. The fineness of the score value must match the clarity of the justification.

---

## V. Overview of the Six-Dimensional Scoring Structure

ASRI V1.0 divides the six dimensions into two groups:

### S-Group: Substitution Pressure Formation Dimensions
- Degree of Proceduralization
- Degree of Digitalization
- Verifiability of Outcomes

### D-Group: Defensive Dimensions
- Ambiguous Adaptability
- Interpersonal Empathy
- Non-standard Operations

The calculation formulas are as follows:

- **S = (Degree of Proceduralization × 0.5) + (Degree of Digitalization × 0.3) + (Verifiability of Outcomes × 0.2)**
- **D = (Ambiguous Adaptability × 0.35) + (Interpersonal Empathy × 0.35) + (Non-standard Operations × 0.3)**
- **ASRI = (S × 0.6) - (D × 0.4)**

The theoretical result range of ASRI is approximately **-0.4 to 0.6**.
A higher score indicates that the task composition within that occupational scenario bears higher structural substitution pressure; a lower score indicates that the defensive task structure within that occupational scenario is stronger.

---

## VI. Six-Dimensional Scoring Anchors

The following anchors are used to help scorers form relatively stable judgments within the 0.0–1.0 range. Anchors are not mechanical templates but judgment references.

---

## VI-I. Degree of Proceduralization

### Definition
Refers to whether a task possesses an execution structure that is relatively stable, repeatable, and decomposable into standard procedures.

### Key Observation Points
- Are there clear step sequences?
- Are similar processing logics frequently repeated?
- Is it easy to form SOPs?
- Are exceptions few?
- Can newcomers quickly take over through procedural training?

### Anchor References
- **0.0–0.2**: Tasks are highly open, processing paths change frequently, making it difficult to form fixed procedures.
- **0.3–0.4**: Some fixed steps exist, but exceptions are many, and procedural stability is limited.
- **0.5–0.6**: The main work can be executed according to relatively stable procedures, but some on-the-spot adjustment is still needed.
- **0.7–0.8**: Most tasks have clear steps, high repeatability, and can form standard procedures.
- **0.9–1.0**: Tasks are almost entirely proceduralized, execution paths are highly stable, and replacing the executor has little impact.

### Scoring Tip
Do not automatically judge an occupation as having low proceduralization just because it is "highly professional." Many high-skill occupations can also be highly proceduralized in specific organizational scenarios.

---

## VI-II. Degree of Digitalization

### Definition
Refers to whether the input, processing, and output of a task primarily occur within digital systems, and whether its information can be recorded, transmitted, processed, and reorganized in digital form.

### Key Observation Points
- Is the work mainly completed on computers, platforms, software, or databases?
- Are the input materials digital text, images, voice, code, or structured data?
- Can the output results be generated and delivered directly within digital systems?
- Is there a high dependency on online collaboration, digital platforms, or software pipelines?
- Is the task process easily captured and embedded by systems?

### Anchor References
- **0.0–0.2**: Tasks primarily occur in offline, real-world environments, with minimal digital system involvement.
- **0.3–0.4**: Digital tools play a supporting role, but the core of the task is not completed in a digital environment.
- **0.5–0.6**: A considerable portion of the task is digitized, but it still clearly relies on offline contexts or physical execution.
- **0.7–0.8**: Tasks are mainly completed in digital environments; input and output are basically digitizable.
- **0.9–1.0**: Tasks are almost entirely embedded in digital systems and can be fully recorded, transmitted, and processed.

### Scoring Tip
A high Degree of Digitalization does not automatically equate to being easily substituted; it is merely one of the important preconditions for entering AI takeover conditions.

---

## VI-III. Verifiability of Outcomes

### Definition
Refers to whether task outcomes can be easily inspected, compared, judged as right or wrong, or measured for quality based on explicit standards.

### Key Observation Points
- Is there a unified acceptance standard?
- Can "right/wrong" or "pass/fail" be judged relatively clearly?
- Is the output of different executors easy to compare horizontally?
- Can the results be quantitatively evaluated?
- Are errors easy to identify?

### Anchor References
- **0.0–0.2**: Results are highly subjective, and quality is difficult to judge uniformly.
- **0.3–0.4**: Some standards exist, but evaluation is still highly dependent on context and subjective interpretation.
- **0.5–0.6**: Basic verification is possible, but there is still considerable gray area.
- **0.7–0.8**: Most results can be verified according to explicit rules or objectives.
- **0.9–1.0**: Results have highly clear acceptance standards; right/wrong or standard-meeting status is easy to determine.

### Scoring Tip
"Creative work" does not necessarily mean low verifiability. If its output has clear technical standards, format standards, or delivery requirements within an industrial pipeline, it may still possess high verifiability.

---

## VI-IV. Ambiguous Adaptability

### Definition
Refers to whether a task requires continuous judgment and on-the-spot adjustment under conditions of incomplete information, changing situations, insufficient rules, or conflicting goals.

### Key Observation Points
- Is the practitioner frequently faced with unprescribed problems?
- Is there a need to reconstruct handling methods based on on-site changes?
- Must judgments be made when information is insufficient?
- Does a balance or trade-off need to be made between multiple goals?
- Can the task not be completed simply by relying on fixed rules?

### Anchor References
- **0.0–0.2**: Tasks are basically executed according to established rules; ambiguous situations are extremely rare.
- **0.3–0.4**: Occasionally need to respond to changes, but the main work can still be handled according to established frameworks.
- **0.5–0.6**: Rules and judgment coexist; work frequently requires a degree of flexible adjustment.
- **0.7–0.8**: A large number of tasks depend on on-the-spot judgment, exception handling, and situational adaptation.
- **0.9–1.0**: Tasks are perpetually in highly uncertain situations; the core value lies precisely in judging and adapting within ambiguity.

### Scoring Tip
Do not mistake "busyness at work" for high "Ambiguous Adaptability." This dimension assesses judgment load under uncertainty, not labor intensity.

---

## VI-V. Interpersonal Empathy

### Definition
Refers to whether a task depends on trust-building, emotional processing, relationship maintenance, and contextualized understanding, and requires the practitioner to take responsibility for the consequences of the interaction.

### Key Observation Points
- Is there a need to establish sustained trust relationships?
- Is there a need to handle complex emotional reactions?
- Is there a need to understand the context and intent behind words?
- Must professional, ethical, or ongoing relational responsibility be borne based on the consequences of the interaction?
- Does the interaction go beyond "polite communication" and enter a true responsible interaction?

### Key Distinction: Performative Empathy vs. Responsible Empathy

#### Performative Empathy
Displaying linguistic postures of comfort, understanding, gentleness, and companionship. This type of empathy can be imitated and cannot be directly equated with high Interpersonal Empathy.

#### Responsible Empathy
Not only expressing understanding, but also bearing responsibility for whether that understanding is accurate, whether the response is appropriate, and whether the consequences of the interaction are bearable. This is the source of defensibility that ASRI truly values in this dimension.

### Anchor References
- **0.0–0.2**: Almost no need for genuine interpersonal understanding; interaction is minimal or very superficial.
- **0.3–0.4**: Basic communication is needed, but relationships are shallow, responsibility is light, and substitutability is high.
- **0.5–0.6**: Interaction has a degree of contextual understanding requirement, but the depth of responsibility is limited.
- **0.7–0.8**: Requires continuous handling of trust, emotions, and relationships, and bearing responsibility for the quality of the interaction.
- **0.9–1.0**: Interpersonal judgment and responsible empathy constitute the core of the occupation; the consequences of errors are significant.

### Scoring Tip
"Frequently dealing with people" does not equate to high Interpersonal Empathy. For example, standardized sales pitches, basic reception, and simple customer service may involve frequent interaction, but the depth of responsibility is not necessarily high.

---

## VI-VI. Non-standard Operations

### Definition
Refers to whether a task depends on complex, variable, and difficult-to-fully-script real-world operations, especially the execution capabilities requiring fine motor skills, hand-eye coordination, and on-site adjustment in physical environments.

### Key Observation Points
- Are complex real-world environmental operations involved?
- Are fine motor skills or on-site manual handling required?
- Are differences in objects, environments, or materials frequently encountered?
- Is it difficult to completely describe all operational details through a fixed script?
- Is it necessary to "be on-site" and adjust actions in real time?

### Anchor References
- **0.0–0.2**: Almost no real-world operational requirements; tasks are primarily pure digital or pure cognitive processing.
- **0.3–0.4**: Some operational components exist, but the degree of standardization is relatively high, and variation is small.
- **0.5–0.6**: Requires a degree of on-site execution and adjustment, but still has many standard actions to rely on.
- **0.7–0.8**: A large number of operations depend on specific environments, object states, and manual experience.
- **0.9–1.0**: The core of the task is built upon complex, immediate, and strongly situation-dependent non-standard execution.

### Scoring Tip
This dimension emphasizes non-standard execution in real-world environments, not general tool use. For example, high proficiency in keyboard and mouse operation does not automatically constitute high Non-standard Operations.

---

## VII. Standard Scoring Procedure

The basic version of ASRI V1.0 recommends the following steps for scoring.

### Step 1: Define the Scoring Object
Clearly write out:
- Occupational title
- Scenario scope
- Core task description
- Marginal tasks not included in this scoring

If the scoring object's boundaries are unclear, do not proceed to formal scoring.

### Step 2: List the Primary Task Composition
It is recommended to first briefly describe the primary tasks in the scenario using 3–8 items, for example:
- Receive requirements and clarify revision directions
- Complete standardized modeling according to templates
- Handle basic textures and material configurations
- Coordinate with upstream and downstream links to confirm delivery formats

The purpose of this step is to prevent the scorer from scoring directly based on occupational impressions.

### Step 3: Score Dimension by Dimension
Assign a 0.0–1.0 score to each of the six dimensions and write 1–3 sentences of justification for each.

### Step 4: Calculate S, D, and ASRI
Use the following formulas:
- **S = (Degree of Proceduralization × 0.5) + (Degree of Digitalization × 0.3) + (Verifiability of Outcomes × 0.2)**
- **D = (Ambiguous Adaptability × 0.35) + (Interpersonal Empathy × 0.35) + (Non-standard Operations × 0.3)**
- **ASRI = (S × 0.6) - (D × 0.4)**

### Step 5: Write the Result Interpretation
The result interpretation should at least answer:
- Why S is high or low
- Why D is high or low
- Whether the occupation is more likely to be substituted, reshaped, or show clear differentiation
- What the most critical scenario assumption of this scoring is

### Step 6: Conduct a Review
Check the following issues:
- Whether the occupational label was used as the basis for scoring
- Whether individual excellence was mistaken for occupational structure characteristics
- Whether the justification for any dimension is too weak
- Whether the scoring is consistent with the written explanation
- Whether the scenario delimitation is too coarse

---

## VIII. Recommended Recording Template

It is recommended to record each scoring object in the following format.

### 1. Scoring Object Information
- Occupational Title:
- Scenario Delimitation:
- Task Emphasis Description:
- Scoring Date:
- Scorer:
- Data Sources:
- Notes:

### 2. Primary Task Composition
- Task 1:
- Task 2:
- Task 3:
- Task 4:
- Task 5:
- Task 6:

### 3. Tasks Not Included
- Not Included Item 1:
- Not Included Item 2:
- Not Included Item 3:

### 4. Six-Dimensional Scoring Table

#### Degree of Proceduralization
- Score:
- Justification:

#### Degree of Digitalization
- Score:
- Justification:

#### Verifiability of Outcomes
- Score:
- Justification:

#### Ambiguous Adaptability
- Score:
- Justification:

#### Interpersonal Empathy
- Score:
- Justification:

#### Non-standard Operations
- Score:
- Justification:

### 5. Result Calculation
- S =
- D =
- ASRI =

### 6. Brief Interpretation
- Primary sources of substitution pressure:
- Primary sources of defensibility:
- Whether this occupational scenario is more likely to be substituted, reshaped, or internally differentiated:
- The key scenario assumption of this scoring:
- Boundary conditions to remind the reader of:

---

## IX. Calculation Example: 3D Modeler (Game Asset Mass Production Pipeline Scenario)

The following example is only used to demonstrate the ASRI scoring method and should not be seen as a one-time verdict on the occupation of "3D Modeler" as a whole.

### 1. Scoring Object
**3D Modeler (Game Asset Mass Production Pipeline Scenario)**

### 2. Scenario Description
The 3D modeler in this scenario is primarily responsible for the mass production of assets for game production pipelines. Their work is constrained by explicit project specifications, format requirements, delivery standards, and upstream/downstream collaboration workflows. The task emphasis leans toward mass-production execution rather than highly open original character or world-building.

### 3. Primary Task Composition
- Produce standardized model assets according to requirement sheets and concept drafts
- Control polygon count, structure, and naming conventions according to project specifications
- Handle basic textures, materials, and format adaptation
- Correct delivery issues in coordination with the engine or upstream/downstream links
- Complete version iterations and rework within the established pipeline

### 4. Six-Dimensional Scores and Justifications

#### Degree of Proceduralization: 0.75
Justification:
The workflow in this scenario is relatively clear, typically following a stable path of "receive requirements—model—adjust—accept—rework." Although a degree of experience and aesthetic judgment is still required, the overall pipeline repeatability is high.

#### Degree of Digitalization: 0.95
Justification:
Task input, processing, and output occur almost entirely within digital systems, including concept draft reception, software modeling, file collaboration, and final delivery. This is a typical occupational scenario highly embedded in a digital environment.

#### Verifiability of Outcomes: 0.70
Justification:
Delivery results can usually be inspected relatively clearly based on project standards, polygon count control, format compatibility, texture requirements, and visual consistency. Although there is still some gray area aesthetically, in a mass production pipeline, most results have relatively explicit acceptance criteria.

#### Ambiguous Adaptability: 0.40
Justification:
Although some revision and communication exist in this scenario, most issues can still be handled within established specifications and the project framework. The proportion of judgment tasks that are truly highly open and have unclear goals is relatively limited.

#### Interpersonal Empathy: 0.20
Justification:
This type of work requires communication and collaboration but typically does not depend on deep trust relationships, complex emotional processing, or responsible empathy. Communication exists but is not the core source of occupational defensibility.

#### Non-standard Operations: 0.10
Justification:
This position is typical digital production work, relying almost not at all on complex non-standard operations in real-world environments, hence this dimension is scored low.

### 5. Calculation Process

#### Calculate S
S = (0.75 × 0.5) + (0.95 × 0.3) + (0.70 × 0.2)
S = 0.375 + 0.285 + 0.140
S = **0.800**

#### Calculate D
D = (0.40 × 0.35) + (0.20 × 0.35) + (0.10 × 0.3)
D = 0.140 + 0.070 + 0.030
D = **0.240**

#### Calculate ASRI
ASRI = (0.800 × 0.6) - (0.240 × 0.4)
ASRI = 0.480 - 0.096
ASRI = **0.384**

### 6. Example Interpretation
This case shows that 3D modeling work in the game asset mass production pipeline possesses a high Degree of Digitalization, high procedural stability, and relatively clear acceptance standards, hence the S-group score is relatively high. At the same time, its defensive dimensions are mainly weak: Interpersonal Empathy and Non-standard Operations are low, and Ambiguous Adaptability has not reached a highly open level. Therefore, this scenario overall exhibits relatively evident structural substitution pressure.

However, it must be emphasized that this conclusion only applies to the "game asset mass production pipeline scenario" and does not automatically represent high-end film and television custom work, original world-building development, or strongly cross-departmental creative coordination type 3D modeling work.

---

## X. Notes on Case Differences: Scoring Subjectivity and Retaining Disagreements

Although ASRI V1.0 has tried to minimize arbitrariness through six-dimensional definitions, anchor tables, and formula structures, scoring still contains judgmental components. Therefore, even under the same scenario setting, different scorers may arrive at different results.

For example, for the "3D Modeler (Game Asset Mass Production Pipeline Scenario)," different derivations have yielded two results: **0.30** and **0.384**. This difference should not be simply viewed as "someone miscalculated"; it more likely indicates that scorers have different understandings on the following dimensions:
- Degree of Proceduralization
- Verifiability of Outcomes
- Ambiguous Adaptability

Because ASRI uses 0.0–1.0 continuous scoring, small shifts across multiple dimensions can accumulate into a visible total score difference. This precisely illustrates that ASRI V1.0 currently still needs further calibration through systematic **inter-rater reliability** testing.

Therefore, during the methodological trial phase:
- Different scoring results should be recorded;
- Disagreements should be broken down back to specific dimensions;
- Differing values should not be forcibly deleted to create a "single correct answer."

These differences are themselves important materials for subsequent methodological improvement.

---

## XI. Multi-Scorer and Consistency Recommendations

To improve the stability and reviewability of ASRI, the basic version recommends adopting a multi-scorer mechanism in formal research whenever possible.

### 1. Dual Scorer Independent Scoring
At least two scorers should independently complete the scoring under non-interfering conditions.

### 2. Discrepancy Comparison
Compare the six-dimensional scores item by item, marking dimensions with significant differences.

### 3. Disagreement Discussion
Conduct review discussions focusing on differences in scenario delimitation, data understanding, and anchor usage, rather than only fixating on the total score.

### 4. Retain Original Records
Keep the initial scores, reviewed scores, discussion records, and final scores for subsequent consistency analysis.

### 5. Consistency Statistics
After the sample size increases, conduct statistical tests on inter-rater consistency as supplementary evidence for methodological reliability.

### 6. Delphi Method Calibration
For controversial occupations or highly uncertain scenarios, multiple experts in related fields can be invited to provide multiple rounds of anonymous feedback and opinion convergence to improve the stability of key dimension anchors.

---

## XII. Common Misconceptions in Scoring

### 1. Treating the Occupational Label as the Scoring Object
Incorrect example: Scoring "teacher" directly.
Correct approach: Breaking it down into specific scenarios, such as "Secondary School Homeroom Teacher (Scenario Combining Teaching and Student Management)."

### 2. Mistaking Individual Capability for Occupational Structure
Incorrect example: Judging an entire occupation as low ASRI because a top practitioner is hard to replace.
Correct approach: What is assessed is the task structure, not the ceiling of individual talent.

### 3. Mistaking "Often Communicating with People" for High Interpersonal Empathy
Incorrect example: Automatically assigning high Interpersonal Empathy to all customer service roles.
Correct approach: Judge whether it requires responsible empathy, not performative communication.

### 4. Mistaking "Creative" for Low Outcome Verifiability
Incorrect example: Assuming all design categories are unverifiable.
Correct approach: If an industrial pipeline has clear delivery standards, it can still possess high Verifiability.

### 5. Mistaking "Tool Complexity" for High Non-standard Operations
Incorrect example: Software operation is complex, so Non-standard Operations is high.
Correct approach: Non-standard Operations primarily look at non-standard execution in real-world environments, not digital tool proficiency.

### 6. Treating the Score as a Fate Verdict
Incorrect example: A high ASRI means this occupation will disappear immediately.
Correct approach: ASRI reflects net structural substitution pressure, not an occupational end-of-life timeline.

---

## XIII. Applicability Boundaries of the Basic Version

This scoring manual applies to basic research, case trial scoring, and methodological demonstration for ASRI V1.0. Its applicability boundaries include:

- Suitable for small-sample, case-based, and explanatory research
- Suitable for analysis of intra-occupational scenario differentiation
- Suitable as a foundational format for a subsequent standard case database
- Temporarily not equivalent to a large-scale statistical measurement tool
- Temporarily does not substitute for formal industry surveys, labor data modeling, or policy prediction models

---

## XIV. One-Sentence Summary

ASRI V1.0 scoring is not an intuitive rating of an occupational title, but a six-dimensional continuous assessment of the **task composition structure of a specific occupation in a specific scenario**; its value lies in advancing the originally vague question of "Will AI replace this job?" into a structured judgment process that is decomposable, interpretable, and reviewable.
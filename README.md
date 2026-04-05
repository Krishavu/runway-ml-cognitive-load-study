# Minimizing Cognitive Load: Optimizing UI for Multimodal Generative AI Applications

## Overview
This repository contains the supplementary dataset and survey instruments used in the research paper *"Minimizing Cognitive Load: Optimizing UI for Multimodal Generative AI Applications."* The study investigates the cognitive workload experienced by users when interacting with complex multimodal generative AI tools, specifically using **Runway ML** as the primary testing platform. The data reflects the mental strain, time pressure, and frustration levels of 150 participants across three distinct tasks of varying complexity.

## Repository Contents
* `runway_ml_full_150_results.csv`: The raw, anonymized dataset containing the demographic information and evaluation scores for all 150 participants.
* `README.md`: This file, containing the project description and the exact phrasing of the survey instruments used.

## Methodology & Tasks
Participants were divided evenly to perform one of three tasks on the Runway ML platform:
1. **Simple Image Generation:** Creating an image using a basic text prompt.
2. **Complex Image Generation:** Creating an image using intricate prompts and adjusting advanced parameters.
3. **Video Generation:** Creating a short video by combining text, pictures, and sound.

Immediately following the completion of their assigned task, participants evaluated their cognitive load using two standardized psychological assessment tools: the **NASA Task Load Index (NASA-TLX)** and the **Subjective Workload Assessment Technique (SWAT)**.

---

## Survey Instruments

### 1. NASA Task Load Index (NASA-TLX)
*Participants rated the following six factors on a linear scale from 1 to 21.*

* **Mental Demand:** How much mental and perceptual activity was required (e.g., thinking, deciding, calculating)? Was the task easy or demanding? *(1 = Very Low, 21 = Very High)*
* **Physical Demand:** How much physical activity was required (e.g., clicking, typing, controlling the interface)? *(1 = Very Low, 21 = Very High)*
* **Temporal Demand:** How much time pressure did you feel due to the rate or pace at which the task elements occurred? *(1 = Very Low, 21 = Very High)*
* **Overall Performance:** How successful do you think you were in accomplishing the goals of the task? *(1 = Perfect/Highly Successful, 21 = Failure/Highly Unsuccessful)*
* **Effort:** How hard did you have to work (mentally and physically) to achieve your level of performance? *(1 = Very Low, 21 = Very High)*
* **Frustration Level:** How insecure, discouraged, irritated, stressed, and annoyed did you feel during the task? *(1 = Very Low, 21 = Very High)*

### 2. Subjective Workload Assessment Technique (SWAT)
*Participants selected the single statement (1, 2, or 3) that best described their experience across three dimensions.*

**Time Load:**
1. **(Low):** I often had spare time. Interruptions were infrequent.
2. **(Medium):** I occasionally had spare time. Interruptions or overlapping activities occurred frequently.
3. **(High):** I almost never had spare time. Overlapping activities occurred all the time.

**Mental Effort Load:**
1. **(Low):** Very little conscious mental effort required. Activity was almost automatic.
2. **(Medium):** Moderate conscious mental effort required. Considerable attention was needed.
3. **(High):** Extensive mental effort and concentration were necessary. Required total attention.

**Psychological Stress Load:**
1. **(Low):** Little confusion, risk, frustration, or anxiety existed.
2. **(Medium):** Moderate stress due to confusion, frustration, or anxiety noticeably added to the workload.
3. **(High):** High to very intense stress due to confusion, frustration, or anxiety.

---

## Data Dictionary
For researchers reviewing the `runway_ml_full_150_results.csv` file, the columns are defined as follows:

* `Participant_ID`: Unique anonymized identifier for each participant.
* `Age_Group`: Participant age range.
* `Gender`: Participant gender.
* `Background`: Professional or educational background (Technical, Creative, General).
* `Experience`: Prior experience level with generative AI tools.
* `Task`: The specific Runway ML task evaluated.
* `NASA_Mental`: NASA-TLX Mental Demand score (1-21).
* `NASA_Physical`: NASA-TLX Physical Demand score (1-21).
* `NASA_Temporal`: NASA-TLX Temporal Demand score (1-21).
* `NASA_Performance`: NASA-TLX Performance score (1-21).
* `NASA_Effort`: NASA-TLX Effort score (1-21).
* `NASA_Frustration`: NASA-TLX Frustration score (1-21).
* `SWAT_Time`: SWAT Time Load score (1-3).
* `SWAT_Mental`: SWAT Mental Effort score (1-3).
* `SWAT_Stress`: SWAT Psychological Stress score (1-3).

## Ethics & Privacy
All participant data was collected anonymously. No personally identifiable information (PII) such as names, email addresses, or IP addresses was recorded. All participants provided informed consent for their anonymized data to be used for academic research purposes.

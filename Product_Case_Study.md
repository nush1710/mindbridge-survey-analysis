# MindBridge – Product Case Study

### AI-Based Mental Health Chatbot for Indian College Students

**Project Type:** Product Research & Strategy
**Role:** Product Research, User Research & Product Conceptualisation
**Tools:** Google Forms, Python, Pandas, Matplotlib
**Academic Institution:** Keshav Mahavidyalaya, University of Delhi

---

## 1. Product Overview

MindBridge is a proposed AI-powered mental health chatbot designed specifically for Indian college students. The concept aims to bridge the gap between students experiencing mental health challenges and the support available to them.

The proposed platform combines culturally relevant conversations, principles from Cognitive Behavioural Therapy (CBT), Motivational Interviewing (MI), and crisis support mechanisms to make mental health assistance more accessible and approachable.

The product is envisioned as a supportive first point of contact, not a replacement for professional mental health services.

## 2. Problem Statement

College students experience several mental health challenges, including academic stress, anxiety, loneliness, peer pressure and uncertainty about the future.

Despite experiencing these challenges, many students hesitate to seek professional help due to:

- Social stigma and fear of judgement.
- Financial barriers to accessing counselling.
- Limited awareness of available mental health services.
- Preference for handling problems independently.
- Difficulty accessing support when needed.

Existing mental health chatbots offer a potential way to make support more accessible. However, there is an opportunity to design a solution that better understands the cultural and social experiences of Indian college students.

**How might we make mental health support more accessible, culturally relevant and approachable for Indian college students while ensuring that AI complements professional care?**

## 3. Target Users

**Primary Users:** Indian college students, particularly those aged 18–26.

**User Needs:**

- A comfortable and non-judgmental space to express emotions.
- Accessible support whenever they need it.
- Practical ways to manage everyday stress.
- Privacy and confidentiality when discussing personal concerns.
- Guidance towards professional help when necessary.

## 4. User Research

To understand students' attitudes towards mental health support and AI-based chatbots, a primary survey was conducted using Google Forms.

**Research Method:** Online questionnaire
**Participants:** 32 college students
**Research Focus:** Mental health awareness, help-seeking behaviour, attitudes towards AI chatbots and preferred features.

The survey responses were analysed using Python, Pandas and Matplotlib.

### Key Research Findings

| Research Area          | Key Finding                                                                         |
| ---------------------- | ----------------------------------------------------------------------------------- |
| Stress frequency       | 75% experienced stress sometimes or very often                                      |
| Help-seeking behaviour | 65.62% had not considered seeking professional help                                 |
| Main barrier           | 81.25% preferred handling their problems independently                              |
| Comfort with AI        | 50% were comfortable talking to an AI chatbot                                       |
| Perceived usefulness   | 87.5% responded Yes or Maybe to the potential usefulness of such a chatbot          |
| Main concerns          | Incorrect advice (65.62%), lack of human understanding (62.5%) and privacy (59.38%) |
| Preferred features     | Stress relief exercises (59.38%) and emergency support (56.25%)                     |

*Note: Percentages for multi-select questions are calculated using all 32 participants as the denominator.*

## 5. Key User Insights

The survey findings highlighted four important areas:

**1. Students need accessible support**

75% of respondents experienced stress sometimes or very often. This indicates an opportunity to explore more accessible forms of everyday mental health support.

**2. Seeking professional help can feel difficult**

65.62% had not considered seeking help, while 81.25% selected handling problems independently as a barrier. This highlights the importance of making initial engagement with mental health support feel approachable.

**3. Trust is essential for AI adoption**

Concerns around incorrect advice, lack of human understanding and data privacy indicate that accessibility alone may not be enough to encourage adoption.

**4. Students value practical support**

Stress relief exercises and emergency support emerged as the most frequently selected features, suggesting that students may value practical assistance alongside conversational support.

## 6. Product Opportunity

Based on the literature review and survey findings, the opportunity was to conceptualise a specialised chatbot that could:

- Offer an accessible space for students to express their feelings.
- Understand the cultural and social context of Indian college students.
- Provide structured, supportive conversations.
- Introduce practical coping strategies.
- Recognise situations where professional intervention may be required.

The central product direction was to build a bridge between students and available mental health care rather than position AI as a replacement for human counselling.

## 7. Proposed Product Solution

MindBridge is proposed as a culturally relevant AI mental health chatbot built around three key principles:

**Accessibility:** Available whenever students need a space to express themselves.

**Cultural Relevance:** Designed around student experiences such as academic competition, family expectations, social pressure and identity-related challenges.

**Responsible AI Support:** Grounded in established therapeutic approaches, with clear boundaries and mechanisms to connect users with professional help.

## 8. Proposed Core Features

| Feature                      | Description                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------------- |
| AI Conversations             | Supportive conversations that allow students to express their thoughts and feelings.                |
| Sentiment Analysis           | Proposed system to track emotional patterns throughout conversations.                               |
| CBT-Based Support            | Guided exercises to identify negative thought patterns and explore healthier coping strategies.     |
| Motivational Interviewing    | Conversations that encourage self-reflection and motivation for positive change.                    |
| Stress Relief Exercises      | Practical exercises to help students manage everyday stress.                                        |
| Crisis Detection             | Identification of potentially high-risk language, followed by guidance towards appropriate support. |
| Professional Help Connection | Direct students towards helplines and university counselling services when needed.                  |
| Privacy Protection           | Proposed safeguards involving anonymisation, encryption and responsible data handling.              |

*These are proposed product capabilities from the research framework, not features of a deployed chatbot.*

## 9. Product Architecture & Clinical Approach

The research proposes a technical framework using Python and TensorFlow for sentiment analysis and crisis detection.

The proposed conversational approach draws on two therapeutic methods:

- **Cognitive Behavioural Therapy (CBT):** To help students identify unhelpful thought patterns and explore coping strategies.
- **Motivational Interviewing (MI):** To encourage self-reflection and help students explore their motivations for change.

The proposed crisis support mechanism would identify high-risk conversations and guide students towards appropriate helplines and university counselling services.

Clinical validation and professional supervision would be necessary before real-world deployment.

## 10. Proposed Product Development & Evaluation

The research outlines a four-phase development and evaluation roadmap:

| Phase                         | Proposed Activity                                                                                           |
| ----------------------------- | ----------------------------------------------------------------------------------------------------------- |
| Phase 0 – Needs Assessment    | Conduct student surveys to understand user needs and attitudes towards AI support.                          |
| Phase 1 – System Development  | Develop the proposed chatbot architecture, including sentiment analysis and crisis detection.               |
| Phase 2 – Pilot Testing       | Conduct a four-week pilot with 30 students and evaluate usability through the System Usability Scale (SUS). |
| Phase 3 – Clinical Evaluation | Conduct an eight-week RCT with 300 students using PHQ-9 and GAD-7 assessment scales.                        |

*Only Phase 0, the needs-assessment survey, was completed as part of this project. The remaining phases are proposed future work.*

## 11. Ethical Considerations & Limitations

Since MindBridge deals with sensitive mental health information, the research identifies several important considerations:

- **Data Privacy:** Protecting personal information through appropriate security and data-handling practices.
- **Clinical Accountability:** Ensuring professional oversight and avoiding harmful or misleading advice.
- **Crisis Management:** Establishing reliable escalation mechanisms for high-risk situations.
- **Human Involvement:** Ensuring that AI does not replace professional counselling or human connection.
- **Cultural Sensitivity:** Designing interactions that are relevant to the experiences of Indian students.

The proposed framework also requires clinical validation and real-world testing before it can be considered suitable for deployment.

## 12. Project Limitations

- The primary survey included only 32 participants and may not represent the wider college student population.
- Findings were based on self-reported responses.
- The survey was exploratory and does not establish clinical needs or treatment effectiveness.
- The chatbot was proposed as a product framework; it was not developed or deployed.
- The proposed therapeutic and technical capabilities have not been clinically validated or experimentally evaluated.

## 13. Key Learnings

Through this project, I explored how product opportunities can emerge from combining secondary research with primary user research.

The project involved:

- Identifying a user problem through literature review.
- Conducting primary research to understand user attitudes and pain points.
- Analysing survey responses using Python, Pandas and Matplotlib.
- Translating research findings into product opportunities.
- Conceptualising features around user needs, trust, accessibility and safety.
- Understanding the importance of ethical considerations in AI-driven products.

---

**Project Outcome:** A research-backed product concept and proposed framework for an AI-powered mental health chatbot tailored to Indian college students.

# HairSense

## AI Hairstyle and Grooming Recommendation with Virtual Try-On

**Final Year Project | Department of Computer Science**
**Status:** Proposal and Planning

---

## Table of Contents

1. [Project Idea Selection Process](#1-project-idea-selection-process)
2. [Supervisor Meetings](#2-supervisor-meetings)
3. [Background and Justification](#3-background-and-justification)

---

## 1. Project Idea Selection Process

Before finalizing the project, the team brainstormed and formally evaluated four candidate ideas. Each was assessed against its practical relevance, technical depth, feasibility within the FYP timeline, and potential for demonstration and commercialization.

### 1.1 Candidate Ideas

#### Idea 1: Automated End-to-End Data Science Workflow (Multi-Agent System)

A multi-agent system in which the user defines only the problem and task, while specialized agents manage the full data science lifecycle:

| Agent | Responsibility |
|---|---|
| Data Collection Agent | Searches for and gathers relevant datasets |
| Preprocessing Agent | Cleans, transforms, and prepares the data |
| EDA Agent | Performs exploratory data analysis |
| Visualization Agent | Produces charts and insights |
| Training Agent | Selects and trains models |
| Improvement Agent | Tunes hyperparameters and iterates on results |
| Deployment Agent | Packages and deploys the final model |

#### Idea 2: FYP Management System

A platform that supports supervisors and project managers by tracking proposals, milestones, meetings, submissions, feedback, and evaluations in a single system.

#### Idea 3: AI Makeup and Skin-Tone Matching with Virtual Try-On

A mobile/web application that:

1. Captures a selfie or uses the live camera.
2. Analyzes skin tone, undertone (warm, cool, neutral, olive), skin type, and facial features.
3. Recommends foundation and concealer shades, lipstick and blush colors, eyeshadow palettes, eyeliner styles, and complete looks by occasion (everyday, office, wedding, evening), along with skincare-adjacent guidance.
4. Allows users to try products live on their face using augmented reality.
5. Matches shades across brands and links to purchase options.
6. Offers premium features such as unlimited try-ons, cross-brand matching, saved looks, personalized routines, and makeup-artist consultations.

#### Idea 4 (Selected): AI Hairstyle and Grooming Recommendation with Virtual Try-On

A mobile/web application that:

1. Takes the user's photo.
2. Uses computer vision to analyze face shape.
3. Recommends suitable hairstyles, beards, mustaches, hair lengths, and grooming styles.
4. Allows the user to virtually try the recommended styles on their own face.
5. Optionally recommends products, barbers, and salons.
6. Provides premium users with advanced recommendations and unlimited virtual try-ons.

### 1.2 Evaluation and Rationale for Selection

| Criterion | Idea 1 | Idea 2 | Idea 3 | **Idea 4** |
|---|:---:|:---:|:---:|:---:|
| Personal motivation within the team | No | No | No | **Yes** |
| Addresses a real, everyday problem | No | Yes | Yes | **Yes** |
| Strong computer vision and AI component | No | No | Yes | **Yes** |
| Hardware extension possible (salon device) | No | No | No | **Yes** |
| Clear monetization (B2C and B2B) | No | No | Yes | **Yes** |
| Demonstrable live at the FYP defense | No | Yes | Yes | **Yes** |

Idea 4 satisfied every criterion and was the only candidate that combined a strong AI component, a practical hardware extension, and a dual-market business model. It was therefore selected as the final project.

---

## 2. Supervisor Meetings

### 2.1 Meeting 1: Request for Supervision

| | |
|---|---|
| **Date** | Week 2 |
| **Attendees** | Munib, Usman, Awais, Dr. Hafiz Muhammad Faisal Shahzad |

**Discussion:** The team approached Dr. Hafiz Muhammad Faisal Shahzad and requested that he serve as the Final Year Project supervisor.

**Outcome:** Dr. Faisal agreed to supervise the project and asked the team to return with well-considered project ideas.

### 2.2 Meeting 2: Idea Presentation and Selection

| | |
|---|---|
| **Date** | Week 3 |
| **Attendees** | Munib, Usman, Awais, Dr. Hafiz Muhammad Faisal Shahzad |

**Discussion:** The team presented all four candidate ideas: the multi-agent data science workflow, the FYP management system, AI makeup matching, and AI hairstyle and grooming recommendation.

**Outcome:** After discussion, AI Hairstyle and Grooming Recommendation with Virtual Try-On was approved as the project topic.

**Action item from supervisor:** Study existing applications in this domain and identify gaps that the project can address. The findings of this study were presented at the third meeting (Section 2.3).

### 2.3 Meeting 3: Presentation of Gap Analysis and Project Finalization

| | |
|---|---|
| **Date** | Week 4 |
| **Attendees** | Munib, Usman, Awais, Dr. Hafiz Muhammad Faisal Shahzad |

**Discussion:** The team presented its survey of existing consumer applications and salon hardware products in the hairstyle try-on space and the limitations it found in them. It then described how HairSense would address those limitations and where it would differ from current solutions. The supervisor asked questions about feasibility, scope, and the planned salon device, and the team discussed which parts of the work should be treated as core deliverables and which could be extended if time permits.

**Outcome:** The supervisor approved the gap analysis and the proposed scope. The project idea was fully finalized as **HairSense: AI Hairstyle and Grooming Recommendation with Virtual Try-On**, comprising a mobile/web application and a salon device prototype, with a tablet/kiosk web application as a fallback if hardware integration proves too time-consuming.

**Next steps:** Prepare the Software Requirements Specification, conduct a user survey, begin dataset collection, and draft the project roadmap.

---

## 3. Background and Justification

### 3.1 Origin of the Problem

The idea originated from a direct, shared experience. While at a barber shop, team members Munib, Usman, and Awais each faced the same question: which hairstyle suits me best? Describing a desired style to a barber is difficult, visualizing the result is harder, and a haircut cannot be reversed. Any of us could leave with a style that did not suit our face.

This was reinforced by a second observation. Munib had previously received a client request for a similar solution during the fifth semester, indicating that the problem is genuine and that there is demand for a solution.

These two factors, first-hand experience and real client interest, led the team to commit to this project.

### 3.2 Significance of the Problem

- **Irreversibility.** A haircut cannot be undone in the short term, and an unsuitable one may take weeks to grow out.
- **Communication barrier.** Clients and barbers often struggle to align on the intended result. A case study from a smart-mirror vendor reports that 95% of hairstylists believe they conduct a thorough consultation, while only 7% of clients feel they received one ([Visage Technologies, piiq case study](https://visagetechnologies.com/case-studies/piiq-digital/)). This figure comes from a vendor case study and should be treated as indicative rather than definitive.
- **Automatable styling rules.** Selecting a style by face shape follows established principles, such as jawline contour, length-to-width ratio, and cheekbone placement, which can be implemented using computer vision ([HaircutAI comparison guide](https://haircutai.app/best-ai-hairstyle-apps)).

### 3.3 Existing Work

Substantial work already exists in this domain. This validates market demand and also shows where the space is crowded.

- **Consumer applications and web tools.** A broad ecosystem is available, including YouCam Makeup (Perfect Corp), HaircutAI, CutMuse, Hiface, TryHair AI, HairHunt, Hairstyle Maker, Fotor, BeautyPlus, and Glancely.
- **Salon hardware.** Vendors such as Vercon (with piiq software) and Orbo already offer smart mirrors and kiosks with virtual hairstyle try-on.
- **Academic research.** Hairstyle transfer, hair segmentation, and strand-level 3D hair reconstruction are active research areas, with recent examples including HairPort, StrandHead, and DiffLocks. The literature also acknowledges that current methods struggle with large pose changes and complex hair structures.

The limitations identified in these products, and how the project addresses them, were presented to the supervisor in Meeting 3 (Section 2.3).

### 3.4 Rationale for Pursuing the Project

Given the crowded market, the project is not intended to be another single-purpose try-on filter. Our survey indicates that important capabilities remain unsolved or are fragmented across separate products. The team also brings the following advantages:

1. **First-hand user experience** of the problem being addressed.
2. **Demonstrated client interest**, evidenced by the fifth-semester request.
3. **A well-rounded scope** combining AI and computer vision, mobile and web development, and a hardware component, which suits the requirements of a Final Year Project.
4. **A viable path to a sustainable business**, through a freemium model for individual users and subscriptions for salons.

---

**Team:** Munib, Usman, Awais
**Supervisor:** Dr. Hafiz Muhammad Faisal Shahzad

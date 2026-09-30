# Progress Report #3 (September 2026)

## Reporting Period

August 2026 – September 2026

## Project Overview

Over the past two months, Navis AI focused on translating its refined product vision into a functional visual guidance prototype.

Following the insights from the previous reporting period, development shifted from application-specific voice navigation toward a broader AI-powered augmented reality learning experience.

The main objective was to validate whether AI could understand what a user is looking at and provide visual guidance by showing them exactly where to look.

This resulted in the development of the first prototype of the core Navis AI interaction:

**SEE → ASK → POINT**

---

## Objectives

* Translate the refined Navis AI vision into a working prototype
* Develop an AI system capable of understanding visual context
* Explore AR-based visual pointing and guidance
* Test natural-language interaction with visual environments
* Establish a technical foundation for future learning applications
* Prepare the prototype for further user testing

---

## Activities Completed

✅ Refined the product direction toward AI-powered visual learning

✅ Developed a smartphone-based visual guidance prototype

✅ Implemented a camera-based interaction flow

✅ Developed natural-language question input

✅ Integrated Gemini Vision for visual understanding

✅ Developed coordinate-based visual pointing

✅ Explored AR pointer and gesture-based guidance

✅ Refined the Navis AI interface and user experience

✅ Established the technical architecture for future AR learning applications
---

## Product Evolution

The previous reporting period identified that users valued AI assistance but also wanted to understand what was happening rather than simply having an AI system complete tasks for them.

This led to a further refinement of the Navis AI concept.

### Previous Direction

* Voice-guided application navigation
* Step-by-step assistance for digital tasks
* Healthcare appointment booking as an initial workflow

### Updated Direction

* AI-powered visual learning and guidance
* Real-time understanding of the user's environment
* Natural-language interaction
* Visual pointing to relevant objects or information
* Learning through interactive, contextual guidance

The focus is now on building a general-purpose visual guidance capability that can eventually support education, digital literacy, workplace training, and everyday learning.

---

## Current Prototype

The current prototype explores a simple interaction:

**SEE → ASK → POINT**

A user points their smartphone camera at a visual environment and asks Navis AI a natural-language question.

For example:

> "Where is the C=C double bond?"

The AI analyses the captured image, identifies the relevant visual element, and returns its location.

Navis AI then uses this information to position an AR pointer over the target.

The system therefore moves beyond simply answering a question.

Instead of saying:

> "The C=C double bond is in the middle of the molecule."

Navis AI attempts to show the user:

> "The C=C double bond is here."

This interaction forms the foundation for the broader AI learning platform.

---

## Technical Development

The prototype is currently being developed as a mobile web application to enable rapid testing across smartphones.

### Current Architecture

**Smartphone Camera → Natural-Language Question → Gemini Vision → Visual Target + Coordinates → AR Pointer → Explanation**

### Technology

* React + Vite
* FastAPI
* Gemini Vision
* Web camera APIs
* Web Speech APIs
* AR-style visual pointer
* Coordinate-based visual targeting

The system is designed so that the AI identifies not only what is present in an image, but also the approximate location of the relevant visual element.

This allows the interface to provide spatial guidance rather than relying solely on text or voice explanations.

---

## Prototype Demonstration

The current technical demonstration uses a chemistry structural diagram as an example learning environment.

A user can point the camera at a molecular structure and ask:

> "Where is the C=C double bond?"

The system analyses the image and identifies the relevant part of the diagram before positioning the visual pointer over the target.

Chemistry was selected as an initial demonstration because diagrams contain clearly identifiable visual elements and provide a straightforward way to test whether the AI can accurately identify and point to specific information.

The underlying technology is not limited to chemistry.

The same interaction could eventually be applied to:

* Mathematics diagrams
* Electronics and circuit diagrams
* Scientific illustrations
* Software interfaces
* Workplace procedures
* Everyday objects
* Digital literacy tasks

---

## User Experience Development

The interface was redesigned around a simpler interaction model that prioritises visual guidance.

### Core User Flow

**Camera → Ask → Analyse → Point → Confirm / Ask Again**

The prototype includes:

* Camera interface
* Natural-language input
* Voice input
* AI analysis state
* Visual pointer
* Spoken explanations
* Captions
* Confirmation and retry interactions
* Settings

The goal is to make the interaction feel less like using a traditional chatbot and more like having an AI coach physically guide the user through what they are seeing.

---

## Key Learning

The development process reinforced an important insight from the previous reporting period:

**AI assistance is more useful when it helps users understand and act, rather than simply providing an answer.**

The initial concept focused primarily on guiding users through digital applications.

The current prototype explores a broader question:

> **Can AI help people learn by showing them exactly where to look and what to do in the environment around them?**

This represents an important shift from **task completion** toward **learning through interaction**.

---

## Challenges

Several technical and product challenges remain:

* Accurately identifying specific visual targets
* Mapping AI-generated coordinates onto the live camera view
* Handling different camera orientations and screen sizes
* Ensuring visual guidance remains intuitive and unobtrusive
* Maintaining user trust when AI makes an incorrect identification
* Designing guidance that supports learning rather than simply completing tasks
* Determining the most valuable initial learning applications

These challenges will form the focus of the next stage of development.

---

## Financial Update

| Item             | Amount (SGD) |
| ---------------- | -----------: |
| NTU SEP Grant    |       $3,000 |
| Claude Pro       |         $150 |
| Remaining Budget |       $2,850 |

### Planned Expenditure

Future expenditure will primarily support continued development and testing of the Navis AI prototype.

Planned expenses include:

* Gemini API usage for AI-powered visual analysis
* Continued AI development tools and software
* User testing and prototype development
* AR/VR hardware for future experimentation
* Other software or technical resources required for MVP development

As development moves toward a real-time visual guidance experience, additional Gemini API usage is expected to support testing, visual analysis, and refinement of the AI guidance system.
---

## Competitions & Activities

* Continued participation in the NTU Student Entrepreneurship Programme (SEP)
* Continued development of Navis AI
* Continued exploration of AI and augmented reality applications in education

---

## Project Milestones

### ✅ Completed

- Product direction refined toward AI-powered visual learning
- Smartphone visual guidance prototype
- Camera-based interaction
- Natural-language question input
- Gemini Vision integration
- Coordinate-based visual targeting
- AR pointer prototype
- Updated Navis AI interface and user experience

### 🔄 In Progress

- Improving visual target accuracy
- Refining AR pointer positioning
- Improving mobile camera experience
- Testing different visual learning scenarios
- Developing a more reliable end-to-end prototype

### ⏳ Upcoming

- User testing of the visual guidance prototype
- Expand testing beyond chemistry
- Improve AI visual targeting accuracy
- Develop step-by-step learning guidance
- Explore additional education and real-world applications
- Explore wearable AR/VR hardware

---

## Next Steps

* Complete the real-time visual guidance MVP
* Improve Gemini-based visual target detection
* Improve coordinate mapping and pointer accuracy
* Conduct user testing with the updated prototype
* Test the system across different educational and real-world scenarios
* Develop more interactive step-by-step guidance
* Explore wearable AR hardware for future versions

---

## Progress Video

(https://youtu.be/mhFGBI7dz8Y)

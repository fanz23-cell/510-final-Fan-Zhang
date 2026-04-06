# SPEC.md

## Project Title

MedAssist Web Support for Elderly Patients Visiting Hospitals Alone

## Client

Fan Zhang

## Developer

Cui Youqian

## Agreed Development Fee

TBD (to be finalized with developer)

## Background

A growing number of older adults need to visit hospitals alone, but current hospital environments and service flows are often too complex for them to navigate independently. Large hospital spaces, unclear signage, fragmented medical procedures, and difficult-to-understand documents create barriers throughout the visit.

This project is based on prior research into elderly solo hospital visits and focuses on translating those research insights into a realistic web-based design solution.

## Problem Statement

Older adults visiting hospitals alone often struggle to understand where to go, what to do next, and how to interpret hospital instructions and documents. As a result, routine tasks such as registration, finding departments, payment, testing, and medication pickup become confusing, stressful, and physically demanding.

## Target Users

### Primary Users
- elderly patients who visit hospitals alone
- older adults with reduced vision, hearing, memory, or mobility
- users who feel overwhelmed by large hospitals and complicated workflows

### Secondary Users
- family members helping older adults prepare for hospital visits
- caregivers who want a simpler way to guide patients remotely

## User Stories

- As an elderly patient, I want to see my hospital visit as a simple sequence of steps so I do not get confused.
- As an elderly patient, I want to know what I should do next at any point in the visit.
- As an elderly patient, I want simple explanations of hospital tasks and documents so I can act with more confidence.
- As an elderly patient, I want help understanding signs, windows, and locations in the hospital.
- As an elderly patient, I want a large-text, easy-to-read interface that does not overwhelm me.
- As a caregiver or family member, I want the patient to have clearer instructions so they can complete more of the process independently.

## Core Features

### 1. Step-by-step hospital visit guidance
The website should guide users through a simplified hospital flow, such as:
- registration
- finding the correct department
- waiting
- testing
- payment
- follow-up consultation
- medication pickup

### 2. Current step and next step support
The interface should clearly show:
- where the user is now
- what they need to do next
- where they need to go

### 3. Simplified task explanations
The website should translate hospital actions into plain language, including:
- what a payment step means
- what to bring to a test
- when to wait
- where to go after receiving a form or receipt

### 4. Elderly-friendly interaction design
The MVP should prioritize:
- large text
- strong visual hierarchy
- low cognitive load
- minimal clutter
- simple interaction flow

## AI Feature

The website may include an AI-assisted photo interpretation feature.

### AI use case
Users can take or upload a photo of:
- hospital signs
- service windows
- hallway landmarks
- printed forms
- payment slips
- test orders

The AI feature should interpret the image in context and return simple next-step guidance in elderly-friendly language.

### Example outputs
- “This is the laboratory payment slip. Please pay first, then go to the blood test room.”
- “This sign points to outpatient cardiology on the left.”
- “You are at the payment window. After this, return to the consultation department.”

## Non-Goals / Out of Scope

To keep the MVP realistic, the following are out of scope for this phase:

- direct integration with real hospital systems
- full hospital map accuracy across many hospitals
- medical diagnosis or treatment recommendation
- real-time hospital operational data
- multilingual support beyond a simple MVP if time is limited
- a fully production-ready AI vision system for many edge cases

## Technical Preference

Negotiable. Developer may recommend the fastest realistic stack for an MVP.

Preferred product constraints:
- realistic 40–60 hour implementation scope
- 2–3 main pages or views
- simple backend or lightweight storage only if needed
- priority on usability and clarity over technical complexity

## Desired MVP Structure

A realistic MVP may include:

### View 1: Home / Start page
- brief explanation
- select visit stage or scenario
- simple entry point for users

### View 2: Visit guidance page
- current step
- next step
- destination guidance
- simplified instructions

### View 3: AI photo interpretation page
- upload or take photo
- receive simple explanation
- connect result to next-step guidance

## Success Criteria

The project will be considered successful if the MVP can demonstrate:

- a clear elderly-friendly web interface
- a simplified hospital process flow
- visible support for current step and next step
- a believable AI-assisted photo understanding workflow
- an end-to-end scenario that shows how an older adult would use the site during a hospital visit

## Deliverables

Expected developer deliverables:

- functional MVP prototype
- elderly-friendly interface for the main hospital guidance flow
- basic AI-assisted photo interpretation workflow or prototype
- documented structure of pages and logic
- final demo-ready version
- updated README or implementation notes if needed

## Timeline / Milestones

### Milestone 1: Scope and structure
- finalize stack
- confirm MVP boundaries
- define page structure
- align on user flow

### Milestone 2: Main guidance flow
- build core pages
- implement simplified hospital flow
- refine copy and interaction design

### Milestone 3: AI feature and final polish
- prototype or implement photo interpretation flow
- connect outputs to guidance logic
- polish end-to-end demo
- prepare final handoff

## Open Questions for Developer

- Which stack is most efficient for a fast MVP: Next.js, Streamlit, or another option?
- Should the AI feature be fully implemented or demonstrated as a semi-functional prototype?
- What is the lightest backend needed, if any?
- How should the website store or manage visit progress during a session?
- What is the best way to keep the interface readable and simple for older adults?
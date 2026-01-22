# Prompt Strategy & Tone Control – Task 3

## Overview
This document explains the prompt engineering strategy used to design and control chatbot personas for Task 3 – Custom Chatbot Persona Creator.

The goal was to create distinct AI personalities with consistent tone, behavior, and boundaries using structured prompts.

---

## Persona-Based Prompt Design

Each chatbot persona was designed using a system-style instruction prompt that defines:
- Role and purpose
- Tone and communication style
- Behavioral rules
- Safety boundaries
- Fallback behavior

This ensures consistent responses across different user inputs.

---

## Prompt Structure Used

Each persona prompt followed this structure:

1. **Role Definition**
   - Clearly defines who the chatbot is and what it does

2. **Tone Instructions**
   - Specifies how the chatbot should speak (empathetic, supportive, energetic, etc.)

3. **Behavior Rules**
   - Defines what the chatbot should and should not do

4. **Boundaries & Safety**
   - Prevents misuse (e.g., cheating, medical advice, legal guidance)

5. **Fallback Logic**
   - Guides the chatbot on how to respond when a request is outside scope

---

## Example: AI Subject Tutor Prompt Strategy

For the AI Subject Tutor persona, the prompt was designed to:
- Encourage learning instead of providing direct answers
- Explain concepts step by step
- Maintain a patient and supportive tone
- Refuse requests related to cheating or exam answers politely

This approach ensures ethical and effective educational support.

---

## Prompt Chaining Approach

Although only one chatbot was deployed live, prompt chaining was used during design to:
- Refine persona tone
- Test different response styles
- Adjust boundaries and fallback behavior

Outputs from earlier prompt versions were iteratively improved to reach the final persona instructions.

---

## Tool Limitation Handling

Due to free plan limitations of chatbot platforms, only one chatbot persona (AI Subject Tutor) was deployed live.
The remaining personas were fully documented with detailed prompts and sample conversation flows, which aligns with real-world design workflows.

---

## Key Learnings

- Clear role-based prompts improve consistency
- Tone control is critical for user trust
- Defining boundaries prevents misuse
- Prompt engineering enables persona-rich AI experiences without custom models

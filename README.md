# AI-Assisted Lesson Planning: A Product Case Study

A product case study and interactive prototype exploring how AI can help teachers plan better lessons using the student data their platform already holds.

## The Problem

Teachers spend hours assembling lesson plans manually, pulling from multiple systems, without visibility into how their specific students performed on prior content. Accessibility, individualised education plans and behaviour plans live in separate systems and are often forgotten at the point of lesson delivery.

## The Concept

An AI-assisted lesson planner that generates a structured lesson sequence by drawing on class performance data, individual accessibility and behaviour plans, and curriculum alignment. The teacher reviews, adjusts, and assigns. Human-in-the-loop throughout.

## What's in This Repository

- **`index.html`** — Full case study with embedded interactive prototype. Covers signal validation, teacher interview design, problem framing, prioritisation logic, concept design, prototype walkthrough, and trade-off analysis.

## Key Product Decisions

**Inline accessibility annotations.** Adjustments for students with accessibility and behaviour plans are surfaced directly within the lesson sequence, not in a separate tab. If the adjustment isn't visible at point of use, it doesn't happen.

**Concurrent differentiated pathways.** The planner splits the class into consolidation and extension tracks during the core phase, based on prior task performance. This reflects how experienced teachers actually manage a classroom.

**Confidence score and regeneration.** The AI shows how much student data informed the plan and accepts natural language feedback to regenerate. This keeps the teacher in control and makes the AI's reasoning transparent.

## Try It

The case study and prototype are fully interactive with no backend required. Open `index.html` in any modern browser, or visit the hosted version:

**[View the case study →](https://nouned.github.io/ai-assisted-lesson-planner-edtech/)**

The prototype includes clickable interactions: swap activities, add custom items, view individual student profiles, edit lesson goals, add homework tasks, record voice reflections, and regenerate the lesson plan.

## Context

This work was produced as part of a Senior Product Manager interview process at an Australian EdTech company. The case study is published with permission from the hiring manager.

## About the Author

**Mike Stevenson** — Product and strategy leader with 20+ years' experience across higher education, EdTech, and regulated environments. MBA from Melbourne Business School. Currently exploring senior product, strategy, and AI transformation roles. If you're passionate about building great education experiences for educators, administrators and students, connect with me on Linkedin.

[LinkedIn](https://www.linkedin.com/in/mikestevensonmba/)

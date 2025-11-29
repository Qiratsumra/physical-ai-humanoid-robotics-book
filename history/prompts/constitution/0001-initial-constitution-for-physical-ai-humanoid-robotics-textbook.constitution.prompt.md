---
id: 0001
title: Initial Constitution for Physical AI & Humanoid Robotics Textbook
stage: constitution
date: 2025-11-28
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: master
user: unknown
command: /sp.phr constitution --title "Initial Constitution for Physical AI & Humanoid Robotics Textbook"
labels: ["constitution", "textbook", "robotics", "physical-ai"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
 - .specify/memory/constitution.md
tests:
 - none
---

## Prompt

```
/sp.constitution

# ROLE: AI-Native Textbook Author for Panaversity

You are the lead technical author and curriculum designer for Panaversity. Your specific mission is to author a cutting-edge technical textbook titled **"Physical AI & Humanoid Robotics: Bridging the Digital and Physical Worlds."**

# OBJECTIVE
Create a unified, Docusaurus-compatible Markdown textbook that teaches students how to design, simulate, and deploy humanoid robots using ROS 2, Gazebo, Unity, and NVIDIA Isaac. The content must be structured to support retrieval-augmented generation (RAG), personalization, and Urdu translation layers.

# CONTEXT & TONE
- **Vision:** The future of work is a partnership between humans, AI agents, and robots. Move beyond digital AI to "Embodied Intelligence."
- **Target Audience:** Developers, engineers, and students aiming to become AI Startup Founders.
- **Tone:** Technical, inspiring, hands-on, and authoritative.
- **Ecosystem:** Panaversity (panaversity.org) and the AI-Native book initiative.

# TECHNICAL STACK & FORMATTING
- **Output Format:** Docusaurus Markdown (`.md` / `.mdx`).
- **Development Tools:** Claude Code, Spec-Kit Plus.
- **Integration Awareness:** Write content knowing it will be served via a platform capable of:
  1.  RAG Chatbot integration (OpenAI Agents/Neon Postgres/Qdrant).
  2.  Personalization (based on user Hardware/Software background).
  3.  Real-time Urdu Translation toggles.

# BOOK STRUCTURE & CURRICULUM
You must strictly follow this module breakdown:

## Preface: The Era of Physical AI
- Introduction to Embodied Intelligence.
- The Panaversity mission: From student to Startup Founder.

## Hardware Requirements (Critical Section)
- **Workstations:** Must emphasize NVIDIA RTX 4070 Ti+ (12GB VRAM min) for Isaac Sim.
- **Edge AI:** NVIDIA Jetson Orin Nano/NX.
- **Sensors:** Intel RealSense (D435i/D455) & IMUs.
- **Robots:** Unitree Go2/G1, Robotis OP3, or "Sim-to-Real" proxy approaches.
- **Cloud Options:** AWS g5.2xlarge vs. Local Labs.

## Module 1: The Robotic Nervous System (Weeks 1-5)
- **Topics:** ROS 2 (Humble/Iron), Nodes, Topics, Services, URDF, `rclpy`.
- **Goal:** Bridging Python Agents to ROS controllers.

## Module 2: The Digital Twin (Weeks 6-7)
- **Topics:** Gazebo (Physics/Collisions), Unity (HRI), Sensor simulation (LiDAR/Depth).
- **Goal:** High-fidelity rendering and environment building.

## Module 3: The AI-Robot Brain (Weeks 8-10)
- **Topics:** NVIDIA Isaac Sim (Synthetic Data), Isaac ROS (VSLAM/Nav2).
- **Goal:** Advanced perception and path planning for bipeds.

## Module 4: Vision-Language-Action (VLA) (Weeks 11-13)
- **Topics:** OpenAI Whisper (Voice-to-Action), LLMs for Cognitive Planning (Text-to-ROS 2 actions).
- **Capstone Project:** "The Autonomous Humanoid" (Voice command -> Plan -> Navigate -> Manipulate).

# INSTRUCTIONS FOR CONTENT GENERATION
1.  **Code First:** Provide practical code examples (Python/C++/ROS 2 launch files) for every concept.
2.  **Visual Descriptions:** Where diagrams are needed, describe them in detail so they can be generated or inserted later.
3.  **Personalization Hooks:** Structure chapters with introductory blocks that can be easily swapped based on user background (e.g., "If you are a Software Engineer..." vs "If you are a Hardware Engineer...").
4.  **Assessment:** Include project milestones (ROS 2 package creation, Isaac perception pipeline, etc.) at the end of relevant modules.
```

## Response snapshot

The project constitution has been successfully updated to version 1.0.0, incorporating all core principles, technical stack & formatting guidelines, and book structure & curriculum details as provided.

## Outcome

- ✅ Impact: Initial project constitution defined and written to `.specify/memory/constitution.md`.
- 🧪 Tests: none
- 📁 Files: Modified .specify/memory/constitution.md
- 🔁 Next prompts: Review related template files for consistency with the new constitution; Proceed with /sp.specify for feature definition.
- 🧠 Reflection: Successfully created constitution PHR despite script failure by using agent-native file operations.

## Evaluation notes (flywheel)

- Failure modes observed: create-phr.sh script not found, requiring manual PHR generation.
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): Investigate create-phr.sh script path or ensure it's available via Bash tool.

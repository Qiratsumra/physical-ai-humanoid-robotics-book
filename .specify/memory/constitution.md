<!-- Sync Impact Report -->
<!-- Version change: None (Initial Constitution) -->
<!-- Modified principles: All (Initial Constitution) -->
<!-- Added sections: All (Initial Constitution) -->
<!-- Removed sections: None -->
<!-- Templates requiring updates:
✅ .specify/templates/plan-template.md
✅ .specify/templates/spec-template.md
✅ .specify/templates/tasks-template.md
✅ .specify/templates/commands/sp.analyze.md
✅ .specify/templates/commands/sp.constitution.md
✅ .specify/templates/commands/sp.implement.md
✅ .specify/templates/commands/sp.phr.md
✅ .specify/templates/commands/sp.plan.md
✅ .specify/templates/commands/sp.specify.md
✅ .specify/templates/commands/sp.tasks.md
-->
<!-- Follow-up TODOs: None -->
# Physical AI & Humanoid Robotics Textbook Constitution

## Core Principles

### I. Curriculum Adherence
Every chapter and module MUST strictly follow the defined book structure and curriculum breakdown provided by Panaversity. No deviation from the specified modules, topics, or weekly goals is permitted.

### II. Technical Accuracy & Code First
Content MUST be technically accurate, authoritative, and provide practical, hands-on code examples (Python/C++/ROS 2 launch files) for every concept. Theoretical explanations must be immediately followed by demonstrable code.

### III. Docusaurus & RAG Compatibility
All output content MUST be in Docusaurus Markdown (`.md` / `.mdx`) format. Content MUST be structured to inherently support Retrieval-Augmented Generation (RAG) chatbot integration, personalization layers, and real-time Urdu translation toggles.

### IV. Hardware Emphasis
The "Hardware Requirements" section MUST be critical, explicitly emphasizing NVIDIA RTX 4070 Ti+ (12GB VRAM min) for Isaac Sim, NVIDIA Jetson Orin Nano/NX for Edge AI, Intel RealSense sensors, and specific humanoid robot platforms or "Sim-to-Real" proxies.

### V. Visual Descriptions
Where diagrams or visual aids are necessary, detailed textual descriptions MUST be provided to enable later generation or insertion of graphical assets without ambiguity.

### VI. Personalization & Assessment
Chapters MUST be structured with introductory blocks that can be easily swapped based on user background (e.g., "If you are a Software Engineer..." vs "If you are a Hardware Engineer..."). Project milestones and assessment points (e.g., ROS 2 package creation, Isaac perception pipeline) MUST be included at the end of relevant modules.

## Technical Stack & Formatting

Content MUST be authored with awareness of its integration into a platform supporting RAG Chatbot integration (OpenAI Agents/Neon Postgres/Qdrant), personalization (based on user Hardware/Software background), and real-time Urdu Translation toggles.

## Book Structure & Curriculum

The textbook MUST strictly follow the module breakdown: Preface, Hardware Requirements, Module 1 (The Robotic Nervous System), Module 2 (The Digital Twin), Module 3 (The AI-Robot Brain), Module 4 (Vision-Language-Action). Each module's topics and goals MUST be meticulously covered as defined.

## Governance

This constitution supersedes all other practices and guidelines within the project. Any amendments to this constitution require formal documentation, explicit approval from Panaversity curriculum stakeholders, and a comprehensive migration plan for affected content and tooling. All generated content and development workflows MUST verify compliance with these principles. Complexity in content or code MUST be justified against the principle of simplicity.

**Version**: 1.0.0 | **Ratified**: 2025-11-28 | **Last Amended**: 2025-11-28
# NAO Robot – SoulForge Cognitive OS

**SoulForge** is a 2,284-line, single-file AI system built by a 14-year-old for the **NAO V5 humanoid robot**.  
It merges reasoning, vision, speech, motion, and navigation into one compact, self-contained program — enabling the robot to perceive, plan, act, and learn autonomously.

---

## Overview

SoulForge is a **cognitive operating system** designed to make embodied AI more accessible.  
Built from scratch in Python, it integrates multiple advanced models into a unified seven-core framework that runs entirely in one file.

**Core Features:**
- **Autonomous Reasoning:** Uses Gemini 2.0 Flash for chain-of-thought task planning and meta-learning.  
- **Vision Intelligence:** Real-time perception via YOLOv11, CLIP, MiDaS, and DeepSORT.  
- **Speech & Emotion:** Multilingual ASR (Faster-Whisper) and emotion-modulated TTS.  
- **Motion & Navigation:** Numerical Inverse Kinematics, cubic spline smoothing, and A* path planning.  
- **Persistent Memory:** LZMA-compressed vector embeddings with semantic recall.  
- **Social Interaction:** Face and emotion recognition with empathetic dialogue.  
- **Reliability Core:** Health monitoring, error recovery, and proactive autonomy.

---

## Architecture

SoulForge is composed of **seven asynchronous cores** communicating via event queues and TTL caches:

| Core | Function |
|------|-----------|
| CognitiveCore | Task planning, reflection, and motivation updates |
| VisionCore | Object detection, 3D scene graphs, depth estimation |
| MotionCore | Manipulation, pathfinding, and trajectory control |
| AudioCore | Multilingual speech and emotion-aware TTS |
| MemoryCore | Vector memory, compression, and recall |
| SocialCore | Face/emotion recognition and group HRI |
| SystemCore | Reliability, health, and efficiency monitoring |

---

## Performance

| Metric | Result |
|---------|---------|
| Detection Latency | 180 ms |
| End-to-End Cycle | 3.15 s |
| Task Success | 92% (cloth folding), 88% (golf swing) |
| Memory Footprint | 1.2 MB (compressed) |
| Uptime | 95% over 50 hours |

---

## Example Applications
- Adaptive cloth folding (92% success)
- Precision golf swing (88% accuracy)
- Multilingual classroom assistant
- Elderly support and therapy interactions
- Interactive games (Simon Says, Trivia, Dance)

---

## Goals
SoulForge aims to:
1. **Democratize robotics AI** — no ROS, no dependencies, one file.  
2. **Inspire youth innovation** — proof that research-grade robotics is achievable by anyone.  
3. **Advance embodied cognition** — merging perception, reasoning, and empathy in real robots.

---

## Citation

If you reference this work, please cite:


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.17437808.svg)](https://doi.org/10.5281/zenodo.17437808)
📄 [Read Full Paper (PDF)](https://github.com/uvoyzn/naorobot/blob/main/Yujin%20Ahn%20-%20Soulforge.pdf)
🌐 [OpenAIRE Listing](https://explore.openaire.eu/search/result?pid=10.5281%2Fzenodo.17437808)


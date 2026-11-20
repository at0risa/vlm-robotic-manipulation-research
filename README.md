# Vision-Language Models for Robotic Manipulation

Research internship project at Tampere University, Cognitive Robotics Research Group (October 2026).

I explored how vision-language models can be used to interpret natural language instructions and identify objects for robotic manipulation.

Using an existing Franka FR3 control framework, I conducted over 100 robotic manipulation trials, mainly comparing Qwen2.5-VL 3B and 7B. I also explored Gemma 3 and Qwen3-VL.

The experiments focused on task success, response times, object grounding, and common failure cases.

**Key findings:**
- Qwen2.5-VL 7B achieved 61.5% task success, compared with 41.3% for 3B in the evaluated trials.
- Picking objects was generally harder than placing them.
- Visual grounding, lighting, and physical grasping affected task outcomes.

These were exploratory experiments rather than a controlled benchmark.

**Tools:** Python, ROS 2, Docker, Ollama, vision-language models, Franka FR3.





https://github.com/user-attachments/assets/78b3438a-6174-4e4e-a5b2-4ace3c4c46d0







Arnab Das

CS + Data Science @ UW–Madison · Class of 2028

I work at the boundary between ML models and the systems that have to run them in real time. Right now that means fitting speech recognition, vision, and LLM inference onto an 8 GB Jetson and keeping the whole loop under a second.

Currently an AI/Robotics Intern at IT Expert Systems, building an autonomous office robot.

Selected work
Office Robot — conversational robotics on the edge

Autonomous office robot on an NVIDIA Jetson Orin Nano. Chains speech-to-text → LLM → text-to-speech with sub-second responses.

The core design problem was contention: vision, speech, and inference all sharing 8 GB of unified memory while motors need smooth control. Solved by splitting a fast YOLOv8n/TensorRT perception loop (10–20 Hz) from the slower LLM loop, so motion stays fluid while the robot waits on API calls.

Face recognition at 95% accuracy across 50+ enrolled people
Full-duplex audio — WebRTC echo cancellation + Silero VAD for mid-sentence interruption
10,000+ interactions logged to SQLite → EC2, with OpenSearch latency dashboards
Autonomous follow-me navigation and live meeting transcription

Python TensorRT YOLOv8 FastAPI WebSockets ROS2 AWS

Crypto Sentiment & Volatility Arbitrage Engine

Real-time pipeline ingesting live prices and social posts across 100+ cryptocurrencies, scoring each post for sentiment and storing results in SQL for training and backtesting.

A random forest predicts volatility spikes 15% better than a moving-average baseline. The paper trading layer opens positions when sentiment-implied price diverges from the exchange price — 5,000+ trades since January 2026.

Python scikit-learn SQL pandas


Gym Tracker

Mobile workout logger where you record video of each lift and can publish it to a community feed. Postgres row-level security scopes every table to its owner; the cross-user feed runs through a SECURITY DEFINER function so the public/private boundary is enforced in exactly one place rather than in client code.

React Native Expo TypeScript Supabase PostgreSQL

Stack

Languages · Python, JavaScript/TypeScript, C++, Java, SQL, R, Rust (Anchor), HTML/CSS

ML & Vision · PyTorch, TensorRT, YOLOv8, OpenCV, scikit-learn, faster-whisper, Silero VAD

Systems & Infrastructure · Linux, Git, ROS2, AWS (EC2), FastAPI, WebSockets, SQLite, PostgreSQL, Supabase, OpenSearch, REST APIs

Open to Summer 2027 internships in ML engineering, systems, and applied AI.

Arnab Das

CS + Data Science @ UW–Madison · Class of 2028

I work at the boundary between ML models and the systems that have to run them in real time. Right now, that means fitting speech recognition, vision, and LLM inference onto an 8GB Jetson and keeping the whole loop under a second.

Currently an AI/Robotics Intern at IT Expert Systems, building an autonomous office robot.

What I'm building

Office Robot — Conversational robot on an NVIDIA Jetson Orin Nano. Chains speech-to-text → LLM → text-to-speech with sub-second responses. Splits a fast YOLOv8n/TensorRT vision loop (10–20 Hz) from the slower LLM loop so motion stays smooth while waiting on API calls. Face recognition at 95% accuracy across 50+ enrolled people, full-duplex audio with WebRTC echo cancellation and Silero VAD for mid-sentence interruption, and 10,000+ interactions logged to SQLite → EC2 with OpenSearch latency dashboards. Python TensorRT YOLOv8 FastAPI WebSockets ROS2 AWS

Real-Time Crypto Sentiment & Volatility Arbitrage Engine — Pipeline ingesting live prices and social posts across 100+ cryptocurrencies, scoring each post for sentiment and storing results in SQL for training and backtesting. A random forest predicts volatility spikes 15% better than a moving-average baseline. The paper trading layer opens positions when sentiment-implied price diverges from the exchange price — 5,000+ trades since January 2026. Python scikit-learn SQL pandas

CredentialHub — 2nd place out of 94 teams at Badger Build Fest. Universities issue digital diplomas on-chain; employers verify them instantly instead of calling the registrar. Hash commitments let employers confirm authenticity without ever seeing the underlying record. Solana (Anchor) Next.js Node/Express PostgreSQL Tailwind

Stack

Languages · Python, JavaScript/TypeScript, C++, Java, SQL, R, Rust (Anchor), HTML/CSS

ML & Vision · PyTorch, TensorRT, YOLOv8, OpenCV, scikit-learn, faster-whisper, Silero VAD

Systems & Infrastructure · Linux, Git, ROS2, AWS (EC2), FastAPI, WebSockets, SQLite, OpenSearch, REST APIs

Reach me

Email · LinkedIn · Resume

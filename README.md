# Hi, I'm Christofer Piedra 👋  
  
I am a software engineer with a passion for full‑stack web development, machine learning, cybersecurity research, and systems programming. My work spans academic research projects, commercial platforms, and personal experiments. I software that solves real-world problems. My expertise covers modern JavaScript frameworks, Python for data and AI, C/C++ for systems, and cloud services for production‑grade deployments.

<details>
  <summary><strong>🌐 Full-Stack Web & Platforms</strong></summary>

### **FlightPath: Professional Networking Web App**
- Directed development of a full-stack LinkedIn-style app with 4 roles: students, employers, professors, university admin
- Engineered a secure, responsive, scalable UI with role-based navigation & AWS hosting across 40+ components
- Managed agile development cycles across 3 groups: developers, sponsor, & university administration

### **Network Security Testbed with Detection & Dashboard**
- Detected & labeled 5 attack types (ARP poisoning, DDoS, port scan, etc.) in real time using custom IDS scripts
- Implemented a secure data pipeline, processed 20k packets per run, displayed insights into an InfluxDB dashboard
- Personally secured $4,000 in research funding for summer work through a competitive fellowship program and led 2 presentations to a DoD representative, contributing to continued funding of a $591,000 cybersecurity grant

### **Workout App**
- **Structured Data Model:** Uses Firestore collections under `/users/{uid}` to separate long‑lived workout plans, per‑day weight presets, weekly completion status, and user settings. This schema enables stable plan/weight storage while automatically resetting completion checkmarks every Monday at 00:00 America/New_York.
- **History Archiving & Weekly Reset:** Completion documents are keyed by `weekStartISO` (Monday start) so that progress resets on schedule without clearing the underlying plan or weights. Archived completions provide historical visibility into past training weeks.
- **Interval/Cardio Items:** Incorporates interval and cardio items directly into the plan editor.

### **To‑Do App**
- **Integrated Task Manager:** Tasks support creation, editing, marking complete, and deletion.
- **Past‑Due & Recurrence Logic:** Presents overdue tasks, supports recurring tasks so that regularly scheduled activities automatically reappear based on user‑defined intervals.
- **Persistent Storage:** Saves tasks and their status in Firestore, enabling seamless synchronization across devices and sessions. The storage schema cleanly separates task metadata (title, notes, due date, recurrence) from completion state to ensure reliable updates.

### **Interval Timer App**
- **Configurable Timing Sessions:** Provides an interval timer tailored for my personal workouts and cardio. Users can specify work and rest durations, number of rounds, and optional warm‑up/cool‑down periods.
- **Mobile‑First Interface:** Designed with a responsive, touch‑friendly interface that works seamlessly on phones and tablets. Large buttons and clear time displays make it easy to start, pause, and reset sessions during training.

### **Personal Website & Portfolio**
- Developed a responsive single-page application using React/Next.js and Tailwind CSS to serve as a central hub for my résumé and project portfolio.
- Added showcases for major projects: demos of the FlightPath platform, an AI transformer playground, a sports analytics dashboard, and visualizations of intrusion detection metrics.
- Implemented markdown-based blog support, SEO optimization, and automated CI/CD pipelines via GitHub Actions.
  
</details>

<details>
  <summary><strong>🤖 AI & Machine Learning</strong></summary>

### **Custom GPT-2 Build**
- Implemented a 12-layer GPT with bfloat16 DDP, cosine LR decay, grad accum & KV-cache for 20x faster inference
- Tokenized 10B FineWeb tokens & ran a 20-step proof-of concept, reducing val loss from 10.99 to 7.62 (0.246 on HellaSwag MC1)

### **Makemore Character-Level Language Model**
- Trained a 75k+ parameter neural network on 30k+ character sequences using backpropagation and gradient descent
- Reduced loss from 3.6 to 1.76, outperforming the random baseline of 2.30 for a 27-token vocabulary
- Visualized 3 training loss curves and sampled 100+ text outputs to assess model performance and tune architecture

### **AI Basketball Predictor**
- Tuned hyperparameters via grid search & cross validation, achieving over 75% game-result accuracy
- Tuned hyperparameters via grid search and cross-validation across 500+ training iterations
- Packaged into a reusable Python module with an evaluation dashboard visualizing predictions across 12 metrics

### **GPT Experimentation Repository**
- Provides pretraining and fine‑tuning scripts for GPT‑2–style models with configurable hyperparameters (layer count, head size, context length).
- Supports loading and evaluating OpenAI GPT‑2 checkpoints and generating text via CLI or web interface.
- Implements distributed data parallel training with gradient checkpointing to scale across multiple GPUs, enabling training of models beyond single-card memory limits.
</details>

<details>
  <summary><strong>🧑‍💻 Fun/Community Projects</strong></summary>

### **Voltage Robotics Team Website**
- Designed and built a static site for Team Voltage using HTML5, CSS3, and vanilla JavaScript, featuring competition news, team member bios, and sponsor acknowledgments.
- Ensured mobile-first responsiveness and optimized images to sustain lighthouse scores above 95%; integrated Firebase Auth–secured admin tools for content updates via a headless CMS.
- Deployed the site with automated builds and incorporated analytics to track engagement during competition season.

### **Mechanical Maniacs FLL Site**
- Created a dynamic website for the Mechanical Maniacs FLL 2025 season using React and Firebase Hosting.
- Architected an interactive timeline and mission tracker aligned with the season’s archaeology theme and provided a headless CMS for team members to add blog posts, photos, and project updates without code changes.
- Integrated Google Analytics for user engagement insights and iterated on features to enhance visitor interaction.

### **Wordle Entropy Solver**
- Achieved 100% solve rate with an average of 3.70 guesses per word
- Prunes candidates by feedback patterns & reports solve rates for performance metrics
  
</details>

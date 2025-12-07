#Adaptive Myoelectric Hand Control using RL

Prosthetic arms are designed to replace lost limb functionality, enabling individuals
to perform essential motor tasks using assistive technology. However, conventional
myoelectric prosthetics often lack adaptability and struggle to provide precise,
intuitive control. This work introduces an innovative reinforcement learning-based
control system that dynamically adapts to individual users via continuous learning.
The proposed approach begins with supervised pretraining of an Actor-Critic
reinforcement learning model using an EMG dataset with sensor features and action
classifications. This model establishes a foundational signal-to-action mapping.
Following deployment, the same model is refined in real time using the user’s EMG
data, allowing personalized adjustments without retraining from scratch. This
dynamic adaptation enables the system to fine-tune its control policy based on
real-world feedback, enhancing accuracy, responsiveness, and user satisfaction.
Experimental results demonstrate an improvement in action prediction accuracy by
up to 89% after adaptation, validating the system’s ability to learn user-specific
patterns effectively.

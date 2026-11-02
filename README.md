# Richard McKenzie

**Reinforcement Learning & Autonomous Systems Engineer**

## Problem Space

Learning optimal decision-making through trial and error is hard. But when hand-coded policies fail, when the problem space is too large to manually engineer solutions, reinforcement learning shines.

## Core Implementations

### Q-Learning with Function Approximation
Learning value functions for large state spaces using neural networks. Balancing exploration and exploitation through epsilon-greedy strategies.

### Policy Gradient Methods
Direct policy optimization through A3C (Asynchronous Advantage Actor-Critic) and PPO (Proximal Policy Optimization). Better convergence properties than value-based methods for complex problems.

### Actor-Critic Architecture
Combining value estimation and policy optimization. Actor makes decisions, critic evaluates quality. Reduces variance and stabilizes training.

### Multi-Agent Coordination
Multiple agents learning simultaneously with shared and individual rewards. Challenges: credit assignment, coordination, competitive vs cooperative dynamics.

## Key Challenges Addressed

### Exploration vs Exploitation
Early in training, exploit successful strategies. Later, explore to find better solutions. Balancing this tradeoff critically impacts learning speed.

### Credit Assignment Over Long Horizons
How to attribute credit/blame for outcomes when many steps elapse between decision and reward? Discount factors, eligibility traces, and advantage estimation help.

### Sparse Reward Environments
Many real problems have sparse rewards (win/lose at game end). Reward shaping helps but introduces bias. Curiosity-driven exploration provides alternative.

### Training Stability
RL training is notoriously unstable. Small changes in learning rate, network architecture, or hyperparameters cause catastrophic failures.

## Game & Environment Work

### Atari Games
Deep Q-Networks (DQN) learning to play Atari games from raw pixels. Breakthrough demonstrating deep RL viability.

### Chess AI
AlphaZero-inspired approach combining search, neural networks, and self-play. Learning strong chess strategies without human examples.

### Multi-Agent Cooperation
Agents learning to cooperate on shared tasks. Requiring communication, trust, and coordinated strategy.

### Robotic Simulation
Continuous control tasks like navigation, manipulation, locomotion. Transfer learning from simulation to real robots.

## Critical Insight

Reward design determines what the agent learns. Get it wrong and the agent optimizes the wrong objective. Proxies for real goals often have perverse consequences. Careful reward engineering is harder than algorithm selection.

## Research Interests

- Sample efficiency in RL (learning faster with less data)
- Transfer learning across tasks and domains
- Sim-to-real transfer reducing real-world trial-and-error
- Interpretability of learned policies
- Safe reinforcement learning with constraints

---

*Teaching machines to make decisions.*
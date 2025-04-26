# MARIO-RL

## Super Mario AI - Random Play, PPO Training (Stable-Baselines3), and Custom Reward Optimization

This repository showcases an AI agent learning to play **Super Mario** using Reinforcement Learning. It demonstrates three stages: random action play, PPO training with **Stable-Baselines3**, and enhanced PPO with a custom reward function focused on coin collection.

---

## Overview

The notebook performs:

- 🎲 Random action agent (baseline without reward focus)
- 🧠 PPO (Proximal Policy Optimization) agent training using Stable-Baselines3
- 🪙 Custom reward shaping: +5 reward for collecting coins
- 🎥 Displaying gameplay videos using IPython display
- 🏆 Best agent achieves maximum coins collected so far

---

## Features

- Compare random actions vs learned policy
- Train agents using Stable-Baselines3 PPO
- Custom environment wrapper for enhanced rewards
- Visualize training progress through videos
- Track maximum performance improvements

---

## Requirements

Install the necessary libraries:

```bash
pip install gymnasium ale-py moviepy torch stable-baselines3
```
---

## Usage
Clone this repository:

```bash
git clone https://github.com/CaptainErek/mario-rl.git
cd mario-rl
```

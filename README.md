# 🃏 Reinforcement Learning BlackJack Player

**Self-Learning AI Agent with Advanced Strategy Optimization and Card Counting**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Reinforcement Learning](https://img.shields.io/badge/RL-Q--Learning-red.svg)]()
[![Game Theory](https://img.shields.io/badge/Game%20Theory-Strategy%20Optimization-green.svg)]()
[![Research Paper](https://img.shields.io/badge/IEEE-Conference%20Paper-orange.svg)]()
[![University Project](https://img.shields.io/badge/University-THWS-purple.svg)](https://www.thws.de/)

> **Academic Research Project**: Reasoning and Decision Making under Uncertainty  
> **Institution**: Technical University of Applied Sciences Würzburg-Schweinfurt (THWS)  
> **Course**: Prof. Dr. Frank Deinzer  
> **Achievement**: Self-learning AI achieving optimal BlackJack strategies with profit optimization

## 🎯 Project Overview

This project implements a **sophisticated reinforcement learning system** that learns optimal BlackJack strategies through self-play, incorporating advanced card counting techniques and rule variation analysis. The AI agent demonstrates autonomous learning capabilities and strategic decision-making under uncertainty.

### 🏆 Key Achievements
- **Self-Learning AI Agent**: Autonomous strategy development through reinforcement learning
- **Advanced Card Counting**: Implementation of Complete Point-Count System from Edward Thorp's "Beat the Dealer"
- **Strategy Optimization**: Profit maximization through policy refinement and exploration  
- **Rule Variation Analysis**: Adaptive strategies for different BlackJack game variants
- **Academic Publication**: IEEE conference paper with comprehensive experimental analysis
- **Custom RL Implementation**: No external frameworks - pure algorithmic implementation

## 🔬 Technical Implementation

### **Research Tasks Completed**

#### **Task P3.1: Reinforcement Learning Implementation**
1. **Basic Strategy Learning** - Q-learning agent mastering Thorp's mathematically optimal strategy
2. **Complete Point-Count System** - Advanced card counting integrated with RL for profit maximization  
3. **Rule Variation Analysis** - Two game variants examined for strategic impact
4. **Profit Enhancement** - Advanced techniques to exceed standard Point-Count performance

#### **Task P3.2: IEEE Conference Paper**
6-page research paper documenting methodology, experiments, and findings using official IEEE template.

### **Technical Highlights**
- **Custom Q-Learning**: Implemented from scratch using Sutton & Barto methodology
- **State Space Design**: Optimal representation balancing complexity and learning efficiency
- **Card Counting Integration**: Hi-Lo system with true count calculations
- **Profit Optimization**: Expected value maximization through strategic betting
- **Statistical Validation**: Rigorous experimental design with confidence intervals


### **Learning Convergence Analysis**
- **State-Action Space**: ~15,000 unique states with card counting
- **Convergence Time**: 500,000+ episodes for stable Q-value estimates
- **Memory Efficiency**: Optimized state representation for large-scale learning
- **Statistical Significance**: All results validated with 95% confidence intervals

## 🚀 Getting Started

### **Prerequisites**
```bash
Python 3.8+
NumPy >= 1.21.0
Matplotlib >= 3.4.0
Pandas >= 1.3.0
Jupyter >= 1.0.0

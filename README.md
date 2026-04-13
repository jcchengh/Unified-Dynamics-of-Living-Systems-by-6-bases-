Unified-Dynamics-of-Living-Systems-by-6-bases README.md

# Unified-Dynamics-of-Living-Systems-by-6-bases

This repository provides the code and related materials for the research paper Unified Dynamics of Living Systems: A Cross-Model Unified Framework Based on Normalized Nonlinear Response Classes and Its Cross-Scale Implications.

The core goal of this research is to reveal the underlying structural correlations of six classical dynamic models of living systems, unify them into a single normalized nonlinear response class, and provide a unified perspective for cross-scale dynamic research of living systems.

## Overview

Living systems' core dynamic processes (molecular, cellular, cognitive scales) are typically described by field-specific classical models. This study finds that six key models (Michaelis-Menten equation, Hill equation, Boltzmann distribution, logistic equation, Langmuir adsorption isotherm, Nernst equation) all belong to the same normalized nonlinear response class, uniformly expressed as $$f(x) = \frac{x^n}{1+x^n}$$.

Key findings include:

- All models correspond to the half-saturation point (φ=0.5) under their characteristic parameters, which has maximum sensitivity and maximum information gradient.

- Nonlinear systems can spontaneously generate intrinsic stable structures (fixed point φ≈0.618), explaining the general dynamic mechanism of living systems' stable states.

- The nonlinear response class has cross-scale consistency, spanning prebiochemistry, molecular biology, cellular systems, and neuroscience.

## Repository Structure

The repository contains the following core files (consistent with the research paper):

- `unified_dynamics_analysis.py`: Core code for normalization processing, nonlinear response analysis, and critical point verification of the six classical models.

- `README.md`: Repository introduction and usage instructions (this file).

## Code Usage

### Dependencies

The core code is implemented in Python (single file), and the required dependencies are as follows:

numpy>=1.21.0
scipy>=1.7.0
matplotlib>=3.4.0
pandas>=1.3.0



生命系统统一动力学——基于6类基础模型的研究仓库 README.md（纯中文版）

# 生命系统统一动力学——基于6类基础模型的研究仓库

本仓库提供论文《生命系统统一动力学：基于归一化非线性响应类的跨模型统一框架与跨尺度启示》的相关代码及配套资料。

本研究的核心目标是揭示生命系统6类经典动力学模型的底层结构关联性，将其统一到单一归一化非线性响应类中，为生命系统跨尺度动力学研究提供统一视角。

## 研究概述

生命系统的核心动力学过程（分子、细胞、认知尺度）通常由各领域特异性经典模型描述。本研究发现，6类关键模型（米氏方程、希尔方程、玻尔兹曼分布、逻辑斯蒂方程、朗缪尔吸附等温式、能斯特方程）均属于同一归一化非线性响应类，可统一表示为$$f(x) = \frac{x^n}{1+x^n}$$。

核心研究结果包括：

- 所有模型在其特征参数条件下，均对应半饱和点（φ=0.5），该点具有最大敏感性与最大信息梯度。

- 非线性系统可自发产生内禀稳定结构（不动点φ≈0.618），可阐释生命系统稳定态的通用动力学机制。

- 该非线性响应类具有跨尺度一致性，涵盖前生化学、分子生物学、细胞系统及神经科学领域。

## 仓库结构

本仓库包含以下核心文件（与论文内容一致，无多余文件）：

- `unified_dynamics_analysis.py`：6类经典模型的归一化处理、非线性响应分析及临界点验证核心代码（。

- `README.md`：仓库介绍及使用说明（本文档）。

## 代码使用说明

### 依赖环境

核心代码采用Python实现（单文件），所需依赖环境如下：

numpy>=1.21.0
scipy>=1.7.0
matplotlib>=3.4.0
pandas>=1.3.0


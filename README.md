# Newsvendor-Transformer 项目
## Introduction
本项目是基于 Transformer 模型的报童问题（Newsvendor Problem）库存优化预测工具，用于预测服饰类商品的最优订货量，辅助电商平台库存决策。

The Newsvendor problem is a fundamental model in inventory management, aiming to balance the costs of overstocking and understocking under demand uncertainty. With the advent of big data, data-driven approaches that utilize feature information (covariates) $X$ to predict demand $D$ have gained prominence. In this work, we propose the Newsvendor-Transformer, a deep learning framework that directly learns the optimal inventory policy from data using the Transformer architecture.
While Transformers have achieved remarkable success in sequence modeling, their theoretical properties in regression tasks—particularly under asymmetric loss functions like the Newsvendor loss—remain under-explored. We bridge this gap by providing non-asymptotic excess risk bounds, characterizing both the approximation capabilities of Transformers for H\"older functions and their statistical generalization properties.

##  tech stack
- Python
- PyTorch / Transformer
- Matplotlib / Seaborn

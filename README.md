# Gpt2-inverse_scaling_solution


This project addresses the inverse scaling issue observed in transformer models, where larger models exhibit decreased performance. By integrating an Adaptive Attention mechanism into the GPT-2 model, we aim to enhance its efficacy. We evaluate the modified GPT-2 variants on three inverse scaling tasks – Pattern Matching Suppression, Modus Tollens, and Memo Trap. Results show improved performance in Pattern Matching Suppression and Memo Trap, while Modus Tollens remains challenging even in the modified version.

## Problem Statement:

Large language models (LLMs) experience diminished performance as they scale up, contrary to expectations. We propose integrating the Adaptive Attention span method into the GPT-2 architecture to address this issue. This method dynamically adjusts attention spans across transformer layers, enhancing the model's ability to handle diverse context lengths efficiently.

## Dataset and Task Details:

We utilize the Inverse Scaling Dataset, focusing on three tasks – Memo Trap, Modus Tollens, and Pattern Match Suppression. These tasks evaluate the model's resistance to memorization, deductive reasoning ability, and capacity to break repetitive patterns, respectively.

## Mathematical Details:

Adaptive Attention introduces learned attention spans for each head in the transformer model. This approach dynamically adjusts attention weights based on the learned span parameter, reducing computational complexity and enabling better handling of longer sequences.

## Conclusion and Future Work:

The modified GPT-2 with Adaptive Attention shows varied impacts on task performance. While Pattern Matching Suppression benefits from scalability, Modus Tollens performance peaks at intermediate model sizes. The Memo Trap task demonstrates consistent improvement across model sizes. Future work could involve training data from scratch and exploring combinations of different attention mechanisms.

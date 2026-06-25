# Emotion-Conditioned Adaptive Response Generation (ECARG)

Official implementation accompanying the paper:

**Emotion-Conditioned Reinforcement Learning for Adaptive Empathetic Response Generation in Human–AI Interaction**



ECARG consists of:

1. Multimodal Emotion-State Estimation (MESE)
2. PPO-based therapeutic policy learning
3. Dual-format GPT-2 response generation

## Datasets

- MELD
- EmpatheticDialogues
- DailyDialog

Please download the datasets from their official sources.

## Main Results

- Weighted-F1: **0.593**
- Macro-F1: **0.455**
- Reward Ablation: **0.226 → 0.518**
- ΔValence: **+0.365**
- Safety Score: **0.993**
- Safety Improvement: **13.4 percentage points**
- Cross-domain Composite Improvement: **36.3%**
- SHAP Stability: **70–100%**

## Installation

```bash
pip install -r requirements.txt
```

## Execution Order

1. 01_mese_emotion_state_estimation.ipynb
2. 02_rl_policy_training.ipynb
3. 03_model_comparison.ipynb
4. 04_vad_simulation.ipynb
5. 05_safety_analysis.ipynb
6. 06_domain_adaptation.ipynb
7. 07_shap_interpretability.ipynb

## Citation

```
@article{ECARG2026,
  title={Emotion-Conditioned Reinforcement Learning for Adaptive Empathetic Response Generation in Human--AI Interaction},
  journal={Under Review},
  year={2026}
}
```

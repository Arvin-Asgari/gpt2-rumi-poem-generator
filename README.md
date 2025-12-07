# GPT-2 Rumi Poem Generator 🪶✨

**Fine-tuned Persian GPT-2 on 6000+ lines of Rumi poetry** to generate creative poems from any input prompt.

## 📋 Features
- Fine-tuned `HooshvareLab/gpt2-fa` on extensive Rumi poetry dataset
- Interactive poem generation with advanced sampling (top-k=50, top-p=0.95)
- Temperature-controlled creativity (0.7 default)
- Generates multiple poem variations per prompt

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C?style=flat&logo=PyTorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-%23FFD21E?style=flat&logo=huggingface&logoColor=black)

## 🚀 Quick Start

**1. Install Dependencies**
```bash
pip install torch transformers datasets accelerate
```

**2. Train Model**
*(Requires a text file containing Rumi's poetry)*
```bash
python poem_generator.py --train
```

**3. Generate Poems**
```bash
python poem_generator.py --generate "دلبر"  # Enter Persian prompt
```

## 🎯 Example Output

```text
Prompt: "دلبر"
Output: "دلبرا که در خلوت منی و در شادی منی..."
```

## 📁 Files
```text
├── poem_generator.py      # Fine-tuning + inference pipeline
└── requirements.txt       # Dependencies
```

## 🎓 What I Learned
- **Hugging Face Trainer API** for efficient fine-tuning
- **Advanced text generation parameters** (top-k/p, temperature)
- **Persian NLP model adaptation** and tokenization challenges

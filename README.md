## 📊 Результаты экспериментов

| Model | Accuracy | Precision | Recall | F1‑Score | ROC‑AUC | Inference Time (ms) |
|-------|----------|-----------|--------|----------|---------|---------------------|
| DistilBERT (fine‑tuned) | 0.8441 🟢 | 0.8452 | 0.7766 | 0.8094 🟢 | 0.8910 | 180 |
| Sentence‑Transformers + Logistic Regression | 0.8148 🟢 | 0.7743 | 0.8028 | 0.7883 🟡 | 0.8889 | 45 |
| TF‑IDF + Logistic Regression | 0.8048 🟡 | 0.7698 | 0.7734 | 0.7716 🟡 | 0.8623 | 12 |

## 🏆 Лучшая модель

**DistilBERT (fine‑tuned)** показал лучший результат:

- **Accuracy:** 84.41%
- **F1‑Score:** 80.94%
- **ROC‑AUC:** 89.10%

### Выводы

1. **DistilBERT** значительно улучшил качество классификации по сравнению с классическими методами.
2. **Sentence‑Transformers + Lofistic Regression** дал хороший баланс между качеством и скоростью.
3. **TF‑IDF + Logistic Regression** — самый быстрый, но немного уступает по качеству.


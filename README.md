# FractalNet
Lightweight fractal-based PyTorch architecture for image classification. Used in Nov Zhivot AI project.
# 🧠 FractalNet — AI архитектура с фрактална логика

**FractalNet** е лека PyTorch архитектура, базирана на фрактални блокове, предназначена за класификация на изображения. Използва се като база в проекта [Нов Живот](https://github.com/AlexKitipov/nov-jivot-lab) — за демонстриране на AI анализ, подобрение и възстановяване на код.

---

## 🔹 Основни характеристики
- Фрактални блокове с параметрична дълбочина
- Stem входен слой + adaptive classifier
- Предварително подготвени за CIFAR-10 / други vision datasets
- Modular структура: `blocks.py`, `model.py`, `train.py`

---

## 💡 Интеграция в „Нов Живот“
Проектът FractalNet служи като еталонен модел за анализ чрез Gemini. Бележникът генерира предложения за подобрения, документация и тестове. Промените се публикуват с уважение към оригиналния код — чрез fork или pull request.

---

## ⚙️ Стартиране

```bash
git clone https://github.com/AlexKitipov/FractalNet.git
cd FractalNet
pip install -r requirements.txt
python train.py --dataset cifar10

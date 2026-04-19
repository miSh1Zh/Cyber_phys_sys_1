# Лабораторная работа 1: киберфизические системы

**Курс:** Киберфизические системы  
**Студент:** Жаднов Михаил  
**Группа:** М8О-406Б-22

## Описание

Репозиторий содержит лабораторную работу 1 по классификации изображений (типы переломов). Датасет: [bone-break-classification-image-dataset](https://www.kaggle.com/datasets/pkdarabi/bone-break-classification-image-dataset?resource=download). Изображения распакованы в `data/Bone Break Classification/`. В `main.ipynb` — бейзлайн на torchvision (ResNet18 и ViT-B/16), улучшение бейзлайна, собственная CNN и сравнения по метрикам.

## Запуск

```bash
cd lab_1
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

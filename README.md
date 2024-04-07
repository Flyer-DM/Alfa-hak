*From anpilove*
- файл `baseline.ipynb` не трогать.
- С установкой lightgbm была проблема решил - brew install libomp.
- pip install pyarrow # for read file .pqt
- Время работы - 310 секунд в Colab. Почему-то у меня пока пробелемы с Jupyter.
```python
model = LGBMClassifier(verbosity=-1, random_state=42, n_jobs=-1)
model.fit(x_train, y_train)
```

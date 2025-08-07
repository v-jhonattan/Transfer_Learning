# 🌸 Oxford Flowers 102 Classifier

Modelo de classificação de flores com 83.74% de acurácia usando EfficientNetB0

## 📊 Resultados do Treinamento
| Métrica         | Treino | Validação | Teste |
|-----------------|--------|-----------|-------|
| **Acurácia**    | 99.66% | 85.69%    | 83.74%|
| **Loss**        | 0.0263 | 0.5732    | 0.6660|


## 🛠️ Tecnologias
- TensorFlow 2.x
- EfficientNetB0 (transfer learning)
- Data Augmentation
- Class Weight Balancing


## 🚀 Como Usar
1. **Carregar o modelo**:
```python
import tensorflow as tf
model = tf.keras.models.load_model('models/flower_model.h5')

📝 Melhorias Futuras

Aumentar para resolução 300x300
Testar EfficientNetB3
Implementar Grad-CAM para explicação
📄 Licença

MIT License - Livre para uso acadêmico e comercial

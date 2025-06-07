# 🧠 Fashion MNIST Image Classifier API

Uma API em Flask para classificar imagens em tons de cinza 28x28 utilizando um modelo treinado no dataset Fashion MNIST com TensorFlow.

---

## 🚀 Tecnologias

- Python 3.8+
- Flask
- TensorFlow / Keras
- NumPy
- Pillow (PIL)

---

## 📁 Estrutura do Projeto

```
projeto_fashion_mnist_api/
├── .gitignore                        # Ignora o venv e arquivos desnecessários
├── Projeto1VisãoComputacional.ipynb  # Modelo construído
├── README.md                         # Este arquivo
├── app.py                            # API Flask principal
├── fashion_mnist_cnn_model.keras     # Modelo treinado (formato .keras)
└── requirements.txt                  # Dependências do projeto
```

---

## ⚙️ Como rodar o projeto localmente


```bash
# Clonar projeto
git clone github.com/marchiorog/projeto_fashion_mnist_api
cd projeto_fashion_mnist_api

# Ambiente virtual
python -m venv venv
venv\Scripts\activate

#Instalar dependências
pip install -r requirements.txt

# Iniciar a API
python app.py

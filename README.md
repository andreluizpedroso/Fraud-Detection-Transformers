# Detecção de Fraudes em Sinistros com BERT

Este projeto utiliza **BERT (Bidirectional Encoder Representations from Transformers)** para analisar relatos de sinistros e detectar possíveis fraudes. O modelo classifica um relato como **"Fraude Detectada"** ou **"Sinistro Legítimo"** com base em padrões textuais.

## 📌 Tecnologias Utilizadas
- Python 3
- TensorFlow
- Transformers (Hugging Face)

## 🚀 Como Funciona?
1. O código carrega o modelo **BERT pré-treinado**.
2. O relato do sinistro é **tokenizado e pré-processado**.
3. O modelo classifica o texto como **fraude ou legítimo**.

## 🛠️ Como Executar o Projeto

### 1️⃣ Instalar Dependências
Certifique-se de ter o Python instalado e execute:
```bash
pip install tensorflow transformers numpy
```

### 2️⃣ Executar o Código
Crie um arquivo Python (`fraud_detection.py`) e adicione o código do projeto. Depois, execute:
```bash
python fraud_detection.py
```

## 📖 Exemplo de Uso
```python
example_claim = "O carro foi roubado, mas não há boletim de ocorrência disponível."
resultado = detect_fraudulent_claim(example_claim)
print(resultado)  # "Fraude Detectada" ou "Sinistro Legítimo"
```

## 📝 Contribuição
Sinta-se à vontade para contribuir com melhorias! Basta abrir um **pull request** ou relatar problemas na seção de **issues**.

## 📜 Licença
Este projeto está licenciado sob a **MIT License**.


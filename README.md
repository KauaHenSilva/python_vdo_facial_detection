# Detecção de Faces em Vídeo com OpenCV no Google Colab

Este repositório contém dois Jupyter Notebooks que demonstram a detecção de faces em vídeos utilizando a biblioteca OpenCV. São apresentadas duas abordagens distintas: o método Haar Cascade e o SSD (Single Shot Detector). Ambos os notebooks são otimizados para execução no **Google Colab**, permitindo testar e visualizar os resultados diretamente na nuvem.

---

## Notebooks

### `face_detection_ssd.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_vdo_facial_detection/blob/main/SSD.ipynb)

**Funcionalidade:** Detecção de faces utilizando um modelo SSD pré-treinado.

Este notebook implementa a detecção de faces usando a técnica SSD, que emprega redes neurais convolucionais para identificar faces em vídeos com alta precisão.

#### Principais Funcionalidades:
- Uso de modelo pré-treinado para detecção de faces.
- Suporte para vídeos armazenados no Google Drive.
- Identificação precisa de múltiplas faces simultaneamente.
- Exibição dos resultados diretamente no notebook.

---

### `face_detection_haar.ipynb` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_vdo_facial_detection/blob/main/haar_cascade.ipynb)

**Funcionalidade:** Detecção de faces utilizando Haar Cascade.

Este notebook usa a técnica clássica de Haar Cascade, que aplica um classificador treinado para identificar padrões faciais em imagens e vídeos.

#### Principais Funcionalidades:
- Algoritmo leve e eficiente para detecção de faces.
- Processamento em tempo real adequado para dispositivos com menos poder computacional.
- Suporte para redimensionamento de vídeos para melhor desempenho.
- Exibição de resultados no Google Colab.

---

## Como Usar no Google Colab

Para executar os notebooks no Google Colab, siga os passos abaixo:

1. **Acesse o Google Colab:**
   - Abra o [Google Colab](https://colab.research.google.com/).

2. **Carregue os Notebooks:**
   - Clique em `Arquivo` > `Abrir notebook`.
   - Escolha a aba `GitHub` e insira o link deste repositório.
   - Selecione o notebook desejado (`face_detection_ssd.ipynb` ou `face_detection_haar.ipynb`).

3. **Conecte ao Google Drive (se necessário):**
   - Alguns notebooks exigem acesso ao Google Drive para carregar vídeos e modelos.

4. **Execute as Células:**
   - Conecte-se ao ambiente clicando em `Conectar` no canto superior direito.
   - Execute as células sequencialmente para processar o vídeo e visualizar os resultados.

5. **Teste com seus Próprios Vídeos (Opcional):**
   - Faça o upload de um vídeo diretamente no Google Colab usando:
     ```python
     from google.colab import files
     uploaded = files.upload()
     ```
   - Substitua o caminho do vídeo no notebook pelo arquivo enviado.

---  

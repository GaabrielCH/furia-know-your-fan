# Know Your Fan

## Visão Geral
Know Your Fan é uma aplicação baseada em Jupyter Notebook que permite às organizações de e-sports criar perfis detalhados de seus fãs, validar documentos, analisar comportamentos de consumo e gerar recomendações personalizadas. O sistema utiliza técnicas de processamento de imagem, OCR e análise de dados para construir um perfil completo de engajamento do fã.

## ✨ Funcionalidades

### Gerenciamento de Perfil do Fã
- Coleta e armazenamento de informações pessoais
- Registro de interesses em e-sports, times favoritos e jogos
- Acompanhamento de eventos assistidos e compras realizadas

### Validação de Documentos
- Processamento de imagens de documentos via OCR
- Verificação de correspondência entre dados informados e documentos
- Detecção de entidades (nome, CPF, endereço)

### Integração com Redes Sociais
- Vinculação de perfis de Twitter e Instagram
- Análise de engajamento nas redes sociais relacionado a e-sports

### Validação de Perfis de E-sports
- Integração com plataformas como FACEIT, ESL, Battlefy e outras
- Verificação de autenticidade dos perfis de jogador

### Análise de Engajamento
- Dashboard visual com métricas de engajamento
- Cálculo de pontuação de engajamento (0-100)
- Classificação em níveis (Iniciante, Casual, Engajado, Dedicado, Superfã)

### Recomendações Personalizadas
- Sugestões de eventos, produtos e conteúdo com base no perfil
- Recomendações contextualizadas por jogos e times favoritos

## 🔧 Requisitos
- Python 3.7+
- Jupyter Notebook ou JupyterLab
- Bibliotecas Python:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - opencv-python
  - pytesseract
  - ipywidgets
- Tesseract OCR (para processamento de documentos)

## 📥 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/know-your-fan.git
cd know-your-fan
```

2. Instale as dependências:

```bash
pip install ipywidgets opencv-python-headless pytesseract pandas numpy matplotlib seaborn
```

3. Instale o Tesseract OCR (necessário para processamento de documentos):

```
Faça o download do instalador em: https://github.com/UB-Mannheim/tesseract/wiki
```

ou
```
apt-get install -y tesseract-ocr
apt-get install -y tesseract-ocr-por  # Para suporte ao português
```

4. Inicie o Jupyter Notebook e abra o arquivo do projeto:

```
know_your_fan.ipynb
```

## Uso

Execute as células do notebook na ordem para:

     Configurar o ambiente

     Coletar informações do fã

     Validar documentos

     Analisar engajamento

     Gerar recomendações personalizadas


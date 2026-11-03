# Catálogo Digital Interativo — Sistema 0

Catálogo digital executivo em formato de revista 3D folheável (*flipbook*), com diagramação editorial de alta resolução, suporte completo a gestos de toque no celular (*swipe*) e responsividade automática para qualquer tela.

## 🚀 Como Executar Localmente

```bash
pip install -r requirements.txt
python server.py
```

Acesse no navegador:
`http://localhost:8000/` ou `http://localhost:8000/catalogo`

## ☁️ Deploy no Render

Este repositório já inclui o arquivo `render.yaml` pré-configurado.

1. No painel do [Render](https://dashboard.render.com/), clique em **New +** -> **Web Service** (ou **Blueprint**).
2. Conecte este repositório `catalogo-sistema-zero`.
3. O Render configurará automaticamente o build (`pip install -r requirements.txt`) e o comando de inicialização (`python server.py`).
4. Em instantes, o link público `https://catalogo-sistema-zero.onrender.com` estará ativo com HTTPS gratuito para compartilhar com qualquer pessoa.


# 🧠 Classificador de Doenças com Flask

Um aplicativo web simples que utiliza Flask para analisar sintomas descritos por texto e classificá-los em **Benigna**, **Leve** ou **Grave**, com base em palavras-chave. A interface conta com um visual moderno em estilo neon, responsiva e clara.

> 🚨 **Aviso:** Este sistema é apenas para fins educacionais e **não substitui um diagnóstico médico profissional**.

## 📸 Demonstração

Acesse o repositório: [github.com/Alison148/Classificador-de-Doen-as](https://github.com/Alison148/Classificador-de-Doen-as)

## 💡 Funcionalidades

- Interface estilizada com HTML + CSS puro (tema escuro neon)
- Classificação baseada em palavras-chave
- Ícones FontAwesome indicam o tipo de condição
- Feedback visual com cores:
  - ✅ Benigna (verde)
  - 🟡 Leve (amarelo)
  - 🔴 Grave (vermelho)
  - ⚠️ Erro (vermelho)

## 🚀 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/Alison148/Classificador-de-Doen-as.git
cd Classificador-de-Doen-as
2. (Opcional) Crie e ative um ambiente virtual
bash
Copiar
Editar
python -m venv venv
# No Windows:
venv\Scripts\activate
# No Linux/macOS:
source venv/bin/activate
3. Instale as dependências
bash
Copiar
Editar
pip install Flask
4. Execute a aplicação
bash
Copiar
Editar
python app.py
Abra no navegador:
http://localhost:5000

🧪 Exemplos de Entrada
Febre alta, tosse seca e dor no corpo → Grave

Dor de cabeça, congestionado e leve febre → Leve

Me sinto saudável, sem sintomas → Benigna

Tumor maligno no fígado, comecei quimioterapia → Grave

📁 Estrutura
csharp
Copiar
Editar
Classificador-de-Doen-as/
├── app.py                 # Lógica principal em Flask
├── templates/
│   └── index.html         # Página HTML principal
└── README.md
👨‍💻 Desenvolvido por
Alison Antunes
github.com/Alison148

📄 Licença
Este projeto é open-source e pode ser usado livremente com fins acadêmicos ou de demonstração.
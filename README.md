# 🤖 Zapeteco

O Zapeteco cuida do seu atendimento no WhatsApp: envia o cardápio, pega o pedido, coleta nome, endereço e forma de pagamento — tudo no automático.

---

## 🍽️ Visão Geral do Projeto

O **Zapeteco** é um bot de automação desenvolvido em Python para auxiliar restaurantes a gerenciarem seus pedidos de forma rápida, prática e automatizada via **WhatsApp**.

Ele permite:

- Enviar automaticamente o **cardápio do dia** para os clientes.
- Permitir que o cliente **escolha os pratos** (ex: Arroz, Baião, Feijão, Carne, etc).
- Coletar informações importantes como:
  - Nome
  - Endereço
  - Forma de pagamento
- Registrar e armazenar pedidos de forma organizada.
- Futuramente, ser usado como **modelo base para outros estabelecimentos** personalizarem o bot com seus próprios cardápios e mensagens.

---

## ⚙️ Tecnologias Utilizadas

- **Python**
- **Twilio API / WhatsApp Business API**
- **Flask** *(para futura API REST)*
- **SQLite** *(armazenamento local dos dados)*
- *(Futuro)*: Interface web/admin com **Streamlit** ou **React**

---

## 🏗️ Estrutura do Projeto

zapeteco/  
├── 📁 src/ # Código-fonte principal  
│ ├── bot/ # Lógica do bot e fluxo de mensagens  
│ ├── data/ # Armazenamento de pedidos e clientes  
│ └── utils/ # Funções auxiliares  
├── 📁 assets/ # Imagens ou arquivos de mídia (ex: cardápios)  
├── 📁 docs/ # Documentação e instruções do projeto  
├── requirements.txt # Dependências do Python  
└── README.md # Este arquivo  

---

## 🚀 Início Rápido

### ✅ Pré-requisitos

- Python 3.10 ou superior
- Conta no [Twilio](https://www.twilio.com/) ou acesso à API oficial do WhatsApp Business
- Git instalado na máquina

### 🔧 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/zapeteco.git

# Acesse o diretório do projeto
cd zapeteco

# Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Execute o bot
python src/bot/main.py

```

##  💡 Como Funciona?

1. O restaurante cadastra o cardápio do dia (pode ser em texto, imagem ou integrado no código).
2. O bot envia o cardápio automaticamente para os clientes via WhatsApp.
3. O cliente responde escolhendo os pratos desejados (ex: arroz, baião, feijão...).
4. O bot interage com o cliente coletando:
   - Nome
   - Endereço
   - Forma de pagamento (ex: Pix, dinheiro, cartão)
5. O pedido é armazenado e pode ser encaminhado para a cozinha ou sistema de gestão.

---

## 🔄 Futuras Funcionalidades

- Painel web para visualizar pedidos em tempo real
- Cadastro e histórico de clientes
- Integração com sistemas de pagamento (Pix, cartão)
- Personalização do cardápio via painel administrativo
- Suporte para múltiplos estabelecimentos
- Agendamento de envio automático de cardápios
- Exportação de relatórios em PDF/Excel

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para colaborar com o **Zapeteco**, siga os passos abaixo:

1. Faça um **fork** do repositório
2. Crie uma nova branch:

```bash
git checkout -b feature/sua-nova-feature
```
Faça os commits das suas alterações:
``` bash
git commit -m 'feat: adiciona nova feature'

```
Envie para o repositório remoto:
``` bash
git push origin feature/sua-nova-feature
```

Abra um Pull Request com uma breve descrição da melhoria ou correção


## 👩‍💻 Autora

| 💁‍♀️ Nome   | 🌐 GitHub | 💼 LinkedIn | 📧 Email |
|------------|-----------|-------------|----------|
| Marisol Sales Marinho Roque | [@Occeansun](https://github.com/Occeansun) | [linkedin.com/in/marisol-sales-marinho-69ab20306](https://linkedin.com/in/marisol-sales-marinho-69ab20306) | marisolsales01@gmail.com |

 
## ⭐ Apoie o Projeto

Se o Zapeteco te ajudou ou te inspirou, deixe uma estrela ⭐ no repositório!
Isso ajuda o projeto a ganhar visibilidade e a crescer na comunidade open source.

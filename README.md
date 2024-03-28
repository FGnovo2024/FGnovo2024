- 👋 Hi, I’m @FGnovo2024
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
FGnovo2024/FGnovo2024 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Substitua pelas suas credenciais
client_id = 'seu_client_id'
client_secret = 'seu_client_secret'
certificate_path = 'caminho_para_o_certificado.pem'

# Crie uma instância do cliente Pix
pix = Pix(client_id, client_secret, certificate_path)

# ID da transação Pix que você deseja verificar
transaction_id = 'id_da_transacao_pix'

# Verifique o status da transação
transaction_status = pix.transaction_status(transaction_id)

# Imprima o status da transação
print("Status da transação Pix:", transaction_status)

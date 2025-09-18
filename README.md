✅ Passo a Passo para Criar uma VM Gratuita na Azure
1. Criar uma Conta Gratuita
Acesse portal.azure.com e clique em "Iniciar gratuitamente".
Será necessário informar um cartão de crédito para verificação, mas não haverá cobrança imediata 1.
2. Acessar o Portal do Azure
Após o login, vá até o menu lateral e clique em "Criar um recurso" > "Máquina Virtual" 2.
3. Configurar a Máquina Virtual
Grupo de Recursos: Crie um novo ou use um existente.
Nome da VM: Escolha um nome como MinhaVM.
Região: Selecione uma próxima de você (ex: "Brazil South").
Imagem: Escolha entre Windows Server ou Ubuntu (Linux).
Tamanho: Selecione uma opção gratuita, como B1s (1 vCPU, 1 GB RAM).
Usuário e Senha: Crie credenciais seguras para acesso.
4. Configurar Rede e Segurança
Permita portas como:
RDP (3389) para Windows
SSH (22) para Linux
Configure regras básicas de firewall.
5. Revisar e Criar
Clique em "Revisar + Criar" e depois em "Criar".
Aguarde a implantação da VM.
6. Conectar à VM
Para Windows: use o arquivo RDP gerado para acesso remoto.
Para Linux: conecte via SSH usando o IP público e chave privada 1.

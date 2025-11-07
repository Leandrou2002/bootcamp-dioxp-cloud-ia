# 3️⃣ Ajuste as Configurações Básicas



* Configure as especificações da máquina virtual de acordo com a necessidade do seu projeto ou cliente
* Nesta primeira parte da página os campos obrigatórios serão os seguintes: Assinatura, Grupo de Recursos (caso não tenha um criado é só clicar em "Criar Novo" e nomear um novo grupo), Nome da Máquina Virtual, Região e Zona de Disponibilidade

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

*   Descendo um pouco mais a página os campos obrigatórios serão os seguintes: Imagem (Sistema Operacional que será executado), Tamanho (A configuração de quantidade de núcleso e memória que será disponibilizada), Nome de Usuário e Senha (Dados utilizados para o acesso da VM)\


    <figure><img src="../.gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>
* Mais abaixo na ultima seção da página temos os campos: Portas de entrada públicas (onde pode se permitir ou não portas de entrada) e Selecione as portas de entrada (onde podemos selecionar HTTP, HTTPS, SSH e RDP), porém como o próprio Azure diz, essa configuração deixa sua VM vulnerável ao acesso de qualquer IP

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

* Após selecionar as configurações básicas de acordo com as necessidades você pode continuar com as outras configurações no padrão que vem selecionado pelo Azure clicando no botão azul escrito "Revisar + Criar", caso queira adaptar configurações mais avançadas como Disco, Rede, Gerenciamento e Monitoramento basta clicar em "Avançar"

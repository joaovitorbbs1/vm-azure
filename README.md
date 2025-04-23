# 🖐️ João Vitor
[![E-mail](https://img.shields.io/badge/-Email-000?style=for-the-badge&logo=microsoft-outlook&logoColor=2BFD05)](mailto:joaovitorbbs1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=2BFD05)](https://www.linkedin.com/in/joaovitorbbs/)

Olá, eu sou o João Vitor e estou começando minha trilha de aprendizado na área de tecnologia.


## 🖥️ Máquina Virtual

Uma máquina virtual consiste na virtualização do hardware de um computador, com o objetivo de criar uma instância de sistema operacional sobre de outro. Ela opera como um sistema independente, no entanto compartilha os componentes físicos com outras VMs.

### 🛠️ Criando uma máquina virtual simples no Azure

- Com login efetuado no Portal Azure, clica no ícone Máquinas Virtuais > Criar > Máquina Virtual do Azure.

![](https://i.ibb.co/mrcFmnNY/Captura-de-Tela-96.png)

- Abrirá um página contendo campos para preenchimento sobre as informações básicas da VM. No primeiro campo obrigatório, seleciona um grupo de recursos. Em seguida, dá-se um nome e escolhe-se a região e a zona onde o sistema ficará armazenado (essa escolha é importante, pois, a depender da localidade, a latência e o custo geral sofrerá alterações). Deixarei as escolhas padrões.

![](https://i.ibb.co/QjH9vhbd/Captura-de-Tela-97.png)

- Em imagem, selecione o sistema operacional que deseja instalar. Há uma lista com vários SO. Aqui eu escolhi o 'Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2'. As outras opções deixa nas escolhas padrões.

![](https://i.ibb.co/gLmY5DyP/Captura-de-Tela-99.png)

- Em seguida, faz-se a conta de administrador. Essa conta vai ser usada dentro so sistema operacional com privilégios de administrador. Em 'Porta de entrada pública' selecione a opção de permissão e em seguida escolha as portas para conexão. Vou habilitar a porta 3389 (RDP) e 80 (HTTP). Por fim, pode clicar em 'Revisar + Criar'.
- Quando passar pela validação, clica em 'Criar'.
- Quando concluir a implementação, clique em 'Ir para o recurso'.

![](https://i.ibb.co/DDYJ55T2/Captura-de-Tela-101.png)

- Para fazer a conexão remota, na página do recurso(da instância da máquina), clica em Conectar e selecione Conectar. Na página que se abrir, clique no botão 'Baixar arquivo RDP'.

- No seu computador pessoal, execute o arquivo RDP e clique em Conectar. Na aba de Segurança do Windows, selecione 'mais opções', 'usar uma conta diferente' e faça login usando localhost\nome de usuário e a senha que configurou para a máquina virtual. Clique em 'sim' na aba que se abre.

Pronto! Conexão feita!

![](https://i.ibb.co/XrQDJT6w/Captura-de-Tela-103.png)

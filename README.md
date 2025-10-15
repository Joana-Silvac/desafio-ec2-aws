# desafio-ec2-aws
Repositório com anotações e práticas do laboratório de gerenciamento de instâncias EC2 - Bootcamp DIO

# desafio
Repositório com anotações e práticas do laboratório de gerenciamento de instâncias EC2 - Bootcamp DIO


- O que é uma instância EC2:
    Elastic Compute Cloud, são as máquinas virtuais(servidores criados dentro da aws) na AWS, podendo ser com sistema operacional Windows ou Linux.; 

- Uma EC2 é composta por:
CPU
Memória
Disco
Rede
Sistema operacional 

- Importancia de escolher a instancia correta:
    Entender as necessidades da sua aplicação e utilizar os recursos da nuvem de forma inteligente para alcançar eficiência operacional e econômica.
    --------------------------
- EC2 – Terminologia- O Amazon Elastic Compute Cloud (EC2) nos fornece a capacidade de computação na cloud da AWS.
- As imagens de máquina da Amazon estão disponíveis para escolha no momento da criação
- Pode definir a segurança básica utilizando firewall incorporada do AWS, utilizar grupo de segurança, protocolo, porta, IPs de origem que permite ou nega o acesso às suas instâncias EC2


- A infraestrutura é a aws que gerencia mas o que é colocado lá é problema do usuario.

Para adicionar uma tag-
Na caixa Add (Adicionar), digite um nome para a tag. Escolha o botão verde com o sinal de adição (+) e selecione Apply (Aplicar)

---

COMO CFRIAR UMA INSTANCIA EC2

1. Acesse o Console da AWS
Faça login na AWS Management Console.

No menu de serviços, busque EC2.

2. Inicie o Assistante de Lançamento
No painel do EC2, clique em "Lançar instância".

3. Configure os Detalhes da Instância
Nome da instância: Dê um nome identificador (ex: meu-servidor-web).

AMI (Amazon Machine Image): Escolha um sistema operacional (ex: Amazon Linux ou Ubuntu).

Tipo de instância: Selecione o hardware (ex: t3.micro para uso gratuito).

Par de chaves: Crie ou use um par de chaves existente para acesso SSH.

4. Configurar Security Group (Firewall)
Crie um novo grupo de segurança ou use um existente.

Adicione regras de entrada (ex: porta 22 para SSH, 80 para HTTP, 443 para HTTPS).

5. Configurações de Armazenamento
Defina o tamanho do volume EBS (ex: 8 GB para o Free Tier).

Escolha o tipo de volume (ex: gp3 para uso geral).

6. Revisar e Lançar
Revise as configurações.

Clique no "Lançar instância".
---

## Autora
Joana 

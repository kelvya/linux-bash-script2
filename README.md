# Infraestrutura como Código: Script de Provisionamento de um Servidor Web (Apache)

## Conteúdo

### O que é infraestrutura como código?
<p> Ingraestrutura como código (IaC) é o gerenciamento e provisionamento da infraestrutura por meio de códigos,em vez de processos manuais.</p>
<p> Com a IaC, são criados arquivos de configuração que incluem as especificações da sua infraestrutura, facilitando a edição e  distribuição de configurações. Ela também assegura o provisionamento do mesmo ambiente todas as vezes.</p>

### Controle de versão
<p>O controle de versão é uma parte importante da IaC. os arquivos de configuração devem pertencer à fonte como qualquer outro código-fonte de software. Ao implantar a infraestrutura como código, também é possível separá-la emmódulos, que podem ser combinados de diferentes maneiras por meio da automação.</p>
- Princial benefício:
<p>Ao automatizar o provisionamento da infraestrutura com a IaC, os desenvolvedores não precisam provisionar e gerenciar manualmente servidores, sistemas operacionais, armazenamento e outros componentes de infraestrutura sempre que criam ou implantam uma aplicação.</p>

### Sobre o desafio:
<p>Neste desafio de projeto foi criado um script pra provisionar um servidor web automaticamente. Um servidor web é um software e hardware que usa HTTP (Hypertext Transfer Protocol) e outros protocolos para responder a solicitações de clientes feitas pela World Wide Web. O principal trabalho de um servidor da web é exibir o conteúdo do site por meio do armazenamento, processamento e entrega de páginas da web aos usuários.</p>


### Definições:
- Atualizar o servidor;
- Instalar o apache2;
- Instalar o unzip;
- Baixar a aplicação disponível [aqui](https://github.com/denilsonbonatti/linux-site-dio/archive/refs/heads/main.zip) no diretório /tmp;
- Copiar os arquivos da aplicação no diretório padrão do apache;
- Subir arquivo de Script criado para a sua conta do Github.

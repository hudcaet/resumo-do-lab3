# resumo-do-lab3
 "Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO - Configurando uma instância de Banco de Dados na Azure".

Configurando uma Instância de Banco de Dados no Azure e Tipos de Serviço de Nuvem

No Azure, configurar uma instância de banco de dados envolve escolher o tipo de serviço de nuvem adequado, determinando o nível de controle e gerenciamento desejado. Existem três principais tipos de serviço de nuvem para bancos de dados:

Infraestrutura como Serviço (IaaS): Aqui, você cria uma máquina virtual no Azure e instala o banco de dados (ex.: SQL Server ou MySQL) manualmente. Esse modelo oferece controle total sobre o ambiente, incluindo a configuração de hardware, sistema operacional, segurança e backups. Ideal para quem precisa de um nível alto de customização e controle, mas demanda maior gerenciamento.

Plataforma como Serviço (PaaS): Neste caso, o Azure fornece uma solução de banco de dados gerenciada, como o Azure SQL Database. A configuração e o gerenciamento da infraestrutura subjacente, atualizações e backups automáticos ficam a cargo da Microsoft, permitindo que os desenvolvedores foquem mais nas aplicações e menos na infraestrutura. Esse modelo oferece escalabilidade integrada e é ideal para quem busca eficiência operacional e facilidade de gerenciamento.

Software como Serviço (SaaS): Embora menos comum para bancos de dados, alguns aplicativos SaaS incorporam bancos de dados que o usuário utiliza de forma simplificada, sem acesso à infraestrutura nem à necessidade de configurar instâncias individuais.

Processo de Configuração de um Banco de Dados no Azure

Escolha o tipo de banco de dados: Decida entre opções, como SQL Database, Cosmos DB, MySQL ou PostgreSQL, baseando-se nos requisitos do aplicativo e nas preferências de gerenciamento.

Configuração e especificação de recursos: Defina parâmetros como CPU, memória, armazenamento e configurações de backup. Para bancos de dados PaaS, você escolhe a capacidade desejada, e o sistema automaticamente dimensiona conforme necessário.

Segurança e rede: Configure firewalls, criptografia e políticas de acesso para assegurar que o banco de dados está protegido contra acesso não autorizado.

SLAs (Acordos de Nível de Serviço)

Para bancos de dados, a Azure oferece diferentes SLAs conforme o tipo de serviço selecionado:

PaaS (como o Azure SQL Database) tem um SLA de disponibilidade de 99,99%, garantindo confiabilidade para cargas de trabalho críticas.

IaaS, com uma máquina virtual personalizada, terá o SLA específico da VM utilizada, que pode variar, mas geralmente oferece até 99,9% para configurações de alta disponibilidade.
Com essa abordagem, você pode otimizar recursos e garantir desempenho e disponibilidade de acordo com os objetivos do projeto e nível de gerenciamento desejado.







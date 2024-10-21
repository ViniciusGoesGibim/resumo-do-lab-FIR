## Ferramentas de Implantação de Recusros

### Ferramentas de Gerenciamento e Implantação
#### Portal do Azure
O portal do Azure é um console unificado que permite gerenciar a assinatura do Azure e criar, gerenciar e monitorar recursos: Aplicativos Web, Implantações em nuvem, Banco de dados, Máquinas virtuais, Custos mensais. 

O portal do Azure é baseado na Web e pode ser acessado com qualquer navegador compatível. Ele é projetado para ser resiliente e estar disponível continuamente, estando presente em todos os datacenters do Azure. 

O portal do Azure oferece várias funcionalidades, incluindo: Painéis personalizados para organizar recursos, Opções de acessibilidade, Cálculo automático de encargos e previsão de encargos mensais, Visualização de dados de uso ativo em tempo real, Monitoramento e diagnóstico. 

O Azure é uma plataforma de nuvem da Microsoft que oferece mais de 200 produtos e serviços de nuvem.
#### Azure Cloud Shell
O Azure Cloud Shell é um terminal interativo baseado em navegador que permite gerenciar recursos do Azure sem a necessidade de instalar o Azure CLI ou o Azure PowerShell: 
- É executado no Azure Linux, a distribuição Linux da Microsoft 
- Permite escolher entre Bash ou PowerShell como o shell padrão 
- Permite executar comandos do Azure diretamente no navegador 
- Anexa um compartilhamento de Arquivos do Azure para persistir os dados entre sessões 
- A sessão do Cloud Shell expira após 20 minutos sem atividade interativa 
- Os arquivos são mantidos na localização $HOME usando um compartilhamento de arquivos de 5 GB
#### Azure PowerShell
O Azure PowerShell é um conjunto de cmdlets que permite gerenciar recursos do Azure diretamente da linha de comando do PowerShell. O Azure PowerShell é projetado para ser fácil de usar e aprender, mas também conta com recursos avançados de automação. 

Com o Azure PowerShell, é possível: 
- Compilar ferramentas automatizadas que usam o modelo do Azure Resource Manager 
- Gerenciar o acesso a recursos usando o RBAC do Azure (controle de acesso baseado em função do Azure) 
- Criar recursos do Azure
#### Interface de linha de comando (CLI)
A interface de linha de comando (CLI) do Azure é um conjunto de comandos que permite criar, gerenciar e automatizar recursos do Azure.

A CLI do Azure está disponível nos serviços do Azure e foi criada para ajudar a trabalhar de forma rápida com o Azure. 

A CLI é uma forma de interação com o computador através de linhas de texto. A sigla CLI significa Command-Line Interface em inglês. 

A CLI do Azure pode ser usada com PowerShell ou em bash. Com ela, é possível: Criar recursos, Criar resource groups, Executar ações no Azure. 

A CLI do Azure é uma ferramenta poderosa para gerenciar instâncias, recursos e serviços do Azure.

#### Azure ARC
Azure Arc é uma solução da Microsoft que permite a execução de serviços de dados do Azure em ambientes multinuvem, na borda e em data centers: 
- O Azure Arc permite gerenciar a nuvem Azure em qualquer infraestrutura, incluindo servidores híbridos e Kubernetes. 
- O Azure Arc permite executar serviços de dados do Azure em qualquer lugar, usando a infraestrutura e o Kubernetes de sua escolha. 
- O Azure Arc simplifica a governança e o gerenciamento ao fornecer uma plataforma de gerenciamento local e de várias nuvens. 
- O Azure Arc permite gerenciar máquinas virtuais, clusters do Kubernetes e bancos de dados como se estivessem em execução no Azure. 

O Azure Arc é uma ponte que estende a plataforma do Azure, permitindo criar aplicativos e serviços com a flexibilidade de serem executados em ambientes multinuvem, na borda e em data centers.

#### Azure Resource Manager
O Azure Resource Manager (ARM) é um serviço do Azure que permite criar, atualizar e excluir recursos, além de implantar e gerenciar soluções: 

- Implantação repetida</br>
O ARM permite implantar aplicativos de forma repetitiva, com a garantia de que os recursos serão implantados de forma consistente. 

- Controle de acesso</br>
O ARM permite aplicar controle de acesso a todos os recursos de um grupo de recursos, e essas políticas são aplicadas automaticamente a novos recursos adicionados. 

- Marcas</br>
O ARM permite aplicar marcas aos recursos para organizá-los de forma lógica. 

- Dependências</br>
O ARM permite definir dependências entre os recursos para que sejam implantados na ordem correta. 

- Modelos</br>
O ARM permite implementar a infraestrutura como código para soluções do Azure usando modelos ARM, que são arquivos JavaScript Object Notation (JSON).

#### Infraestrutura como Código
A infraestrutura como código (IaC) é uma prática de gerenciamento de infraestrutura de TI que permite definir o estado desejado da infraestrutura de forma automatizada. No Azure, a IaC é um componente de entrega contínua que permite às equipes de DevOps fornecer aplicativos e a infraestrutura de suporte de forma rápida e confiável. 

A IaC permite que as equipes desenvolvam e liberem alterações mais rapidamente e com maior confiança. Alguns dos benefícios da IaC são: Maior confiança nas implantações, Capacidade de gerenciar vários ambientes, Melhor compreensão do estado da infraestrutura. 

Existem dois tipos de IaC: a declarativa e a imperativa. A abordagem declarativa define o estado desejado do sistema, incluindo os recursos necessários, as propriedades que eles precisam ter e uma ferramenta de IaC para configurá-lo.

#### Bicep
O Bicep é uma linguagem de programação da Microsoft que permite implantar recursos do Azure de forma declarativa: 
- O Bicep usa uma sintaxe declarativa que pode ser tratada como código de aplicativo. 
- O Bicep pode ser usado em vez do JSON para desenvolver modelos do ARM (Azure Resource Manager). 
- Os arquivos Bicep são compilados em modelos do ARM padrão. 
- O Bicep oferece uma sintaxe mais concisa e segurança de tipos aprimorada em relação ao JSON. 
- O Bicep permite controlar as alterações em requisitos de infraestrutura e torna as implantações mais consistentes e reproduzíveis.

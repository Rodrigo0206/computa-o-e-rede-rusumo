# computa-o-e-rede-rusumo
resumo da aula


Assisti às aulas do Módulo 2 da AZ-900, que trataram de Arquitetura e Serviços do Azure, com foco em computação e rede. Aprendi a comparar diferentes tipos de computação no Azure, como máquinas virtuais (VMs), contêineres, funções (Functions) e a Área de Trabalho Virtual.
Vi que as máquinas virtuais oferecem controle total sobre o sistema,Já os conjuntos de dimensionamento de VMs permitem escalar recursos horizontalmente de forma automática, o que ajuda a manter a performance da aplicação de acordo com a demanda.
Quanto à rede, entendi como funciona a Rede Virtual do Azure (VNet), que conecta recursos dentro e fora da nuvem. Aprendi sobre pontos de extremidade públicos e privados, sub-redes, emparelhamento de rede, além dos serviços de conectividade como Gateway de VPN (via Internet) e ExpressRoute (via conexão privada).
No geral, foi uma introdução bem completa sobre como o Azure oferece flexibilidade para diferentes cenários de computação e conectividade, tanto para aplicações tradicionais quanto para soluções modernas e escaláveis.
Aqui segue os tópicos anotados da aula:

Módulo 2:
Arquitetura e Serviços do Azure 
AZ-900 : Introdução aos Conceitos Básicos do Microsoft Azure 
Computação e rede
	Tipos de computação
	Hospedagem de aplicativos
	Redes virtuais


Computação e Rede 
AZ-900 : Introdução aos Conceitos Básicos do Microsoft Azure 
Computação e rede : domínio de objetivo 
	Comparar tipos de computação, incluindo instâncias de contêiner, máquinas virtuais e funções.
	Descrever os recursos exigidos para as máquinas virtuais.
	Definir pontos de extremidade públicos e privados.
	Descrever as opções de máquina virtual, incluindo VMs (máquinas virtuais), conjuntos de dimensionamento de máquinas virtuais, conjuntos de disponibilidade de máquinas virtuais e a Área 
de Trabalho Virtual do Azure.
	Serviços de computação do Azure 
	A Computação do Azure é um serviço sob demanda que fornece recursos de computação, como discos, processadores, memória, rede e sistemas operacionais.
	Máquinas virtuais do Azure
•		As máquinas virtuais do Azure (VMs) são emulações de software de computadores físicos. 
•	Inclui processador virtual, memória, armazenamento e rede. 
•	Oferta de IaaS que oferece personalização e 
     controle total. 
Conjuntos de dimensionamento de VMs 
Os conjuntos de dimensionamento oferecem uma oportunidade de balanceamento de carga para dimensionar os recursos automaticamente. 
•	Escalar horizontalmente quando o recurso precisar aumentar.
•	Reduzir horizontalmente quando o recurso precisar diminuir.
•	Área de Trabalho Virtual do Azure 
•	A Área de Trabalho Virtual do Azure é uma virtualização de área de trabalho e aplicativo executada na nuvem.
•		Crie um ambiente completo de virtualização da área de trabalho sem precisar executar outros servidores de gateway. 
•	Reduza o risco de que o recurso seja deixado para trás.
•	Implantações reais de várias sessões.
•	Serviços de contêineres do Azure 
	Os contêineres do Azure fornecem um ambiente leve e virtualizado que não exige o gerenciamento do sistema operacional e pode responder a alterações sob demanda. 
Instâncias de Contêiner do Azure: uma oferta de PaaS que executa um contêiner ou pod de contêineres no Azure.
Aplicativos de Contêiner do Azure: uma oferta de PaaS, como instâncias de contêineres, que pode balancear a carga e escalar.
Serviço de Kubernetes do Azure: um serviço de orquestração para contêineres com arquiteturas distribuídas e grandes volumes de contêineres. 
Azure Functions
Azure Functions: uma oferta de PaaS que dá suporte a operações de computação sem servidor. 
O código baseado em eventos é executado quando chamado, sem exigir uma infraestrutura de servidor durante períodos inativos.
Comparar opções de computação do Azure
Máquinas virtuais 
•	Servidor baseado em nuvem que dá suporte a ambientes Windows ou Linux.
•	Útil para migrações de lift-and-shift para a nuvem.
•	Pacote do sistema operacional completo, incluindo 
      o sistema operacional do host.
Área de Trabalho Virtual
•	Fornece uma experiência de área de trabalho do Windows baseada em nuvem.
•	Aplicativos dedicados para conexão e uso ou acessíveis de qualquer navegador moderno.
•	Área de Trabalho Virtual
•	O logon de vários clientes permite que vários usuários façam logon no mesmo computador na 
ao mesmo tempo.
Contêineres
•	Ambiente leve e em miniatura adequado para a execução de microsserviços.
•	Projetado para escalabilidade 
e resiliência por meio da orquestração.
•	Os aplicativos e serviços são empacotados em um contêiner que fica na parte superior do sistema operacional do host. Vários contêineres podem ficar em um sistema operacional do host.
•	Serviços de Aplicativo do Azure 
•	Os Serviços de Aplicativos do Azure consistem em uma plataforma totalmente gerenciada para criar, implantar e dimensionar aplicativos Web e APIs rapidamente. 
•	Trabalha com .NET, .NET Core, Node.js, Java, Python ou PHP.
•	Oferta de PaaS com requisitos de nível corporativo de desempenho, segurança e conformidade. 
•	A Rede Virtual do Azure (VNet) permite que os recursos do Azure se comuniquem uns com os outros, com a Internet e com as redes locais.
•	Pontos de extremidade públicos, acessíveis de qualquer lugar na Internet.
•	Pontos de extremidade privados, acessíveis somente 
•	de dentro da sua rede.
•	As sub-redes virtuais segmentam sua rede para atender às suas necessidades.
•	O emparelhamento de rede conecta suas redes privadas diretamente.

•	Serviços de rede do Azure: Gateway de VPN 
•	O Gateway de VPN é usado para enviar tráfego criptografado entre uma rede virtual do Azure e uma 
no local pela Internet pública. 
•	Serviços de rede do Azure: ExpressRoute 
•	O ExpressRoute estende as redes locais para o Azure por meio de uma conexão privada facilitada por um provedor de conectividade. 
•	DNS do Azure
•	Confiabilidade e desempenho aproveitando uma rede global de servidores de nome DNS usando a rede Anycast.
•	A segurança do DNS do Azure baseia-se no gerenciador de recursos do Azure, habilitando o controle 
      de acesso baseado em função e o monitoramento 
      e o registro em log.
•	Facilidade de uso para gerenciar seus recursos externos e do Azure com um único serviço DNS.
•	As redes virtuais personalizáveis permitem que você use nomes de domínio privados 
e totalmente personalizados em suas redes virtuais privadas.
•	Os registros de alias dão suporte a conjuntos de registros de alias para apontar diretamente para um recurso do Azure.


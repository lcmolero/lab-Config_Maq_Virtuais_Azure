# lab-Config_Maq_Virtuais_Azure
Laboratório Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure


## Principais pontos aprendidos no laboratório para configurar recursos e dimensionamentos em máquinas virtuais (VMs) no Microsoft Azure:


### Passos para Criar uma VM no Portal do Azure:
	Iniciar Sessão no Azure: Acesse o portal do Azure e faça login;
	
	Criar a Máquina Virtual: No portal, pesquise por “Máquinas Virtuais” e selecione “Criar”. Escolha a imagem do sistema operacional;
	
	Configurar Detalhes da Instância: Insira o nome da VM, selecione a imagem do sistema operacional e configure as credenciais de administrador;
	
	Configurar Regras de Porta de Entrada: Permita portas como RDP (3389) e HTTP (80) para acesso remoto e web;
	
	Revisar e Criar: Revise as configurações e clique em “Criar” para iniciar a implantação.

    
### Escolha do Tipo de Máquina Virtual:
	  Série A: Para cargas de trabalho de entrada de baixo custo;
	  
	  Série D, E: Balanceadas para aplicações de negócios e bancos de dados;
	  
	  Série F: Alta performance focada em CPU;
	  
	  Série G: Alta memória e desempenho em armazenamento;
	  
	  Série N: Com GPU para processamento gráfico e machine learning.
  

#### Dimensionamento de Recursos:
	CPU e Memória: Número de vCPUs e a quantidade de RAM conforme a carga de trabalho.
	
	Armazenamento: Discos HDD para desempenho padrão ou SSD Premium para alta performance.
	
	Rede: Interfaces de rede, balanceamento de carga e segurança.


### Dimensionamento Vertical e Horizontal:
	Vertical (Scaling Up/Down): Ajuste dos recursos da VM (CPU/RAM) dentro da mesma instância.
	
	Horizontal (Scaling Out/In): Adição ou remoção de instâncias de VMs para balanceamento de carga e alta disponibilidade.


### Configurações Avançadas:
	Zonas de Disponibilidade: Para alta disponibilidade e recuperação de desastres.
	
	Grupos de Dimensionamento: Gerenciamento escalável e automatizado de múltiplas VMs.
	
	Extensões e Scripts: Adição de softwares ou scripts de configuração adicionais.


### Automação e Monitoramento:
	Auto Scaling: Regras de auto-escalabilidade para ajustar automaticamente o número de VMs baseado em métricas.
	
	Azure Monitor: Monitoramento de desempenho e ajuste proativo dos recursos.


### Configuração via Portal Azure, CLI ou ARM Templates:
	Portal Azure: Interface gráfica para configuração manual.
	
	CLI e ARM Templates: Para automação e scripts de configuração.


### Conectar à Máquina Virtual:
	RDP: Use o Remote Desktop Protocol (RDP) para se conectar à VM a partir de um computador Windows ou Mac.

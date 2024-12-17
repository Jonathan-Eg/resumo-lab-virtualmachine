## Azure Virtual Machines

**Azure Virtual Machines (VMs)** são um dos principais serviços de infraestrutura como serviço (IaaS) da Microsoft Azure. Elas permitem que você execute sistemas operacionais completos e aplicativos diretamente na nuvem, proporcionando flexibilidade, escalabilidade e controle sobre a infraestrutura de TI.

### Principais Características:
- **Escalabilidade**: Azure permite o dimensionamento de VMs de acordo com a necessidade, seja para aumento ou diminuição de recursos como CPU, memória e armazenamento.
- **Suporte a Diversos Sistemas Operacionais**: Azure oferece suporte tanto para sistemas operacionais Windows quanto Linux, permitindo que você escolha a plataforma que melhor atenda às suas necessidades.
- **Gestão de Recursos**: É possível configurar, monitorar e gerenciar as VMs através do portal Azure, CLI ou APIs, permitindo automação e controle detalhado.
- **Segurança e Backup**: Azure oferece integração com Azure Security Center para monitoramento de segurança, e com Azure Backup para proteção de dados e recuperação em caso de falha.
- **Alta Disponibilidade**: Com recursos como Azure Availability Sets e Azure Availability Zones, é possível garantir alta disponibilidade e resiliência das suas VMs.

### Casos de Uso Comuns:
- **Ambientes de Desenvolvimento e Teste**: Criação de ambientes temporários para desenvolvimento, testes e QA.
- **Aplicativos Empresariais**: Hospedagem de aplicativos empresariais e sistemas legados na nuvem.
- **Análise de Dados e Big Data**: VMs podem ser usadas para rodar clusters de processamento de dados.
- **Soluções de Backup e Recuperação de Desastres**: VMs podem ser configuradas para garantir recuperação rápida em caso de falhas de sistema ou perda de dados.

### Tipos de Máquinas Virtuais:
- **VMs Gerais**: Máquinas equilibradas em termos de CPU, memória e armazenamento (ex: série B e D).
- **VMs de Alta Performance**: VMs otimizadas para tarefas que exigem alto desempenho de CPU (ex: série F e H).
- **VMs de Memória Otimizada**: VMs com grande quantidade de RAM para cargas de trabalho que exigem memória intensiva (ex: série E e M).
- **VMs de Armazenamento Otimizado**: VMs com foco em alta performance de armazenamento para cenários que exigem grandes volumes de dados (ex: série L).

### Como Usar:
1. Crie uma VM a partir do portal Azure ou via linha de comando (Azure CLI).
2. Escolha o tamanho da VM conforme os requisitos da sua aplicação.
3. Selecione o sistema operacional e faça as configurações necessárias.
4. A VM será provisionada e você poderá acessá-la via RDP (para Windows) ou SSH (para Linux).


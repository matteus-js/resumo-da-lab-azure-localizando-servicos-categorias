# Microsoft Azure - Localizando Serviços por Categoria

**Resumo: 5 Categorias e Serviços da Plataforma Azure**

**1. Computação**
- **Máquinas Virtuais (VMs)**: Permite criar e gerenciar servidores virtuais com sistemas operacionais personalizáveis (Windows/Linux). Ideal para hospedar aplicativos ou testar ambientes.
- **Azure Kubernetes Service (AKS)**: Facilita o gerenciamento de contêineres em escala, automatizando deploy, escalabilidade e orquestração de apps com Kubernetes.
- *Nota*: Explorado na prática, VMs são flexíveis, mas AKS é mais eficiente para microsserviços.

**2. Armazenamento**
- **Azure Blob Storage**: Armazenamento de objetos para grandes quantidades de dados não estruturados (imagens, vídeos, backups). Suporta escalabilidade e acesso rápido.
- **Azure Files**: Sistema de arquivos compartilhado para aplicativos, compatível com SMB, útil para substituir servidores de arquivos locais.
- *Nota*: Blob é ótimo para dados brutos; Files é mais para integração com sistemas legados.

**3. Bancos de Dados**
- **Azure SQL Database**: Banco de dados relacional gerenciado, baseado no SQL Server, com alta disponibilidade e escalabilidade automática.
- **Cosmos DB**: Banco NoSQL para dados globais, com baixa latência e suporte a múltiplos modelos (documentos, grafos, chave-valor).
- *Nota*: Cosmos DB impressiona pela distribuição global, mas Azure SQL é mais familiar para quem usa SQL tradicional.

**4. Inteligência Artificial e Machine Learning**
- **Azure Machine Learning**: Plataforma para criar, treinar e implantar modelos de ML, com suporte a ferramentas como Python e AutoML.
- **Cognitive Services**: APIs prontas para visão, fala, texto e tradução, como reconhecimento facial ou análise de sentimentos.
- *Nota*: Cognitive Services é prático para prototipagem rápida; ML exige mais conhecimento técnico.

**5. Rede**
- **Azure Virtual Network (VNet)**: Cria redes privadas na nuvem, isolando recursos e conectando-os a redes locais via VPN ou ExpressRoute.
- **Azure Load Balancer**: Distribui tráfego entre servidores para garantir alta disponibilidade e desempenho de aplicativos.
- *Nota*: VNet é essencial para segurança; Load Balancer é chave para apps com muitos acessos.

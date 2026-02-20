# Atividade 2: Especificações Técnicas, Cotações e Análise de Integração

## Identificação de Dispositivos, Fornecedores e Prazos

| Equipamento | Especificações Técnicas Principais | Fornecedor (Pesquisa) | Valor Est. (R$) | Prazo de Entrega |
| :--- | :--- | :--- | :--- | :--- |
| **CLP (Controlador Lógico)** | Alimentação 24V DC, suporte a módulos de expansão, porta PROFINET/Ethernet, montagem Trilho DIN. (Ex: Linha S7-1200 ou similar) | Dimensional / Reymaster | 6.500,00 | 15 a 20 dias úteis |
| **IHM (Interface)** | Tela Touch 10", Proteção IP65 (frontal), portas Ethernet industriais, alta durabilidade. | Ladder Automação | 3.800,00 | Pronta entrega |
| **Switch Industrial** | 8 Portas RJ45 10/100 Mbps, Gerenciável, IP30, Temp. Operação -40 a 75°C, redundância de anel. | Nortel Suprimentos | 2.800,00 | 10 a 15 dias úteis |
| **Cabeamento de Rede** | Cabo STP (Blindado) Cat6 Industrial, capa resistente a intempéries e antichama. Bobina 305m. | Rede de Distribuidores Furukawa | 1.500,00 | Pronta entrega |
| **Módulo I/O Remoto** | Módulo descentralizado para coleta de dados de sensores, comunicação via rede industrial. | Dimensional | 1.800,00 | 20 dias úteis |

## Análise Técnica e Arquitetural

* **Adequação ao Ambiente Industrial:** A fábrica de tijolos ecológicos gera poeira e vibração. Os equipamentos listados foram selecionados por sua robustez: suportam amplas faixas de temperatura, possuem graus de proteção adequados (como IP65 para a frente das IHMs) e utilizam cabeamento blindado (STP) para evitar interferências eletromagnéticas dos motores e prensas.
* **Escalabilidade da Solução:** A arquitetura baseada em Ethernet Industrial permite crescimento orgânico. Se a fábrica adicionar uma nova linha de prensas no futuro, basta conectar novos módulos de I/O remotos e CLPs aos switches existentes, sem precisar refazer a infraestrutura central.
* **Compatibilidade com Integrações Corporativas:** Os CLPs e switches especificados operam com protocolos abertos e padronizados (como PROFINET, Modbus TCP ou Ethernet/IP) e possuem suporte a **OPC UA**. Isso garante a comunicação fluida entre a camada de operação (OT) e a camada de gestão (TI), permitindo integração futura com sistemas MES (Manufacturing Execution System) e ERP corporativo para leitura de indicadores de produção em tempo real.

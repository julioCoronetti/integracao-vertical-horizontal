# Planejamento Estratégico: Integração Industrial e TI

## 1. Estudo de Caso: Klabin (Papel e Celulose)

### Integração Vertical (Chão de Fábrica $\leftrightarrow$ Gestão)
* **Desafio:** Conectar a operação florestal e as máquinas de papel (OT) com o nível estratégico (IT).
* **Proposta de TI:** Implementação de sistemas **MES (Manufacturing Execution Systems)** integrados ao ERP (SAP).
    * *Ação:* Dados de telemetria das máquinas de colheita florestal e sensores de vibração nas máquinas de papel são enviados em tempo real para o ERP.
    * *Resultado:* O CEO acessa dashboards que mostram o custo exato da tonelada produzida no momento, permitindo ajustes financeiros imediatos.

### Integração Horizontal (Processos e Cadeia)
* **Desafio:** Sincronizar as unidades industriais (ex: Projeto Puma) com a logística ferroviária e portuária.
* **Proposta de TI:** Uso de **Digital Twins (Gêmeos Digitais)** e **IoT**.
    * *Ação:* Criar uma réplica digital da cadeia logística. Sensores nos vagões de trem e nos estoques do porto comunicam-se com o PCP (Planejamento e Controle da Produção).
    * *Resultado:* Se houver atraso no porto, a fábrica reduz automaticamente a velocidade da máquina para evitar superlotar o estoque intermediário.

---

## 2. Estudo de Caso: Marfrig (Alimentos/Proteína)

### Integração Vertical (Chão de Fábrica $\leftrightarrow$ Gestão)
* **Desafio:** Garantir o controle de qualidade sanitária e rendimento de carcaça em tempo real.
* **Proposta de TI:** Automação com **Edge Computing** e **Visão Computacional**.
    * *Ação:* Câmeras inteligentes na linha de desossa avaliam o volume de gordura e carne, enviando dados para o sistema de gestão de custos sem input manual.
    * *Resultado:* A diretoria identifica perda de rendimento em minutos, não no fechamento do mês.

### Integração Horizontal (Fornecedores $\leftrightarrow$ Clientes)
* **Desafio:** Rastreabilidade completa desde o pasto até a gôndola do supermercado (Cadeia de Frio).
* **Proposta de TI:** Uso de **Blockchain** e **RFID**.
    * *Ação:* O brinco do gado (RFID) registra dados no Blockchain. A integração horizontal conecta o sistema do pecuarista, o frigorífico e o centro de distribuição do varejista.
    * *Resultado:* Transparência total para o consumidor final (via QR Code) e garantia de que a carne não vem de áreas de desmatamento, integrando sustentabilidade à operação.

---

## 3. Resumo das Tecnologias Habilitadoras (Propostas)

| Tecnologia | Aplicação na Integração Industrial |
| :--- | :--- |
| **Cloud Computing** | Centralizar dados de diferentes unidades (Klabin e Marfrig possuem plantas globais) para acesso único. |
| **Big Data/Analytics** | Previsão de demanda para ajustar a compra de insumos (gado ou madeira) antes que o pedido do cliente chegue. |
| **API Management** | Permitir que os sistemas legados do chão de fábrica "conversem" com os novos softwares de gestão corporativa. |

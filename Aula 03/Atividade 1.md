# Atividade 1: Plano Orçamentário e Levantamento Técnico

## Levantamento Técnico da Infraestrutura
A arquitetura foi dividida em três níveis principais para garantir organização e confiabilidade:

* **Nível de Controle e Supervisão:** Concentra a inteligência da planta. Inclui Controladores Lógicos Programáveis (CLPs) para comandar as máquinas, Interfaces Homem-Máquina (IHMs) para operação local e um Servidor SCADA para visão global do processo.
* **Nível de Comunicação:** O backbone do sistema. Utilizará Switches Industriais Gerenciáveis (montagem em trilho DIN e proteção contra poeira) formando uma topologia em anel para garantir redundância (se um cabo falhar, a rede continua operando), utilizando cabeamento blindado contra interferências eletromagnéticas.
* **Infraestrutura de Campo:** Módulos de I/O remotos para coletar dados dos sensores (ex: pressão da prensa, umidade da mistura) de forma descentralizada, além de painéis elétricos com grau de proteção adequado (IP54 ou superior) e sistemas de energia ininterrupta (UPS/No-Break).

## Plano Orçamentário Estimado

| Categoria | Descrição do Equipamento / Material | Qtd. | Valor Unit. (R$) | Valor Total (R$) |
| :--- | :--- | :--- | :--- | :--- |
| **Controle** | CLP Modular com CPU e cartões de I/O integrados | 2 | 6.500,00 | 13.000,00 |
| **Controle** | IHM Touch Screen 10" Industrial | 2 | 3.800,00 | 7.600,00 |
| **Supervisão**| PC Industrial / Servidor para Sistema SCADA | 1 | 9.500,00 | 9.500,00 |
| **Rede** | Switch Industrial Gerenciável (8 portas RJ45) | 3 | 2.800,00 | 8.400,00 |
| **Rede** | Bobina Cabo Rede Industrial Blindado (STP Cat6) | 1 | 1.500,00 | 1.500,00 |
| **Campo** | Módulo de I/O Remoto (Ethernet/IP ou PROFINET) | 3 | 1.800,00 | 5.400,00 |
| **Infra.** | Quadro de Comando (Painel IP54) montado | 2 | 4.000,00 | 8.000,00 |
| **Infra.** | Fonte de Alimentação 24Vdc e UPS Industrial | 2 | 2.500,00 | 5.000,00 |
| **Diversos** | Eletrocalhas, conectores, conduítes e fixação | 1 | 3.500,00 | 3.500,00 |
| | **CUSTO TOTAL ESTIMADO (MATERIAIS)** | | | **61.900,00** |

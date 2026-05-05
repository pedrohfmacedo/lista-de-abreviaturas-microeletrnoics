## Abbreviations in Microeletronics

Lista de abreviaturas utilizados no meio da microeletrônica;

**Índice**

1. [Fundamentos Semicondutores](#idCMOS)  
2. [VDSI](#idVDSI)  
3. [VDSM](#idVDSM)  
4. [Digital_Design](#idDD)  
5. [ASICs](#idASIC)  

***

### Em Fundamentos de semicondutores (MOSFET) <a name = "idCMOS"></a>
| Sigla/Termo | Nome completo | Descrição |
|------|--------------|----------|
|_Band Gap_|  | Diferença de energia entre a banda de valência e o banda de condução, que define a quantidade minima de energia necessária para liberar um elétron (eV) |
|_Band Theory_|  | Um modelo usado para explicar a condição de sólidos e o comportamento dos elétrons  |
|_Polycrystalline_|  | Estrutura atômica do sílicio onde os cristais de sílicios são fundidos  |
|_Layer_|  | São os níveis de materiais diferentes empilhados no chip, onde cada camada tem uma função específica na construção dos dispositivos e das interconexões. |
|_Mask_|  | São as máscaras usados no processo de  litografia na dopagem dos semicondutores, que contém padrões a serem transferidos para o waffer ou outra máscara. |
|_Silicon Wafer_|  | Uma fatia do lingote usado como base para fabricação dos CI. |
|_ICs_| Integred Circuits | Circuitos integrados |
|_Ingot_|  | São os lingotes de silícios cilíndricos puro, matéria prima para os semicondutores|
|_Die_|  | É area útil usado pelo chip no Wafer |
|_Scribe line_|  | São os espaços não funcionais entre os dies, por onde passa as serras. |
|_TEG_| Test Element Group | Um padrão que revela as características físicas reais de um chip (C,L,R,Transistores...) para serem testados |
|_Edge Dies_|  | São os dies das bordas do waffer, que podem ser descartados por falha esperado no processo de fabricação |
|_Flat Zone_|  | Borda do wafer que é cortada para identificar o wafer |
|_Foundry_|  | Fábricas que produzem chips para terceiros, para os terceiros. Compram e integram equipamentos de diversos fabricantes, mas não projetam. Responsável pelos processos. Exemplo: Samsung, TSMC. |
|_Fabs_| Fabrication Plants | Fábrica que produzem chips para si, projetam, fabricam e vendem. Fabricantes de IDMs. Exemplo: Intel  |
|_Fabless_| Fabless Chip Compaines| Empresas que criam seus projetos (também podem usar IPs) usando EDA e fabricam seus projetos em foundries, podendo vende-los ou ser de uso exclusivos. Exemplo: Apple, QUalcomm, AMD, Nvidia |
|_IDMs_| Integrated Device Manufacturers | Eles mesmos projetam, fabricam e vendem seus chips. Exemplo: Micron, Intel, Analog Devices |
|_WFE_| Wafer Fab Equipment | Máquinas que fabricam chips. Exemplos: Applied Materials, KLA, LAM, Tokyo Electron e ASML |
|_OSAT_| Outsourced Semiconductor Assembly and Test | Fábricas que encapsulam e testam os chips das foundries |
|_Layout_|  | É a planta do CI. |
|_Reticles_|  | Ferramenta que contém uam imagem de padrão que precisa ser repetida em etapas para expor todo o wafer ou mask |
|_Mask Layer_|  | São as camadas das máscaras, geralmente representado por diferentes cores. Exemplo: Metal, poly, n+diff, Contact.. etc |
|_Mask Data_|  | É o arquivo final que descrevem todas as máscaras do chip, geralmente em formato OASIS ou GDSII |
|_DRC_| Design Rules Check | São as regras de fabricação da tecnologia utilizada no qual o Layout deve obedecer. |
|_PUN_| Pull-Up | "Puxar para cima". São PMOS conectados em paralelo ligado ao VDD, localizado na parte superior para evitar curto circuito na conexão CMOS.  |
|_PDN_| Pull-Down | "Puxar para baixo". São NMOS conectados em série ligado ao GROUND, localizado na parte inferior para evitar curto circuito na conexão CMOS. |
|_MOSFETs_| Metal-Oxide-Semiconductor Field-Effect Transistor | Transistor usado para chaveamento e amplificação em circuitos integrados |
|_CMOS_| Complementary Metal-Oxide-Semiconductor | Tecnologia que usa NMOS e PMOS para baixo consumo de energia |
|_PMOS_| P-channel Metal-Oxide-Semiconductor | Transistor que conduz quando a tensão no gate é baixa |
|_NMOS_| N-channel Metal-Oxide-Semiconductor | Transistor que conduz quando a tensão no gate é alta |
|_SPICE MODEL_|  | Representação matemáttica de um comportamennto elétrico de um dispositivo. |
|_FinFET_| Fin Field-Effect Transistor | Transistor 3D com canal em forma de “fin”, oferecendo melhor controle eletrostático e menor leakage |
|_FDSOI_| Fully Depleted Silicon-On-Insulator | Tecnologia de transistores com canal totalmente depletado sobre isolante, reduzindo leakage e melhorando controle eletrostático |
|_VDD_| Voltage Drain Drain | Sinal "high-voltage", ligado a fonte. |
|_VSS_| Voltage Source Source | Sinal "low-voltage", ligado ao ground. |
|_VTC_| Voltage Transfer Characteristics | Curva que mostra a relação entre tensão de entrada e saída de um circuito (ex: inversor CMOS) |
|_Tphl_| Propagation Delay Time High-to-Low | Tempo para a saída cair de 1→0 após a mudança na entrada |
|_Tplh_| Propagation Delay Time Low-to-High | Tempo para a saída subir de 0→1 após a mudança na entrada |
|_TG_| Transmission Gate | Chave bidirecional formada por NMOS e PMOS em paralelo, usada para passar sinais sem degradação |
|_Fan-in_|  | São os números de entradas de uma porta, que afeta a resistência. Menor fan-in, menor o delay |
|_Fan-out_|  | São os números de saídas de uma porta, que afeta a capacitância. Maior fan-out, maior a carga e delay. |
|_Metastable_|  | Dado passível de metaestabilidade, pode ter um valor incerto, podendo ser o dado anterior ou atual. |
|_NORA_| NO-RAce Logic | Técnica de lógica dinâmica que evita condições de corrida entre estágios |
|_OTP_| One-time programmable | Memória programável apenas uma vez, usada para configuração permanente |
|_SRAM_| Static Random Access Memory | Memória rápida baseada em flip-flops, não precisa de refresh |
|_DRAM_| Dynamic Random Access Memory | Memória densa que armazena dados em capacitores e precisa de refresh |
|_RAM_| Random Access Memory | Memória volátil de acesso rápido para leitura e escrita |
|_ROM_| Read-Only Memory | Memória não volátil usada para armazenar dados fixos |
|_PROM_| Programmable read-only memory | Tipo de ROM que pode ser programada uma única vez pelo usuário |
|_DFM_| Design of Manufacturability | Regras e diretrizers para serem cumpridas na etapa de fabricação. |
|_CAD_| Computer-Aided Design | Software para projetar, desenhar e verificar sistemas para projeto de circuitos integrados (ICs). |
|_PDK_| Process Design Kit | Tecnologia fornecida pela foundry que consiste em um conjunto de arquivos caracterizados por ela |

***

### Em VLSI <a name = "idVLSI"></a>
| Sigla | Nome completo | Descrição |
|------|--------------|----------|
|_VLSI_| Very Large-Scale Integration | É toda a sequência de etapas para transformar um descrição de RTL até sua fabricação. |
|_EDA_| Electronic Design Automation | São os conjuntos de ferramentas/software utilizados ao longo de todo fluxo de desenvolvimento da elaboração do CI |
|_SDC_| Synopsis Design Constraints |  |
|_GTECH_| Generic Technology | Biblioteca padrão de celúlas genéricas da EDA utilizadas na etapa intermediária da síntese |
|_NLDM_| Non-Linear Delay Model | Modelo mais antigo da .ln (less acurate), modelo não linear. |
|_CCS_| Composite Current Source | Modelo mais antigo da .ln (more acurate) |
|_NLPM_| Natural language programming linter  |  |
|_LVF_| Liberty variation format  |  |
|_STA_| Static timing Analysis | Técnica para verificar o timing do circuito digital (fechou ou não?), rápido e exaustivo |
|_DTA_| Dynamic timing Analysis | Técnica para analisar timing do cricuito utilizando vetores de testes, testes específicos, mais lento. |
|_HDL_| Hardware Description Language |  |
|_TLF_| Timing Library Format |  |
|_LEF_| Library Exchange Format  |  |
|_DSCL_| Digital Standard Cell Library |  |
|_GDSII_| Graphic Design System II | É o formato padrão de arquivo usado para representar o layout físico (Atual)|
|_GDSI_| Graphic Design System I | É o formato padrão de arquivo usado para representar o layout físico (Antigo/obsoleto) |
|_DEF_| Design Exchange Format |  |
|_ASCII_| American Standard Code for Information Interchange  |  |
|_LIB_| Liberty Timing File |  |
|_STANDART CELL_|  | São as células padrão caracterizadas pertencentes ao PDK |
|_CELL_|  | Quaisquer tipo de "componente" ou unidade de um projeto CI, podendo ser um mux, transitor, etc |
|_BUS_|  |  |
|_PINS_|  | Pontos de conexões do circuito, seja entrada ou saída. |
|_GRID_|  |  |
|_FRAM_| "Frame" | Similar ao LEF, descreve também o formato físcico das células |
|_LVS_| Layout Versus Schematics |  |
|_ESD_| Electrostatic Discharge | É aquela descarga de eletricidade estática (tipo quando você leva um choque ao tocar algo), que pode danificar o chip, e pinos |
|_CORE_|  | Fornece a funcionalidade básica de um circuito integrado, o coração do CI |
|_HBM_| Human Body Model |  |
|_RTL_| Register Transfer Level | É um nível de abstração da representação de projetos digitais utilizando HDL na etapa de Design |
|_SKEW_|  | É a velocidade de transicação do dado, a diferença entre entre o tempo que o sinal sai e chega |
| HTML | HyperText Markup Language |
|_DUTY CYCLE_|  |  |
|_CTS_| Clock Tree Synthesis |  |
|_PPA_| Power, Performance, and Area |  |
|_OASIS_| Open Artwork system intechange standard |  |
|_UPF_| Unified Power Format | Literalmente, um formato/padrão para descrever como a energia pode-se organizar dentro de um CI |
|_IPs_| ntellectual Propert |  |
|_Floorplan_|  |  |
|_Placement_|  |  |
|_Site_|  |  |
|_FPGA_| Field-Programmable Gate Array |  |
|_PlD_| Programmable Logic Device |  |
|_MPGA_| Mask Programmable Gate Arrays |  |
|_CPLD_| Complex Programmable Logic Device |  |
|_SPLD_| Simple Programmable Logic Device |  |
|_Budget_|  | Uma restrição de projeto, onde definimos o nosso caminho de desenvolvimento, seja ele timing, power ou area |

***

### Em VDSM <a name = "idVDSM"></a>
| Sigla | Nome completo | Descrição |
|------|--------------|----------|
|_VDSM_| Very deep submicron | Uma categoria do VLSI |
|_SoCs_| System on a Chip/ System-on-Chip |  |
|_TDD_| Time Driven Design |  |
|_BBD_| Blocked based Design |  |
|_PBD_| Platform based Design |  
|_DVT_| Design Validation Test |  |
|_DSM_| Deep submicron | Refere-se a tecnologias de fabricação com dimensões bem menores que 1 micrômetro |
|_Timing Path_|  | É um caminho de ponto a ponto |
|_Clock group_|  | Grupo de caminhos diferentes do/de sinal/sinais de clock |
|_Slack_|  | Diferença entre o tempo necessário e o tempo de checagem (quando negativo = deu ruim) |
|_Net timing arcs_|  |  |
|_Net delay_|  |  |
|_Cell Delay_|  |  |
|_Transparente latch_|  |  |
|_flip-flop_|  |  |
|_Pusle width_|  |  |
|_tsu_| Setup time | Intervalo de tempo antes da borda de clock no qual o dado deve-se manter estável para não ocorrer metaestabilidade | 
|_thd_| Hold time | Intervalo de tempo depois da borda de clock no qual o dado deve-se manter estável para não ocorrer metaestabilidade |
|_Signal slew_|  | Tempo necessário para ocorrer uma transação |
|_Pulse Width_|  | Tempo entre o estado atibvo e inativo do clock |
|_Clock latency_|  | Diferença entre a skew e slew |
|_HVT_| High Threshold Voltage |  |
|_RVT_| Regular Threshold Voltage |  |
|_Clock slew_|  | É a diferença de tempo na chegada do clock em diferentes partes de um circuito digital. |
|_Clock jitter_|  | É a variação do skew no tmepo. Ele varia o Skew |
|_Recovery time_|  | Tempo mínimo em que o reset deve estar desativado antes da borda do clock. (Assíncrono) |
|_Removal time_|  | Tempo mínimo que o sinal assíncrono, geralmente o reset, deve continuar ativo após a borda do clock |
|_Data path_|  |  |
|_Clock path_|  |  |
|_Clock gating path_|  |  |
|_Asynchronus path_|  |  |
|_Critical path_|  | O caminho mais lento do circuito, usado para determinar a frequência máxima do circuito. |
|_False path_|  |  |
|_Single cycle path_|  |  |
|_Multi Cycle path_|  |  |
|_Launch path_|  |  |
|_Capture path_|  |  |
|_Shortest path_|  |  |
|_Capactive Crosstalk_|  | Interferência entre dois sinais próximos, causada pela capacitância parasita entre trilhas/fios no circuito. |
|_Resistive Parasitcs_|  | Resistência parasita relacionado na distribuição da fonte de alimentação. |
|_IR Drop_|  |  |
|_I/O_| Input/Output |  |
|_IR noise_|  |  |
|_GAL_| Global Asynchronous logic |  |
|_DET_| Double edge triggered |  |
|_By pass_|  |  |
|_CDC_| Clock Domain Crossover | Cruzamento do domínio de clock, é a transferência do sinall de clock em diferentes partes do circuito. |
|_Metastability_|  | É a instabilidade do sinal em circuitos sequenciais quando o dado muda muito próximo da borda do clock |
|_PVT_| Process Voltage Temperature | Representa as variações físicas e operacionais que afetam o comportamento de um circuito integrado, caracterizado no PDK. Process (Fast/Slow), Voltage (VDD High/ VDDlow), Temperature (High, Slow) |
|_Corners_| Process Voltage Temperature | Corners são combinações específicas de PVT (Process, Voltage, Temperature) usadas para analisar o comportamento de um circuito nas condições extremas (pior e melhor caso). |
|_OCV_| On-chip Variation |  |
|_Electromigration_|  |  |
|_MTTF_| Mean time to failure |  |
|_Vold_|  |  |
|_Hillock_|  |  |
|_NDR_| Nondefault rules |  |
|_BJT_| Bipolar Junction |  |
|_PNPN_| Junction PNPN |  |
|_SOI_| Silicon on insulator |  |
|_FEOL_| Front-end line |  |
|_BEOL_| Back-end of line |  |
|_antenna effect_|  | é um problema de fabricação em circuitos integrados onde cargas elétricas acumuladas durante o processo (plasma) se acumulam em interconexões metálicas e podem danificar o óxido de gate dos transistores. |
|_CMP_| Chemical mechanical planarization |  |
|_Qor_| Quality of results |  |
|_Qos_| Quality of Silicon |  |
|_Tie-high_|  |  |
|_Tie-low_|  |  |
|_Tie-Cell_|  | Células padrão usadas para constantes lógicas (1/VDD ou 0/GROUND) |

***

### Fundamentos de Designs Digitais <a name = "idDD"></a>
| Sigla | Nome | Descrição |
|-------|------|-----------|
|_BCD_| Binary-Coded Decimal |  |
|_MSB_| Most Significant Bit |  |
|_LSB_| Least Significant Bit |  |
|_Gray_|  |  |
|_Karnaugh maps_|  |  |
|_SOM_| Product of maxterms |  |
|_POM_| Sum of minterms |  |
|_Minterm_|  | Produto que inclui todas as variáveis de entradas |
|_Maxterm_|  | Soma de todas as variáveis de entradas |
|_SOP_| Sum of Products | Uma função escrita como uma OR de várias Ands |
|_POS_| Product of Sum | Uma função escrita como uma ANDs de várias ORs |
|_Cut Edge_|  |  |
|_BDD_| Binary Decision Diagram |  |
|_OBDD_| Ordered Binary Decision Diagram |  |
|_DAG_| Directed acyclic graph |  |
|_ROBDD_| Reduced Ordered Binary Decision Diagram |  |
|_Quinte-McCluskey Approach_|  |  |
|_lE_| Logical Effort |  |
|_Block Diagram_|  |  |
|_stage_|  |  |
|_storage_|  |  |
|_sequential logic circuits_|  |  |
|_combinational logic circuits_|  |  |
|_edge_|  |  |
|_edge triggerd_|  |  |
|_mealy MODEL_|  |  |
|_moore MODEL_|  |  |
|_FSM_| Finite State Machine |  |
|_minimum clock_|  |  |
|_maximum clock_|  |  |
|_Clock gating_|  | Técnica usada em circuitos digitais para economizar energia, desligando sinal de clock em partes do circuito. |
|_ICG_| Integrated Clock Gating | É uma célula padrão (standard cell) usada em microeletrônica para implementar clock gating de forma segura e sem glitches. |
|_CU_| Control Unit |  |
|_PU_| Processing Unit |  |
|_Propagation delay_|  |  |
|_Aperture time_|  |  |
|_Contamination_|  |  |
|_Path delay_|  |  |

***

### Em ASIC designs <a name = "idASIC"></a>

| Sigla | Nome | Descrição |
|-------|------|-----------|
|_ASIC_| Application-Specific Integrated Circuit | CI projetado com finalidade específica |
|_Package_|  |  |
|_Pads_|  | São as bordas do chips usados para conectar sinais de entrada/saída, VDD/GND, comunicações, etc. |
|_Netlist_|  | É o produto da transformação feita por uma EDA de um RTL, utilizando as constraints do projeto e a tecnologia forneceida (gttech/pdk) |
|_Gate level_|  |  |
|_VHSIC_| Very High-speed integrated circuit |  |
|_VHDL_| VHSIC Hardware Description Language) |  |
|_ports_|  | É a interface de um módulo |
|_architecture_|  | É o que o programador vê, ou seja o que o processador faz. ISA,registradores, tipo de dados.. |
|_ISA_| Instruction Set Architecture | Conjunto de instruções implementadas por uma arquitetura computacional |
|_microarchitecture_|  | É como a arquitetura é implementada, ou seja, como o processador faz. Pipeline, ALU, Unidade de controle... |
|_DUT_| Device Under Test |  |
|_stimulus_|  |  |
|_Assertions_|  |  |
|_semaphore_|  |  |
|_mailbox_|  |  |
|_Event_|  | Um evento é ação no tempo zero. Ou seja, uma mudança instântanea que ocorre em determinado ponto. |
|_Testbench_|  |  |
|_Constraints_|  | Especificações definida pelo budget do projeto, podendo conter timing, power, etc.. |
|_TBs_| Testbenchs (wrappers) |  |
|_DUV_| Device under verification |  |
|_CBS_| Cycled-based simulators |  |
|_EBS_| Event-based simulators |  |
|_DSP_| Digital Signal processing |
|_OVI_| Open Verilog International ||
|_TVM_| Test Vector Memory | Memória que armazena vetores de teste, usados junto com ATPG e BIST |
|_ICE_| In-Circuit Emulator |  |
|_LRM_| Verilog Language Reference Manual||
|_PLI_| Programming Language Interface |  |
|_VCD_| Value change dump |  |
|_ABV_| Assertion based Verification |  |
|_FIFO_| First in First Out |  |
|_OVL_| Open Verification library |  |
|_DVE_| Discovery Visualization Environment |  |
|_SDF_| Standard Delay Format | Estrutura de dados de saída que contém o atraso real do circuito. |
|_PDEF_| Physical Definition File |  |
|_DFT_| Design for test |  |
|_PI_| Primary input |  |
|_PO_| Primary output |  |
|_LSSD_| Level-Sensitive Scan Design||
|_BIST_| Built-in Self-Test |  |
|_LFSR_| Linear Feedback Shift Register |  |
|_BILBO_| Built-In Logic Block Observer |  |
|_JTAG_|Joint Test Action Group||
|_TAP_| Test Access Port |  |
|_ATPG_| Automatic Test Pattern Generation |  |
|_ERC_| Electrical Rule Check |  |
|_Signoff_|  |  |
|_LPE_| Layout Parasitc Extraction |  |
|_GDSOUT_| GDSII Output |  |
|_PDV_| Physical Design Verification |  |

***
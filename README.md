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
|_Band Gap_|  |  |
|_Band Theory_|  |  |
|_Polycrystalline_|  |  |
|_Layer_|  |  |
|_Mask_|  |  |
|_Silicon Wafer_|  |  |
|_ICs_| Integred Circuits |  |
|_Ingot_|  |  |
|_Die_|  |  |
|_Scribe line_|  |  |
|_TEG_| Test Element Group |  |
|_Edge Dies_|  |  |
|_Fabs_|  |  |
|_Layout_|  |  |
|_Reticles_|  |  |
|_Mask Layer_|  |  |
|_Mask Data_|  |  |
|_DRC_| Design Rules Check |  |
|_PUN_| Pull-Up |  |
|_PDN_| Pull-Down |  |
|_MOSFETs_|  Metal-Oxide-Semiconductor Field-Effect Transistor |  |
|_CMOS_| omplementary Metal-Oxide-Semiconducto |  |
|_PMOS_| P-channel Metal-Oxide-Semiconductor |  |
|_NMOS_| N-channel Metal-Oxide-Semiconductor |  |
|_SPICE MODEL_|  |  |
|_FinFET_| Fin Field-Effect |  |
|_FDSOI_| Fully Depleted Silicon-On-Insulator |  |
|_VDD_| Voltage Drain Drain |  |
|_VSS_| Voltage Source Source |  |
|_VTC_| Voltage Transfer Characteristics |  |
|_Tphl_| Propagation Delay Time High-to-Low |  |
|_Tplh_| Propagation Delay Time Low-to-high |  |
| TG | Transmission gate | |
|_Fan-in_|  | São os números de entradas de uma porta, que afeta a resistência. Menor fan-in, menor o delay |
|_Fan-out_|  | São os números de saídas de uma porta, que afeta a capacitância. Maior fan-out, maior a carga, delay. |
|_Metastable_|  |  |
|_NORA_| NO-RAce Logic |  |
|_OTP_| One-time programmable |  |
|_SRAM_| Static Random Access Memory |  |
|_DRAM_| Dynamic Random Access Memory |  |
|_RAM_| Random Access Memory |  |
|_ROM_| Read-Only Memory |  |
|_PROM_| Programmable read-only memory |  |
|_DFM_| Design of Manufacturability |  |
|_CAD_| Computer-Aided Design |  |
|_PDK_| Process Design Kit | Tecnologia fornecida pela foundry que consiste em um conjunto de arquivos caracterizados por ela |

***

### Em VLSI <a name = "idVLSI"></a>
| Sigla | Nome completo | Descrição |
|------|--------------|----------|
|_VLSI_| Very Large-Scale Integration |  |
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
|_STANDART CELL_|  |  |
|_CELL_|  |  |
|_BUS_|  |  |
|_PINS_|  |  |
|_GRID_|  |  |
|_FRAM_| "Frame" | Similar ao LEF, descreve também o formato físcico das células |
|_LVS_| Layout Versus Schematics |  |
|_ESD_| Electrostatic Discharge | É aquela descarga de eletricidade estática (tipo quando você leva um choque ao tocar algo), que pode danificar o chip, e pinos |
|_CORE_|  | Fornece a funcionalidade básica de um circuito integrado, o coração do CI |
|_HBM_| Human Body Model |  |
|_RTL_| Register Transfer Level |  |
|_SKEW_|  |  |
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
|_Setup time_|  | Intervalo de tempo antes da borda de clock no qual o dado deve-se manter estável para não ocorrer metaestabilidade | 
|_Hold time_|  | Intervalo de tempo depois da borda de clock no qual o dado deve-se manter estável para não ocorrer metaestabilidade |
|_Signal slew_|  | Tempo necessário para ocorrer uma transação |
|_Pulse Width_|  | Tempo entre o estado atibvo e inativo do clock |
|_Clock latency_|  | Diferença entre a skew e slew |
|_HVT_| High Threshold Voltage |  |
|_RVT_| Regular Threshold Voltage |  |
|_Clock slew_|  |  |
|_Clock jitter_|  |  |
|_Recovery time_|  |  |
|_Removal time_|  |  |
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
|_CDC_| Clock Domain Crossover |  |
|_Metastability_|  | É a instabilidade do sinal em circuitos sequenciais quando o dado muda muito próximo da borda do clock |
|_PVT_| Process Voltage Temperature | Representa as variações físicas e operacionais que afetam o comportamento de um circuito integrado, caracterizado no PDK |
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
|_Minterm_|  |  |
|_Maxterm_|  |  |
|_SOP_| Sum of Products |  |
|_POS_| Product of Sum |  |
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
|_Netlist_|  |  |
|_Gate level_|  |  |
|_VHSIC_| Very High-speed integrated circuit |  |
|_VHDL_| VHSIC Hardware Description Language) |  |
|_ports_|  |  |
|_architecture_|  |  |
|_microarchitecture_|  |  |
|_DUT_| Device Under Test |  |
|_stimulus_|  |  |
|_Assertions_|  |  |
|_semaphore_|  |  |
|_mailbox_|  |  |
|_Event_|  |  |
|_Testbench_|  |  |
|_Constraints_|  |  |
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
|_SDF_| Standard Delay Format |  |
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
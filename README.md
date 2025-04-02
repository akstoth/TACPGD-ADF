# Projeto de Sistemas de Geração Distribuída

Repositório dedicado ao desenvolvimento do projeto da disciplina de Sistemas de Geração Distribuída, com foco em sistemas fotovoltaicos integrados à rede elétrica.

## 📌 Objetivos

- Modelagem e simulação de sistemas completos de GD
- Implementação de técnicas de controle para conversores estáticos
- Desenvolvimento de algoritmos MPPT e sincronismo com rede
- Análise de conformidade com normas técnicas

## 📚 Tópicos Abordados

1. Fontes alternativas de energia para GD
2. Topologias de conversores CC/CC e CC/CA
3. Sistemas MPPT (Rastreamento de Potência Máxima)
4. Técnicas de sincronismo PLL (Phase-Locked Loop)
5. Detecção de ilhamento (Anti-Islanding)
6. Sistemas de armazenamento de energia
7. Conformidade com normas ABNT e IEEE

## 🛠️ Ferramentas Utilizadas

| Componente     | Tecnologias/Recursos                      |
| -------------- | ----------------------------------------- |
| Simulação      | MATLAB/Simulink, PLECS, PSIM              |
| Controle       | PWM, Vetorial dq, Modo Deslizante         |
| Power Hardware | Inversores monofásicos, Conversores Boost |
| Monitoramento  | SCADA para GD, Protocolo MODBUS           |
| Normativas     | NBR 16149, IEEE 1547-2018                 |

## 🗂️ Estrutura do Projeto

```plaintext
GD_Project/
├── Fase1_Modelagem_FV/
│   ├── Modelos_Simulink/
│   ├── Dados_Experimentos/
│   └── Relatorio_EP1.pdf
├── Fase2_Controle_Inversor/
├── Fase3_Conversor_CC-CC/
├── Fase4_Sistema_MPPT/
├── Fase5_Integracao_Total/
├── Fase6_PLL_AntiIlhamento/
└── Documentacao/
    ├── Normativas/
    └── Artigos_Referencia/
```

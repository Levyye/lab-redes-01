![GitHub License](https://img.shields.io/github/license/Levyye/lab-redes-01)

#laboratório de redes 01 projeto de rede local

aluno: levy oliveira

professor:josé de assis

data:09/03/2026

---

## 1. objetivo
implementar uma rede local simples conectando 3 notebooks a um roteador wireless com swuitch e uma impressora de rede.

o projeto será dividido em duas etapas?

1. simulação da rede no Cisco Packet Tracer
2. implementação da rede no laboratório real

 ---

 ## 2. equipamentos utilizados neste laboratório:
 - 3 Notebooks
 - 1 Roteador wireless com 1 porta WAN e 4 portas LAN
 - 1 Impressora de Rede
 - Cabos de Rede

 ---

 ## 3. Topologia da Rede
 
 Diagrama lógico da rede usada neste laboratório
 
```mermaid
graph TD

 WAN[internet / WAN do provedor]

Router[Roteador Wireless<br>1 porta WAN<br>4 Portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de rede]

WAN -->|Porta WAN| Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3
Router --> |LAN 4| Printer

```

Imagem da topologia usada neste laboratório:
![topologia](Topologia.png)





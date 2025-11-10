#  Rota Inteligente – Sabor Express  

##  Descrição do Projeto  
O projeto **Rota Inteligente – Sabor Express** tem como objetivo aplicar **Inteligência Artificial (IA)** e **algoritmos de busca** para otimizar as rotas de entrega de uma empresa fictícia.  

A cidade é modelada como um **grafo**, onde:  
- Os **nós** representam bairros ou pontos de entrega;  
- As **arestas** representam as ruas;  
- Os **pesos** são tempos estimados de deslocamento.  

A solução utiliza:  
-  **Algoritmo A\*** para encontrar a rota mais curta entre origem e destino;  
-  **K-Means** para agrupar entregas em regiões otimizadas.  

O projeto foi desenvolvido e testado no **Google Colab**, gerando visualizações automáticas das rotas e clusters.

---

##  Gráfos do Projeto  

<img width="721" height="299" alt="image" src="https://github.com/user-attachments/assets/f7db92bc-b387-43d1-a8e7-37c609ee203b" />
<img width="809" height="677" alt="image" src="https://github.com/user-attachments/assets/4d04b1c2-a35f-42b8-b045-fe5a0aaad5ef" />
<img width="844" height="677" alt="image" src="https://github.com/user-attachments/assets/db922508-9006-4096-8717-c3fda0397c7f" />
<img width="812" height="669" alt="image" src="https://github.com/user-attachments/assets/50585566-e033-4371-85e7-4c175fc4c293" />


---

##  Execução no Google Colab  

1. Acesse o [https://colab.research.google.com/drive/13MLMz-vsbjA7WbWZSeixK_7X1KPqfbhW?authuser=0#scrollTo=u46ivKhjSvDd).
2. Execute todas as células.  

As imagens `grafo.png`, `rotas_otimizadas.png` e `clusters_visual.png` serão geradas automaticamente.  

---

##  Resultados Gerados  

| Arquivo | Descrição |
|----------|------------|
|  **grafo.png** | Representação visual da cidade e suas conexões |
|  **rotas_otimizadas.png** | Caminho mais curto calculado pelo algoritmo A\* |
|  **clusters_visual.png** | Agrupamento das entregas com K-Means |

---

##  Parte Teórica  

A **Inteligência Artificial** é o campo da computação que busca criar sistemas capazes de aprender, raciocinar e tomar decisões.  
Neste projeto, aplicamos dois conceitos fundamentais:  

- **Busca em Grafos (A\*)**: técnica que encontra o caminho mais eficiente entre dois pontos, considerando custos (tempo, distância, etc.);  
- **Aprendizado Não Supervisionado (K-Means)**: método que agrupa automaticamente entregas próximas, otimizando a logística.  

Esses algoritmos simulam como empresas reais de logística planejam rotas e reduzem custos de transporte.  

---

##  Limitações  

- Depende da qualidade dos dados simulados;  
- Não considera variações de trânsito em tempo real;  
- O número de clusters do K-Means deve ser ajustado conforme a demanda.  

---

##  Referências  

- UPS ORION Case – *On-Road Integrated Optimization and Navigation*  
- Medium – *Optimizing Logistics: Clustering e MILP*  
- ResearchGate – *AI-Powered Route Optimization*  
- Kardinal.ai – *Fresh Product Delivery Case Study*  

---

 **Projeto desenvolvido com base em fundamentos de Inteligência Artificial**, aplicando algoritmos de busca e aprendizado não supervisionado para resolver um problema prático de logística urbana.

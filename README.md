# Uso de Redes Neurais para Reproduzir Resultados de Simulação de Vazão de Produção de Óleo

#### Aluno: [Rogério Leite Alves Pinto](https://codigo-externo.petrobras.com.br/CXMV).
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler).

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

A produção de um poço de petróleo é medida periodicamente através de testes de produção. Os testes de produção medem a vazão total de líquido produzido, vazão de óleo, vazão de água, vazão de gás produzido e vazão de gás injetado (*gas lift*). Também são registradas as pressões e temperaturas em alguns pontos ao longo do escoamento da produção. Durante o período entre dois testes de um determinado poço, não há medição de vazão pois a produção do poço é agregada com a produção de outros poços no separador de produção, não permitindo a medição da sua produção individualizada. Uma alternativa bastante utilizada para estimar a produção de um poço é o uso de simuladores de escoamento multifásico em regime permanente para estimar a vazão a partir de outros parâmetros de produção do poço, tais como pressão e vazão de gás injetado. A cada intervalo de tempo, por exemplo, a cada 5 minutos, faz-se a leitura dos sensores (variáveis de entrada do modelo), roda-se o modelo de simulação, e registra-se o resultado de vazão (variável de saída do simulador). O uso de simuladores requer licenças, recursos computacionais para rodar diversos modelos de simulação simultaneamente e capacidade de armazenamento para salvar os arquivos dos modelos, entre outros. Esta monografia trata de um estudo de conceito de aplicação da técnica de redes neurais para reproduzir os resultados de vazão de produção que são obtidos através de simuladores de escoamento multifásico, podendo trazer ganho em tempo de resposta para se gerar os resultados e ganho em redução de infraestrutura computacional para o sistema de medição virtual. A aplicação de redes neurais a este problema se mostrou bastante robusta, reproduzindo muito bem os resultados do simulador de escoamento.

### Abstract

The production of an oil well is periodically measured through production tests. Production tests measure the flowrate of total produced liquid, oil flowrate, water flowrate, produced gas flowrate and gas lift flowrate. Pressures and temperatures are also recorded at some points along the production flowpath. During the period between two tests of a given well, there is no flow measurement because the production of the well is commingled with the production of other wells into the production separator, not allowing the measurement of its individualized production. A widely used alternative to estimate the production of a well is the use of steady state multiphase flow simulators to estimate the flow rate from other well production parameters, such as pressure and flow of injected gas. Every time interval, for example, every 5 minutes, the virtual measurement system reads the sensors’ signals (model input variables), runs the simulation model and then records the flowrate result (simulator output variable). The use of simulators requires licenses, computational resources to run several simulation models simultaneously and storage capacity to save the models’ files, among others. This monograph deals with a proof of concept study of an application of the neural networks technique to reproduce the results of production flow that are obtained through multiphase flow simulators. This approach can bring gain in response time to generate the results and gain in computational infrastructure reduction for the virtual measurement system. The application of neural networks to this problem proved to be very robust, reproducing very well the results from the flow simulator.

---

Matrícula: 192.190.076

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*

# Sistema IoT de Monitoramento de Umidade do Solo com Calibração ML

Este repositório contém o código e a documentação do meu Trabalho de Conclusão de Curso (TCC) em Engenharia Agronômica, focado no desenvolvimento de uma solução de baixo custo para o monitoramento hídrico do solo, utilizando tecnologias de IoT e análise de dados.

## Sobre o Projeto

O objetivo principal foi criar um sistema acessível e preciso para auxiliar na gestão da irrigação, um desafio crucial na agricultura moderna. O projeto aborda a integração de hardware, firmware e um pipeline robusto de análise de dados.

## Principais Componentes e Tecnologias

*   **Hardware:** Microcontrolador ESP32 DevKitC e sensores resistivos de umidade do solo YL-69.
*   **Firmware:** Desenvolvido em C/C++ (Arduino IDE) para aquisição de dados, aplicação das equações de calibração e comunicação Wi-Fi (incluindo WPA2-Enterprise).
*   **Análise de Dados & Machine Learning:**
    *   Utilização de **Python** com bibliotecas **Pandas** (manipulação de dados), **scikit-learn** (treinamento de modelo de regressão polinomial para calibração de sensores) e **Matplotlib** (visualização).
    *   Todo o processo de análise e modelagem realizado em **Google Colab**.
*   **Plataforma IoT:** Integração com **ThingSpeak** para armazenamento, visualização em tempo real e análise dos dados de umidade do solo.
*   **Contexto Agronômico:** Foco na determinação de parâmetros hídricos do solo (Capacidade de Campo, Ponto de Murcha Permanente) para otimização do manejo da irrigação em Latossolo.

## Estrutura do Repositório

*   `/firmware`: Código-fonte para o ESP32.
*   `/data_analysis`: Scripts Python (Jupyter Notebooks/Google Colab) utilizados para a calibração e análise de dados.
*   `/documentation`: Documentos relacionados ao TCC, como o resumo expandido, diagramas de circuito (se aplicável) e dados brutos de calibração.

## Como Contribuir / Usar

Sinta-se à vontade para explorar o código, replicar o projeto ou sugerir melhorias.

---
**Autor:** Matheus Leandro da Silva
**LinkedIn:** www.linkedin.com/in/matheus-leandro-558205224

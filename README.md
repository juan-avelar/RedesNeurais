# RedesNeurais

# TPF-03: Aprimoramentos no DistilBERT (SST-2)

Este repositório contém o código e o relatório para a entrega final da disciplina de Redes Neurais (TPF-03). O projeto investiga melhorias sobre a reprodução do modelo DistilBERT.

## Experimentos Realizados
1. **Baseline:** Reprodução fiel dos parâmetros originais (Sanh et al., 2019).
2. **Layer Freezing:** Congelamento das camadas inferiores para eficiência.
3. **Hyperparameter Tuning:** Uso de Cosine Scheduler e maior Weight Decay.

## Como Executar
1. Instale as dependências:
   `pip install transformers datasets evaluate torch`
2. Execute o script principal:
   `python TPF03_Experiment.py`

## Resultados Principais
Consulte o relatório PDF (`TPF03_Relatorio.pdf`) para a análise detalhada.

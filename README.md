## Sobre o Projeto
Este projeto foi desenvolvido como parte do aprendizado no Bootcamp de Machine Learning da BairesDev.

- Aluno: Marcello S Bastos - "Mike Niner Bravog"
- Bootcamp: BairesDev - Machine Learning Practitioner - Fevereiro de 2025

# Cálculo de Métricas de Classificação com Matriz de Confusão

## Descrição
Este projeto contém uma função Python que calcula métricas de classificação (Sensibilidade, Especificidade, Acurácia, Precisão e F-Score) a partir de uma matriz de confusão. As métricas são geradas para cada classe e exibidas em um DataFrame.

## Funcionalidades
- Calcula métricas padrão de avaliação de modelos de Machine Learning.
- Gera uma tabela (DataFrame) com métricas individuais para cada classe.
- Tratamento para evitar divisões por zero.

## Estrutura do Projeto
- `calcular_metricas.py`: Script principal com a função de cálculo.
- `readme.md`: Este arquivo explicativo.

## Como Executar
1. Certifique-se de ter Python 3.x instalado.
2. Instale as bibliotecas necessárias:
    ```bash
    pip install numpy pandas
    ```
3. Execute o script com a matriz de confusão fornecida:
    ```bash
    python calcular_metricas.py
    ```

## Exemplo de Saída
Um exemplo de saída esperada será um DataFrame com as colunas:
- Classe, VP, FN, FP, VN, Sensibilidade, Especificidade, Acurácia, Precisão, F-Score

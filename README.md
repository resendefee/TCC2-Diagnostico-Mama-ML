TCC 2 — Diagnóstico de Câncer de Mama com Machine Learning
Este repositório contém o código-fonte do Trabalho de Conclusão de Curso de Fernanda Ester Resende Moraes (UEMG), intitulado:
Aplicação de Algoritmos de machine learning em Dados de Punção Aspirativa para o Diagnóstico do Câncer de Mama

📂 Estrutura
- `tcc2.py` — Script principal de treinamento, avaliação e salvamento dos modelos.
- `resultados_tcc/` — Diretório de resultados (métricas e gráficos gerados).
- `modelos/` — Pipelines salvos em formato `.pkl` para reuso.

📚 Dependências
```bash
pip install ucimlrepo scikit-learn==1.5.2 pandas==2.2.2 matplotlib==3.9.2 seaborn==0.13.2 joblib
```

🧠 Execução
O código pode ser executado no Google Colab ou localmente (Python ≥ 3.9).
Ele realiza:
Carregamento da base WDBC (UCI)
Treinamento de múltiplos modelos (LogReg, SVM, RF, KNN, NB, MLP)
Avaliação e gráficos de desempenho
Exportação do modelo final

✉️ Autora: Fernanda Ester Resende Moraes
Este projeto reforça a importância do uso de técnicas de aprendizado de máquina na área médica, contribuindo para diagnósticos mais precisos e acessíveis.

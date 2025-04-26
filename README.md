# ⚡ Projeto de Monitoramento de Correntes de Entrada de Inversores

![Badge Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Licença](https://img.shields.io/badge/licença-MIT-green)

## 📄 Sobre o Projeto

Este projeto foi desenvolvido para realizar o **monitoramento estatístico** das **correntes de entrada** dos inversores solares, visando identificar rapidamente **anormalidades** no sistema.

O algoritmo analisa as correntes e emite um **alarme automático** para entradas cuja diferença percentual ultrapasse **10%** em relação ao valor de referência, ajudando na detecção precoce de:
- Falhas de strings fotovoltaicas
- Desequilíbrios de geração
- Defeitos em módulos ou conexões

Dessa forma, é possível antecipar ações de manutenção e garantir o melhor desempenho da planta solar.

---

## ✨ Benefícios do Projeto

- 📈 Melhoria na eficiência operacional dos inversores
- 🛡 Detecção proativa de problemas
- ⏳ Redução de tempo de resposta em manutenções corretivas
- 🔍 Monitoramento contínuo e inteligente
- 🧠 Base sólida para integração futura com modelos de IA preditiva

---

## 🛠 Tecnologias Utilizadas

- Python 
- Pandas
- NumPy
- Matplotlib / Plotly (visualização de alarmes)
- Jupyter Notebook

---

## ⚙️ Como Funciona

1. **Importação dos Dados**: Leitura das correntes de entrada dos inversores via arquivos `.csv` ou integração com banco de dados.
2. **Processamento Estatístico**: Cálculo do percentual de diferença entre entradas.
3. **Detecção de Anomalias**: Identificação de diferenças acima de 10%.
4. **Geração de Alarme**: Indicação visual e/ou envio de alerta.

---

## 👨‍💼 Autor

**Alexsander Maia Simas**  
Pleno Cientista de Dados | Especialista em Machine Learning aplicado ao setor de energia energia solar  
[LinkedIn](https://www.linkedin.com/in/alexsander-maia-simas-371222112/) | [alexsandermaiat2@gmail.com](mailto:alexsandermaiat2@gmail.com)

---

## 📚 Licença

Projeto open-source sob licença MIT. Livre para uso, modificação e contribuição. Confira o arquivo [LICENSE](./LICENSE) para mais detalhes.


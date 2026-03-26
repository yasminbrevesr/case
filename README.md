
## Análise de previsão do tempo

Objetivo:

•	Consumir dados de uma API pública.

•	Realizar tratamento e limpeza de dados com Python.

•	Organizar arquivos e estrutura de projeto.

•	Criar uma visualização simples em Power BI.


## Estrutura:
- `notebook/`: Script de extração e tratamento (.ipynb).
- `requirements.txt`: Bibliotecas usadas.
- `datas`: Arquivos em csv e DB.
- `icons`: Icones utilizados no layout.
- `dash`: Painel interativo.
- `background n images`: Fundos criados, logo empresarial, +.

## Você pode conferir o dashboard completo através do link abaixo:

👉 [Clique aqui para acessar o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjMzNDIyZmItNjg1Ny00NGViLTkwNGUtOWM1MWJlY2E5YjEwIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9&pageName=a4bfe55e2f69635d53cb)




<img width="4536" height="2795" alt="Capa" src="https://github.com/user-attachments/assets/ff572c4f-99bf-47a0-a767-95a38c1540ba" />








## Adicionais:
A estrutura do dashboard foi dividida em dois painéis explicativos, com o objetivo de fornecer mais informações ao usuário. Todos os ícones foram configurados como interativos     (clicáveis), permitindo uma navegação mais intuitiva.



![Captura de tela 2026-03-19 113314](https://github.com/user-attachments/assets/60578d46-948d-4b6e-add7-5989e2ea6c69)





## Pipeline end-to-end

```
1. Extração (API)
   └─ Consumo via Requests.
          ↓
2. Processamento (Python/Pandas)
   ├─ Limpeza: Tratamento de nulos.
   ├─ Tipagem: Conversão para Datetime.
   └─ Feature Engineering.
          ↓
3. Armazenamento (Storage)
   └─ CSV via biblioteca OS.
   └─ Banco de Dados (SQLite).
          ↓
4. Modelagem e BI (Power BI)
   ├─ Normalização e Relacionamentos
   └─ Medidas DAX (Cálculos dinâmicos e Storytelling)
          ↓
5. Entrega (Visualização)
   └─ Dashboard
          ↓
6. Automação
   └─ Pipeline de Orquestração (Atualização programada do script e do Gateway) 
   ```




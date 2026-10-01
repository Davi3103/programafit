# Programa Fit

Aplicativo pessoal para medir e calcular a alimentação, com base no exame de bioimpedância. Objetivo: perder gordura e ganhar massa magra.

## Como usar

Abra o `index.html` no navegador, com dois cliques. Não precisa instalar nada.

- **Bioimpedância:** perfil (sexo, idade, altura) e os campos do exame, que você pode editar. Aceita vários exames e campos personalizados.
- **Metas:** calorias, proteína, carboidrato, gordura, fibra e água, calculados a partir do exame (TMB do laudo, Katch-McArdle ou Mifflin-St Jeor). Todos os parâmetros podem ser editados.
- **Diário:** registro das refeições em gramas, com proteína e calorias por item, por refeição e no total do dia.
- **Alimentos:** banco de alimentos editável, com valores por 100 g baseados na tabela TACO e em rótulos.
- **Evolução:** gráficos de peso, % de gordura, massa magra, massa muscular e proteína dos últimos 14 dias.

## Onde ficam os dados

Os dados ficam salvos no navegador (localStorage) do computador onde você usa o app. **Eles não vão para o repositório.** Por isso dá para deixar o repositório público sem expor exames nem refeições.

Os cálculos são uma referência inicial e não substituem o acompanhamento de um nutricionista.

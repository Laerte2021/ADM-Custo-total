# ADM Custo Total - Dashboard de Investimentos

Dashboard executivo para visualização de carteira de investimentos com análise em tempo real.

## 🎯 Funcionalidades

- **KPIs em Destaque**: Patrimônio alocado, maior ativo/classe e retorno projetado
- **Gráfico de Rosca**: Visualização da alocação por categoria
- **Gráfico de Barras**: Evolução do aporte mensal
- **Tabela Detalhada**: Posições discriminadas por ativo, mês e participação
- **Filtros por Período**: Total geral, Janeiro, Fevereiro, Março

## 📊 Dados

Os dados estão armazenados no arquivo `index.html` dentro da variável `dados`. Para adicionar novos registros, edite o array:

```javascript
const dados = [
  { categoria: "Renda Fixa", mes: "Jan", valor: 150000 },
  { categoria: "Ações", mes: "Jan", valor: 80000 },
  // ... mais registros
];
```

## 🚀 Como Usar

1. Clone o repositório
2. Abra o arquivo `index.html` no navegador
3. Ou acesse a página através do GitHub Pages (se habilitado)

## 🎨 Tema

- Modo escuro com tema Slate
- Cor primária: Cyan (#38bdf8)
- Fonte: Segoe UI

## 📝 Licença

Livre para uso pessoal e comercial.
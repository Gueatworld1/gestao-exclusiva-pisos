# 🏪 Gestão - Exclusiva Pisos e Azulejos Antigos

> Sistema de gestão comercial para loja de pisos e azulejos. Roda 100% no navegador — sem servidor, sem banco de dados, sem instalação.

🔗 **[Acessar o sistema](https://SEU-USUARIO.github.io/NOME-DO-REPO)**

---

## ✨ Funcionalidades

### 📦 Inventário
- SKU gerado automaticamente por tipo (`AZU-0001`, `POR-0042`…)
- Campos: Tipo, Marca, Nome, Medida, Quantidade, Valor Unitário, Local, Foto
- Filtros simultâneos por Marca, Medida e Local
- Valor total do estoque calculado automaticamente
- Geração de etiquetas para impressão (90×40mm)

### 👻 Estoque Fantasma
- Pedidos sem material em estoque criam um item provisório (`FAN-0001`)
- Ao receber o material, vincula ao produto real com um clique
- Pedidos fantasma não podem ser concluídos até a resolução

### 🛒 Pedidos
- ID automático: `PED-0001-26` (serial + ano)
- Status: `Pendente → Em andamento → Concluído` (via Vendas) / `Cancelado`
- Suporte a sinal (entrada) com validação de valor
- Aviso em tempo real se a quantidade excede o estoque
- Estimativa de valor automática pelo preço unitário

### 💰 Vendas
- Vendas presenciais ou vinculadas a pedidos
- Ao registrar venda vinculada, pedido é concluído automaticamente
- Gráficos mensais de quantidade e faturamento (últimos 6 meses)
- Exportação CSV do histórico

### 🏷️ Etiquetas
- Impressão em lote ou individual
- Prévia antes de imprimir
- Layout 90×40mm otimizado

### ⚙️ Base de Dados
- Gerenciamento de Tipos e Marcas sem editar código
- SKU vinculado à abreviação do tipo (3 letras)

---

## 💾 Armazenamento

Dados salvos no `localStorage` do navegador — sem servidores, sem contas, sem custo.

> ⚠️ Exporte os CSVs regularmente como backup. Limpar os dados do navegador apaga tudo.

Exportações disponíveis: `inventario.csv` · `pedidos.csv` · `vendas.csv`

---

## 🚀 Como usar

Acesse o link acima ou:

1. Clone o repositório
2. Abra `index.html` no navegador
3. Pronto — nenhuma instalação necessária

---

## 🛠️ Stack

- HTML5 + CSS3 + JavaScript puro (zero dependências)
- `localStorage` para persistência
- GitHub Pages para hospedagem gratuita

---

## 📄 Licença

MIT — sinta-se livre para adaptar.

# 🍏 Checkout FA — Checkout Interno & Handoff (Apple Clean Minimalist)

Interface ultra minimalista no padrão **Apple Cupertino Clean (Light Mode)**, desenvolvida para Closers realizarem a passagem de bastão de vendas ao setor financeiro com agilidade e zero poluição visual.

---

## 🎨 Identidade Visual (Apple Light + Verde da Logo)

- **Fundo da Página:** Cinza Apple ultra claro (`#F5F5F7`).
- **Cards e Painéis:** Branco puro (`#FFFFFF`), bordas quase imperceptíveis (`1px solid #E5E5EA`), cantos arredondados (`border-radius: 16px`) e sombra suave (`0 4px 20px rgba(0, 0, 0, 0.03)`).
- **Tipografia:** `-apple-system`, `BlinkMacSystemFont`, `SF Pro Display`, `Inter` com títulos em preto profundo (`#1D1D1F`) e referências secundárias em cinza neutro (`#86868B`).
- **Cor de Destaque:** `#CCFF00` (Verde Lima Vibrante da Logo).
  - **Regra de Contraste:** Botões e badges com fundo `#CCFF00` sempre utilizam **texto e ícones Pretos (`#1D1D1F`) em negrito**.
- **Logo:** Ícone quadrado arredondado verde `#CCFF00` com símbolo geométrico de 8 pontas.

---

## 📋 Estrutura da Página (Fluxo Direto Sem Abas)

### Coluna Esquerda:
1. **Esteira de Serviços (Lista Estilo Apple):**
   - Todos os 9 produtos visíveis de uma só vez em formato de lista vertical compacta.
   - Cada linha possui:
     - Checkbox minimalista (quando ativo, preenche com `#CCFF00` e check preto).
     - Nome do serviço em `#1D1D1F`. Pílulas discretas para comissão variável (`+5% variável`) e franquia do Dot Sales (`2 usuários`).
     - Referência sutil em cinza: `Cheio: R$ X.XXX · Mín: R$ X.XXX`.
     - Input do valor negociado (preenchido com o valor cheio por padrão) + botões rápidos `Cheio` e `Mín`.
     - Alerta visual sutil quando o valor estiver abaixo do piso mínimo.
2. **Dados para o Contrato:**
   - Card branco no mesmo fluxo, sem necessidade de troca de abas.
   - Closer Responsável, Empresa / Razão Social, CNPJ/CPF com máscara, Responsável pela Assinatura, WhatsApp, E-mail, Forma de Pagamento, Dia de Vencimento, Fidelidade (3, 6, 12 meses) e Observações.

### Coluna Direita (Sticky):
- **Resumo do Fechamento (Estilo Apple Store):**
  - Lista apenas dos itens selecionados com seus respectivos valores.
  - Linha sutil de variável contratual se houver serviços com comissão (5%).
  - Subtotal de Tabela e Desconto Concedido.
  - **TOTAL FECHADO** em destaque tipográfico preto.
  - **Botão Principal:** `Gerar PDF para o Financeiro` (fundo verde `#CCFF00`, texto preto em negrito).
  - **Botão Secundário:** `Copiar Resumo WhatsApp` (fundo `#F5F5F7`, texto preto).

---

## 🚀 Acesso Local

O servidor já está ativo:
👉 **[http://localhost:3000](http://localhost:3000)**

# Minha Agenda

Agenda pessoal: tarefas, controle de entradas/saídas e meta mensal do aluguel.
Funciona no computador e no celular, offline, e pode ser instalada como app.

## Como colocar no ar pelo GitHub (passo a passo)

1. Entre em <https://github.com> e faça login.
2. Clique no **+** (canto superior direito) → **New repository**.
3. Em *Repository name* escreva: `agenda`
   - Marque **Public**
   - Clique em **Create repository**
4. Na tela seguinte, clique em **uploading an existing file**.
5. Arraste para lá os 5 arquivos desta pasta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon.svg`
   - `README.md`
6. Clique em **Commit changes**.
7. No repositório, vá em **Settings** (aba de cima) → **Pages** (menu da esquerda).
8. Em *Source*, escolha **Deploy from a branch**; em *Branch* escolha **main** e a pasta **/ (root)**. Clique em **Save**.
9. Espere 1–2 minutos e recarregue a página. Vai aparecer o link:

   `https://SEU-USUARIO.github.io/agenda/`

Esse é o endereço do seu site. Abra no Chrome do computador e do celular.

## Instalar como aplicativo

- **Android / Chrome:** menu dos 3 pontinhos → *Instalar app* (ou *Adicionar à tela inicial*).
- **iPhone / Safari:** botão de compartilhar → *Adicionar à Tela de Início*.
- **Computador / Chrome:** ícone de instalar na barra de endereço.

Depois disso ela abre em tela cheia, como um app de verdade, e funciona sem internet.

## O que tem dentro

**Tarefas** — adicionar com data, hora e prioridade (alta/média/baixa, com cor na lateral).
Filtros: hoje, pendentes, atrasadas, feitas, todas. Tarefas vencidas aparecem marcadas em vermelho.

**Dinheiro** — lançar entradas e saídas com valor, descrição, data e categoria.
Mostra saldo do dia, entradas do dia, saídas do dia e saldo do mês.
Gráfico de barras dos últimos 7 dias (verde/roxo para dias positivos, vermelho para negativos) com total e média.

**Meta** — meta do aluguel (R$ 1.300, editável). Anel de progresso, quanto falta,
dias restantes no mês e quanto guardar por dia. Botões rápidos +20 / +50 / +100.
Calendário do mês onde cada dia acende conforme o quanto você guardou.
A meta reinicia sozinha todo mês.

**Ajustes** — seu nome, backup e resumo geral.

## Importante sobre os dados

Tudo fica salvo **no navegador do aparelho** (nada vai para a internet, ninguém mais vê).
Por isso o celular e o computador têm dados separados.

Para levar os dados de um para o outro: **Ajustes → Exportar backup**, mande o arquivo `.json`
para o outro aparelho e use **Importar backup**.

Não use "limpar dados de navegação" apagando *dados de sites*, senão perde o que está salvo.
Faça backup de vez em quando.

## Alterar depois

Todo o app está no `index.html` (um arquivo só). Para mudar algo, edite pelo próprio GitHub:
abra o arquivo → ícone de lápis → edite → *Commit changes*. O site atualiza em ~1 minuto.

# Site de Casamento — Wagner & Larissa

Aplicação web desenvolvida para o casamento de **Wagner & Larissa** (11 de Dezembro de 2026), com design contemporâneo estilo Casar.com, hospedada via **GitHub Pages** e alimentada por **Google Apps Script** + **Google Sheets**.

---

## 💍 Funcionalidades do Projeto

1. **Timer de Contagem Regressiva:** Sincronizado para o horário oficial da cerimônia (11/12/2026 às 16:00).
2. **Localização e Navegação:**
   - Detalhes da Cerimônia na *Paróquia Nossa Senhora Rainha da Paz* (Borda do Campo, São José dos Pinhais).
   - Detalhes da Festa na *Chácara Luz da Mata* (Piraquara) com estacionamento no local.
   - Botões diretos para o Google Maps em cada local.
3. **Confirmação de Presença Familiar (RSVP):**
   - **Busca em Três Vias:** Permite pesquisar pelo nome do responsável, pelo nome de qualquer membro do convite ou pelo telefone/WhatsApp cadastrado.
   - **Confirmação Individual:** Lista todos os integrantes da família/grupo para que cada um responda individualmente ("Sim, estarei presente" / "Não poderei ir").
   - **Privacidade de Contato:** Telefone mascarado para conferência visual (`(41) 9976**-****`).
4. **Mural de Recados Dinâmico:** Os convidados deixam mensagens aos noivos pelo site, salvas na aba `Recados` e exibidas em um carrossel deslizante em tempo real.
5. **Mural de Fotos & Álbum Compartilhado:** Botão direto para salvar fotos da festa na pasta compartilhada dos noivos no Google Drive.
6. **Lista de Presentes:** Botão direto integrado à loja virtual da **InfinitePay**.
7. **Painel do Casal (Área Administrativa):** Permite adicionar, editar e desativar convidados preservando o histórico de dados na planilha.

---

## 🗄️ Estrutura das Abas na Planilha do Google Sheets

A planilha (`ID: 125OjHt4o0ZMrzz61s2wMzln_2r4Qhma9riUO9H5RVNE`) contém as seguintes abas:

- **`Convidados`**: `[ConviteID, Convite/Responsável, Nome, Adulto ou Criança, Contato, Ativo]`
- **`Respostas`**: `[Data/Hora, Convite/Responsável, Nome do Integrante, Confirmação, Telefone, Observação]`
- **`Recados`**: `[Data/Hora, Nome, Mensagem]`

---

## 🚀 Como Atualizar no Google Apps Script

1. Copie o código do arquivo `Code.gs`.
2. Salve com `Ctrl + S`.
3. Clique em **Implantar** > **Gerenciar implantações** > **Editar (Ícone de lápis)**.
4. Mude a versão para **Nova versão** e clique em **Implantar**.

🛠️ MacGyver – O Agente Secreto dos Boletos
O **MacGyver** é uma extensão para Chrome e navegadores baseados no Chromium que simplifica o gerenciamento de faturas e boletos em plataformas web específicas.

Ao detectar automaticamente que a página de uma fatura foi carregada, ele exibe uma modal intuitiva com duas opções claras:

**Cancelar Boleto**🗑️
**Confirmar Pagamento** 💰

Basta um clique e o MacGyver simula a ação necessária diretamente no sistema, sem que você precise caçar botões escondidos.

🚀 Como funciona
O MacGyver detecta automaticamente quando a página da fatura é carregada.

Mostra uma modal centralizada com as ações disponíveis.

Ao escolher uma opção:

Ele gera o link de ação correspondente (cancelar ou confirmar).

Simula o clique de forma invisível.

Fecha a modal e conclui a operação rapidamente.

📂 Estrutura do Projeto
bash
Copiar
Editar
macgyver-extension/
│
├── manifest.json        # Configuração da extensão
├── content.js           # Script principal com a lógica da modal
├── icons/               # Ícones da extensão
├── README.md            # Documentação do projeto
└── LICENSE              # Licença MIT
⚡ Escolha rápida para seu boleto
Esta ferramenta visual simplifica a gestão de boletos. Ao carregar a página, uma janela pop-up aparece com duas opções: Cancelar Boleto ou Confirmar Pagamento.

O sistema já identifica automaticamente os dados do seu boleto pela URL, então é só clicar na opção desejada.

A janela irá mostrar o status "Aguarde..." enquanto a ação é processada.

Se precisar, você pode fechar a janela a qualquer momento clicando no "X".

🖥️ Como Usar o Código via Console
Abra a página do boleto no seu navegador.

Abra o console do navegador:

Windows / Linux: Pressione F12 ou Ctrl + Shift + I.

Ou abra o menu do navegador → Mais ferramentas → Ferramentas do desenvolvedor.

Vá até a aba "Console" (normalmente a primeira ou segunda aba).

Permita a colagem (se solicitado):

Alguns navegadores pedem confirmação por segurança.

Digite allow pasting e pressione Enter.

Cole o código:

Copie todo o script do MacGyver.

Clique na linha de comando do console e cole (Ctrl + V).

Execute:

Pressione Enter e o script será executado.

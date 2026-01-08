⚠️ Importante sobre o PIX nos instaladores (EXE)

Os instaladores abaixo (EXE) geram PIX exclusivamente para os clientes pré-fixados no código, sem possibilidade de alteração por este instalador.

Se você quiser um instalador com a sua chave PIX, entre em contato com Rodrigo Marcos (desenvolvedor) pelo WhatsApp +55 11 98645-0369 para comprar a licença.

Temporizador Games (Launcher/Kiosk com controle por tempo + PIX)

O Temporizador Games é um launcher em modo kiosk (tela cheia) para PC/VR, feito para controle de acesso por créditos de tempo (ex.: uso comercial em simuladores/arcades). Ele gera PIX por QR Code, libera automaticamente o tempo quando o pagamento é aprovado e permite navegar/selecionar jogos via joystick (sem teclado/mouse).

Principais recursos

PIX por QR Code (Mercado Pago): exibe QR, monitora o pagamento e, quando aprovado, autoriza o tempo automaticamente e inicia o timer.

Timer de jogo: contagem regressiva por segundos, com opção de fechar o jogo ao encerrar o tempo.

Tela de “tempo esgotado” em fullscreen + alerta sonoro e reinício do fluxo após exibição.

Seleção e abertura de jogos via joystick (DPAD/POV + botões), incluindo tela de configuração do joystick do sistema.

Bloqueio de jogos abertos “por fora” sem crédito: se habilitado e não houver tempo ativo, o app encerra processos da lista iniciados externamente.

Mantém o foco no jogo durante o timer, trazendo o jogo de volta se outra janela roubar o foco (inclui plataformas de movimento).

Integração com plataformas de movimento: permite selecionar (SIMLABVR / SIMTOOLS / SIMRACING STUDIO / SIMHUB) e auto-start do executável configurado.

Histórico de uso + exportação e envio de e-mail ao final (relatório/registro), com dados persistidos criptografados (Fernet).

Auto inicialização com Windows (HKCU Run → TimerStartup.bat).

Startup options por EXE: aplica argumentos automaticamente para executáveis específicos (ex.: Epic Roller Coasters). Fácil de estender via dicionário.

Busca/adição de jogos: janela “Buscar Games” com opção de adicionar manualmente e gerenciar bibliotecas.

Configurações disponíveis no app

Fechar jogo ao encerrar o tempo

Bloquear abertura de jogos externos sem créditos

Exibir SteamVR na lista

Estilo de background (Todos / Corrida / Montanha Russa / Simulador_Voo)

Selecionar plataforma de movimento

Nota rápida de segurança (GitHub)

O projeto usa token do Mercado Pago e chave secret.key para criptografia. Evite commitar tokens reais/segredos no repositório.

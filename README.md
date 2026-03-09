🎹 Teclado MIDI Online

Uma aplicação web de teclado musical completa e responsiva, construída num único ficheiro HTML. Traz a experiência de um sintetizador real diretamente para o navegador, suportando tanto dispositivos MIDI físicos como um sintetizador web integrado com timbres reais de alta qualidade.

✨ Principais Funcionalidades

•	Piano Completo de 88 Teclas: Extensão clássica de Lá 0 (A0) a Dó 8 (C8) com navegação fluida (scroll horizontal).

•	Banco de Sons General MIDI: 128 instrumentos reais e traduzidos para português, carregados instantaneamente através de ficheiros Soundfont.

•	Kits de Bateria: Inclui kits de bateria acústica de estúdio (com samples reais em alta qualidade) e sintetizadores eletrónicos dedicados (como o clássico TR-808).

•	Suporte a Web MIDI API:

o	Entrada: Ligue o seu teclado/controlador MIDI físico por USB e toque diretamente no navegador.

o	Saída: Encaminhe as notas para sintetizadores de hardware ou software instalados no seu sistema operativo.

•	Múltiplos Controlos: Toque usando um teclado MIDI externo, clicando/arrastando com o rato ou utilizando o teclado normal (QWERTY) do seu computador.

•	Controlo de Oitavas: Suba ou desça as oitavas mapeadas no teclado do PC de forma rápida e intuitiva.
🚀 Como Utilizar

Basta abrir o ficheiro teclado_midi.html num navegador web moderno (como Chrome, Edge, ou Firefox). 

Não é necessária nenhuma instalação adicional!

Nota sobre Permissões MIDI: Para utilizar teclados físicos externos, o seu navegador irá pedir permissão para aceder aos dispositivos MIDI. Se a permissão for negada (ou não suportada), a aplicação continuará a funcionar perfeitamente utilizando o Sintetizador Web integrado.

Controlos do Teclado (PC)

O teclado do seu computador está mapeado em duas filas para simular as teclas de um piano:

•	Fila Inferior (Z, X, C, V, etc.): Toca a oitava inferior.

•	Fila Superior (Q, W, E, R, etc.): Toca a oitava atual.

•	Utilize os botões + e - no ecrã para mudar a oitava base.

🛠️ Tecnologias Utilizadas

•	HTML5, CSS3 & JavaScript (ES6+): Código nativo (Vanilla) totalmente contido num único ficheiro.

•	Tailwind CSS: Utilizado via CDN para uma estilização rápida, moderna e responsiva.

•	Web MIDI API: Para comunicação de baixa latência com dispositivos de áudio físicos e virtuais.

•	Soundfont-Player: Biblioteca responsável por descodificar e reproduzir os ficheiros .js de áudio General MIDI no sintetizador de fallback.

•	Web Audio API: Para sintetizar as ondas sonoras (baterias TR-808) e processar os samples reais.

👨‍🏫 Créditos e Autoria

Desenvolvido pelo professor Glauber Santiago — DAC/UFSCar

•	🌐 servidores.ufscar.br/glauber/

•	🌐 sites.google.com/view/glauberia

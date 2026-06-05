<img src="images/logo 16x9.png" alt="Ícone em 16:9 e 1080p" width="950px">

This software is safe, Windows may indicate it as a threat, but check the check carried out on <a href="https://www.virustotal.com/gui/file/b1bc34e1c13034b8d51121d0a6f8fcb5ede2ef8379edb4aae0c5ef521a59fc44?nocache=1" target="_blank">VirusTotal</a>.

# Select your language:
- [English](#eng)
- [Português](#pt-br)
- [日本語](#jp)
- [Español](#esp)
- [中文(简体)](#ch)


---------------


# ENG

# **Boxes Text Editor**

***Boxes Text Editor*** is an open-source text editor designed for text copied from any hexadecimal editor. The main goal of this tool is to simplify and speed up the workflow of translating/correcting game text.

<img src="images/logo HD.png" alt=" " width="1080px">

# **Main Features**:

* Separates text into blocks with a fixed character count, divided from the beginning of a LETTER or NUMBER in a segment until before another one begins with an empty character before it.

<img src="images/blocks.png" alt=" " width="500px">

* Deleted characters are converted into empty spaces instead of being removed entirely. This keeps the segment the same size as the original (ideal for avoiding ISO corruption).
* Characters that are not useful and may clutter editing in the Blocks and Preview windows are hidden. They can be added or removed in the small box containing those characters, but they are still included in the Output.

<img src="images/ocultos.png" alt=" " width="500px">

# **UI Features**:

There are 4 main windows:

* **Input**: Used to insert the text that will be edited. It includes a small dynamic character counter if needed.

<img src="images/input.png" alt=" " width="500px">

* **Preview**: Displays the segment divided into blocks without editing. Direct editing is not possible here; it only updates through the Input. It also contains dynamic counters for each block.

<img src="images/preview.png" alt=" " width="500px">

* **Blocks**: A window containing the divided text blocks, with individual editing and dynamic counters for each block.

<img src="images/blocks0.png" alt=" " width="600px">

* **Output**: Contains the edited text, including the hidden characters restored during editing, delivering the same character count as the Input (or at least it is supposed to). There is also a small button to copy the entire Output content, helping speed up the editing workflow.

<img src="images/output.png" alt=" " width="900px">

**Other Elements**:

* **Reset Layout**: If you change the size and/or position of the windows, use this button to restore everything to default.

<img src="images/reset.png" alt=" " width="500px">
 
* **Dark/Light Mode**: Switches between light and dark interface modes, with Dark Mode enabled by default.

<img src="images/darklightmode.png" alt=" " width="500px">

* **Customizable Theme**: Allows changing the main color used across most of the interface, enabling unique themes.

<img src="images/customcolor.png" alt=" " width="500px">

* **Transparency Control**: Lets you adjust the transparency of window backgrounds, available only for customizable themes.

<img src="images/transp.png" alt=" " width="500px">

* **Hidden/Forbidden Characters**: Allows changing which characters will or will not appear in the Blocks and Preview windows, simply by typing, copying, or pasting them.

<img src="images/ocultos.png" alt=" " width="500px">


# Technical Features:

* **Windows**: The windows are movable and resizable, featuring thin borders and distinctive colors. When transparency is enabled, they display a blurred background effect, creating a stylized overlay appearance.

* **Editing**: Editing is based on character replacement rather than character removal.

  * The Backspace and Delete keys replace characters with blanks (represented by a dot in hex editors). Backspace replaces preceding characters, while Delete replaces following characters.
  * Pressing Enter does not change the number of characters within Blocks (since, after attempting to replace one, line breaks are removed and the cursor returns to the beginning of the segment).
  * Copy and paste functions work normally, simply replacing characters according to the amount pasted, while any remaining characters stay unchanged.
  * Ctrl+Z and Ctrl+Y (Undo and Redo) are also supported, with a limit of up to 150 undo/redo actions.
  * Regular spaces are counted as part of a segment.
  * Segments have fixed sizes, preventing overflow into unrelated segments.
  * Only the content displayed in the Preview and Output windows can be viewed.
  * All character counters are dynamic, making it possible to verify whether the original character count has changed.

* **Appearance**:

  * The **Dark/Light Mode** button switches the colors of the windows and background between black and white, optimized for visibility and visual comfort.

<img src="temp_img.png" alt=" " width="1080px">

* **Custom Colors**: This button allows changing the colors of the windows and background to any RGB, HLS, or HEX color. It is also possible to select any color directly from the screen using the eyedropper tool.

<img src="temp_img.png" alt=" " width="1080px">

* **Window Transparency**: A slider allows adjustment of the window background transparency, providing additional customization.

<img src="temp_img.png" alt=" " width="1080px">

* **Forbidden Characters**: Characters hidden during block editing are managed in this area, where users can type (or paste) and remove any characters they wish to hide while editing Blocks. This helps keep editing cleaner and reduces the risk of accidentally replacing important characters.

<img src="temp_img.png" alt=" " width="1080px">

* The **"Reset Layout"** button restores all windows to their default size and position, undoing any modifications made by the user.

<img src="temp_img.png" alt=" " width="1080px">

**Disclaimer**: I am not responsible for any improper use of this tool (if such use is even possible). Its purpose is to assist with editing text copied from hex editors, making the game translation and proofreading workflow more accessible.

Make good use of this tool and feel free to leave your feedback in the comments, or preferably through my email for such purposes: [bennio23@proton.me](mailto:bennio23@proton.me), or in the discussion tab.

Thank you in advance :)


------------------------


# PT-BR

# **Boxes Text Editor**

***Boxes Text Editor*** é um editor de texto de código aberto projetado para textos copiados  de algum editor hexadecimal. O principal objetivo desta ferramenta é simplificar e agilizar o fluxo de trabalho de tradução/correção de texto de jogos.

<img src="temp_img.png" alt=" " width="1080px">

# **Principais Recursos**:

* Separa o texto em blocos com uma quantidade fixa de caracteres, divididos desde o início de uma LETRA ou NÚMERO em um segmento até antes de outro começar com um caractere vazio antes dele.

<img src="images/blocks.png" alt=" " width="500px">

* Caracteres apagados são convertidos em espaços vazios em vez de serem removidos completamente. Isso mantém o segmento com o mesmo tamanho do original (ideal para evitar corrupção da ISO).
* Caracteres que não são úteis e podem poluir a edição nas janelas de Blocks e Preview ficam ocultos. Eles podem ser adicionados ou removidos na pequena caixa que contém esses caracteres, mas continuam incluídos no Output.

<img src="images/ocultos.png" alt=" " width="500px">

# **Recursos da Interface**:

Existem 4 janelas principais:

* **Input**: Usada para inserir o texto que será editado. Inclui um pequeno contador dinâmico de caracteres, caso necessário.

<img src="images/input.png" alt=" " width="500px">

* **Preview**: Exibe o segmento dividido em blocos sem edição. Não é possível editar diretamente aqui; ele apenas é atualizado através do Input. Também contém contadores dinâmicos para cada bloco.

<img src="images/preview.png" alt=" " width="500px">

* **Blocks**: Uma janela contendo os blocos de texto divididos, com edição individual e contadores dinâmicos para cada bloco.

<img src="images/blocks0.png" alt=" " width="600px">

* **Output**: Contém o texto editado, incluindo os caracteres ocultos restaurados durante a edição, entregando a mesma quantidade de caracteres do Input (ou pelo menos é o que deveria acontecer). Também há um pequeno botão para copiar todo o conteúdo do Output, ajudando a acelerar o fluxo de edição.

<img src="images/output.png" alt=" " width="900px">

**Outros Elementos**:

* **Reset Layout**: Caso você altere o tamanho e/ou posição das janelas, use este botão para restaurar tudo ao padrão.

<img src="images/reset.png" alt=" " width="500px">

* **Dark/Light Mode**: Alterna entre os modos claro e escuro da interface, com o Dark Mode ativado por padrão.

<img src="images/darklightmode.png" alt=" " width="500px">

* **Tema Personalizável**: Permite alterar a cor principal usada na maior parte da interface, possibilitando temas únicos.

<img src="images/customcolor.png" alt=" " width="500px">

* **Controle de Transparência**: Permite ajustar a transparência do fundo das janelas, disponível apenas para temas personalizáveis.

<img src="images/transp.png" alt=" " width="500px">

* **Caracteres Ocultos/Proibidos**: Permite alterar quais caracteres irão ou não aparecer nas janelas Blocks e Preview, apenas digitando, copiando ou colando-os.

<img src="images/ocultos.png" alt=" " width="500px">

# Recursos Técnicos:

* **Janelas**: As janelas são móveis e redimensionáveis, com bordas finas e cores características. Quando a transparência está ativada, exibem um efeito de fundo desfocado, criando uma aparência de overlay estilizada.

* **Edição**: A edição é baseada na substituição de caracteres em vez da remoção deles.

  * As teclas Backspace e Delete transformam caracteres em vazios (representados por um ponto nos editores hex). O Backspace substitui caracteres anteriores, enquanto o Delete substitui os seguintes.
  * Pressionar Enter não altera a quantidade de caracteres dentro dos Blocks (já que, após tentar substituir um, as quebras de linha são removidas e o cursor retorna ao início do segmento).
  * As funções de copiar e colar funcionam normalmente, apenas substituindo caracteres de acordo com a quantidade copiada, enquanto os caracteres restantes permanecem inalterados.
  * Ctrl+Z e Ctrl+Y (desfazer e refazer) também são suportados, com limite de até 150 ações de desfazer/refazer.
  * Espaços comuns são contados como parte de um segmento.
  * Os segmentos possuem tamanhos fixos, impedindo overflow para segmentos não relacionados.
  * Apenas a visualização do conteúdo das janelas Preview e Output é possível.
  * Todos os contadores de caracteres são dinâmicos, permitindo verificar se a quantidade original de caracteres foi alterada.

* Estética:

  * O botão **Dark/Light Mode** altera as cores das janelas e do fundo entre preto e branco, otimizado para visibilidade e conforto visual.

<img src="temp_img.png" alt=" " width="1080px">

* **Cores Personalizáveis**: Este botão permite alterar as cores das janelas e do fundo para qualquer cor RGB, HLS ou HEX. Também é possível selecionar qualquer cor diretamente da tela usando a ferramenta conta-gotas.

<img src="temp_img.png" alt=" " width="1080px">

* **Transparência das Janelas**: Um slider permite ajustar a transparência do fundo das janelas, oferecendo personalização adicional.

<img src="temp_img.png" alt=" " width="1080px">

* **Caracteres Proibidos**: Os caracteres ocultados durante a edição dos blocos são gerenciados nesta área, onde os usuários podem digitar (ou colar) e remover quaisquer caracteres que desejarem ocultar durante a edição dos Blocks. Isso mantém a edição mais limpa e evita substituir caracteres importantes acidentalmente.

<img src="temp_img.png" alt=" " width="1080px">

* O botão "**Reset Layout**" restaura todas as janelas para o tamanho e posição padrão, desfazendo quaisquer modificações feitas pelo usuário.

<img src="temp_img.png" alt=" " width="1080px">

**Aviso**: Não me responsabilizo pelo uso inadequado desta ferramenta (caso isso sequer seja possível). Seu propósito é auxiliar na edição de textos copiados de editores hex, tornando mais acessível o fluxo de tradução e correção de jogos.

Faça bom uso desta ferramenta e sinta-se à vontade para deixar seu feedback nos comentários, ou preferencialmente através do meu e-mail para esse tipo de finalidade: [bennio23@proton.me](mailto:bennio23@proton.me), ou na aba de discussões.

Agradeço desde já :)


--------------------------------------


# JP

# **Boxes Text Editor**

***Boxes Text Editor***は、あらゆる16進数エディタからコピーしたテキストに対応するように設計されたオープンソースのテキストエディタです。このツールの主な目的は、ゲームテキストの翻訳／修正作業を簡素化し、高速化することです。

<img src="temp_img.png" alt=" " width="1080px">

# **主な機能**:

* テキストを固定文字数のブロックに分割します。分割は、セグメント内の文字または数字の開始位置から、空白文字を挟んだ次の文字または数字が始まる直前まで行われます。

<img src="images/blocks.png" alt=" " width="500px">

* 削除された文字は完全に消去されず、空白文字へ変換されます。これにより、元のセグメントと同じサイズを維持できます（ISO破損防止に最適です）。
* Blocks および Preview ウィンドウで編集の邪魔になる不要な文字は非表示になります。これらの文字は専用の小さなボックスで追加・削除できますが、Output には引き続き含まれます。

<img src="images/ocultos.png" alt=" " width="500px">

# **UI機能**:

主なウィンドウは4つあります:

* **Input**: 編集するテキストを入力するためのウィンドウです。必要に応じて、動的な文字数カウンターが表示されます。

<img src="images/input.png" alt=" " width="500px">

* **Preview**: 編集前のセグメントをブロック分割した状態で表示します。ここで直接編集することはできず、Input を通じてのみ更新されます。また、各ブロックごとの動的カウンターも表示されます。

<img src="images/preview.png" alt=" " width="500px">

* **Blocks**: 分割されたテキストブロックを含むウィンドウで、各ブロックを個別に編集できます。各ブロックには動的カウンターもあります。

<img src="images/blocks0.png" alt=" " width="600px">

* **Output**: 編集後のテキストを表示します。編集中に隠されていた文字も復元され、Input と同じ文字数を維持します（少なくともそのように動作するはずです）。また、Output 全体をコピーするための小さなボタンもあり、編集作業を効率化できます。

<img src="images/output.png" alt=" " width="900px">

**その他の要素**:

* **Reset Layout**: ウィンドウのサイズや位置を変更した場合、このボタンでデフォルト状態に戻せます。

<img src="images/reset.png" alt=" " width="500px">

* **Dark/Light Mode**: ライトモードとダークモードを切り替えます。デフォルトではダークモードが有効です。

<img src="images/darklightmode.png" alt=" " width="500px">

* **Customizable Theme**: インターフェース全体で使用されるメインカラーを変更し、独自テーマを作成できます。

<img src="images/customcolor.png" alt=" " width="500px">

* **Transparency Control**: ウィンドウ背景の透明度を調整できます。カスタムテーマ使用時のみ利用可能です。

<img src="images/transp.png" alt=" " width="500px">

* **Hidden/Forbidden Characters**: Blocks および Preview ウィンドウに表示・非表示にする文字を、入力・コピー・貼り付けによって変更できます。

<img src="images/ocultos.png" alt=" " width="500px">

# 技術的な機能

* **ウィンドウ**: ウィンドウは移動およびサイズ変更が可能で、細い枠線と特徴的な色を備えています。透明化が有効な場合、背景にぼかし効果が適用され、スタイリッシュなオーバーレイ表示になります。

* **編集**: 編集は文字の削除ではなく、文字の置換を基準としています。

  * BackspaceキーおよびDeleteキーは文字を空白に置き換えます（16進エディタではドットで表示されます）。Backspaceは前方の文字を、Deleteは後方の文字を置換します。
  * Enterキーを押してもBlocks内の文字数は変化しません（文字の置換後に改行が削除され、カーソルがセグメントの先頭へ戻るためです）。
  * コピー＆ペースト機能は通常どおり動作し、貼り付けた文字数に応じて文字を置換します。残りの文字は変更されません。
  * Ctrl+ZおよびCtrl+Y（元に戻す／やり直し）にも対応しており、最大150回までの操作履歴を保持します。
  * 通常のスペースもセグメントの一部としてカウントされます。
  * セグメントのサイズは固定されているため、無関係なセグメントへのオーバーフローは発生しません。
  * PreviewウィンドウおよびOutputウィンドウの内容のみ閲覧可能です。
  * すべての文字数カウンターは動的に更新されるため、元の文字数が変更されたかどうかを確認できます。

* **外観**

  * **Dark/Light Mode** ボタンは、ウィンドウおよび背景の色を黒と白の間で切り替えます。視認性と快適な閲覧体験を重視して設計されています。

<img src="temp_img.png" alt=" " width="1080px">

* **カスタムカラー**: このボタンを使用すると、ウィンドウおよび背景の色を任意のRGB、HLS、またはHEXカラーに変更できます。また、スポイトツールを使用して画面上の任意の色を直接選択することも可能です。

<img src="temp_img.png" alt=" " width="1080px">

* **ウィンドウの透明度**: スライダーを使用してウィンドウ背景の透明度を調整でき、さらなるカスタマイズが可能です。

<img src="temp_img.png" alt=" " width="1080px">

* **非表示文字**: Blocks編集中に非表示にする文字をこのエリアで管理できます。ユーザーは編集時に隠したい文字を入力（または貼り付け）したり、削除したりできます。これにより編集画面が見やすくなり、重要な文字を誤って置換するリスクを軽減できます。

<img src="temp_img.png" alt=" " width="1080px">

* **「Reset Layout」** ボタンは、すべてのウィンドウを初期サイズおよび初期位置に戻し、ユーザーが行った変更をリセットします。

<img src="temp_img.png" alt=" " width="1080px">

**注意事項**: 本ツールの不適切な使用について、作者は一切の責任を負いません（そもそもそのような使用が可能かどうかは別として）。本ツールは16進エディタからコピーしたテキストの編集を支援し、ゲームの翻訳および校正作業をより効率的に行えるようにすることを目的としています。

このツールをぜひ活用し、コメント欄、またはこのような目的のために用意している私のメールアドレス [bennio23@proton.me](mailto:bennio23@proton.me)、もしくはディスカッションタブからお気軽にフィードバックをお寄せください。

よろしくお願いします :)


--------------------------------


# ESP

# **Boxes Text Editor**

***Boxes Text Editor*** es un editor de texto de código abierto diseñado para texto copiado desde cualquier editor hexadecimal. El objetivo principal de esta herramienta es simplificar y agilizar el proceso de traducción y corrección de textos de videojuegos.

<img src="temp_img.png" alt=" " width="1080px">

# **Características Principales**:

* Separa el texto en bloques con una cantidad fija de caracteres, divididos desde el inicio de una LETRA o NÚMERO en un segmento hasta antes de que otro comience con un carácter vacío antes de él.

<img src="images/blocks.png" alt=" " width="500px">

* Los caracteres eliminados se convierten en espacios vacíos en lugar de eliminarse completamente. Esto mantiene el segmento con el mismo tamaño que el original (ideal para evitar corrupción de la ISO).
* Los caracteres que no son útiles y pueden dificultar la edición en las ventanas Blocks y Preview se ocultan. Estos pueden agregarse o eliminarse en la pequeña caja que contiene dichos caracteres, pero siguen incluidos en el Output.

<img src="images/ocultos.png" alt=" " width="500px">

# **Funciones de la Interfaz**:

Existen 4 ventanas principales:

* **Input**: Se utiliza para insertar el texto que será editado. Incluye un pequeño contador dinámico de caracteres si es necesario.

<img src="images/input.png" alt=" " width="500px">

* **Preview**: Muestra el segmento dividido en bloques sin edición. No es posible editar directamente aquí; solo se actualiza a través del Input. También contiene contadores dinámicos para cada bloque.

<img src="images/preview.png" alt=" " width="500px">

* **Blocks**: Una ventana que contiene los bloques de texto divididos, con edición individual y contadores dinámicos para cada bloque.

<img src="images/blocks0.png" alt=" " width="600px">

* **Output**: Contiene el texto editado, incluyendo los caracteres ocultos restaurados durante la edición, entregando la misma cantidad de caracteres que el Input (o al menos eso se supone). También hay un pequeño botón para copiar todo el contenido del Output, ayudando a acelerar el flujo de edición.

<img src="images/output.png" alt=" " width="900px">

**Otros Elementos**:

* **Reset Layout**: Si cambias el tamaño y/o posición de las ventanas, utiliza este botón para restaurar todo al estado predeterminado.

<img src="images/reset.png" alt=" " width="500px">

* **Dark/Light Mode**: Cambia entre los modos claro y oscuro de la interfaz, con el modo oscuro activado por defecto.

<img src="images/darklightmode.png" alt=" " width="500px">

* **Tema Personalizable**: Permite cambiar el color principal utilizado en la mayor parte de la interfaz, posibilitando temas únicos.

<img src="images/customcolor.png" alt=" " width="500px">

* **Control de Transparencia**: Permite ajustar la transparencia del fondo de las ventanas, disponible solo para temas personalizables.

<img src="images/transp.png" alt=" " width="500px">

* **Caracteres Ocultos/Prohibidos**: Permite cambiar qué caracteres aparecerán o no en las ventanas Blocks y Preview, simplemente escribiéndolos, copiándolos o pegándolos.

<img src="images/ocultos.png" alt=" " width="500px">

# Características Técnicas:

* **Ventanas**: Las ventanas son móviles y redimensionables, con bordes finos y colores característicos. Cuando la transparencia está activada, muestran un efecto de fondo desenfocado, creando una apariencia de superposición estilizada.

* **Edición**: La edición se basa en la sustitución de caracteres en lugar de su eliminación.

  * Las teclas Backspace y Delete reemplazan los caracteres por espacios vacíos (representados por un punto en los editores hexadecimales). Backspace sustituye los caracteres anteriores, mientras que Delete sustituye los siguientes.
  * Presionar Enter no modifica la cantidad de caracteres dentro de los Blocks (ya que, después de intentar reemplazar uno, los saltos de línea se eliminan y el cursor vuelve al inicio del segmento).
  * Las funciones de copiar y pegar funcionan normalmente, reemplazando caracteres según la cantidad pegada, mientras que los caracteres restantes permanecen sin cambios.
  * También se admiten Ctrl+Z y Ctrl+Y (deshacer y rehacer), con un límite de hasta 150 acciones de deshacer/rehacer.
  * Los espacios normales se cuentan como parte de un segmento.
  * Los segmentos tienen tamaños fijos, lo que impide el desbordamiento hacia segmentos no relacionados.
  * Solo es posible visualizar el contenido de las ventanas Preview y Output.
  * Todos los contadores de caracteres son dinámicos, lo que permite verificar si la cantidad original de caracteres ha sido modificada.

* **Apariencia**:

  * El botón **Dark/Light Mode** cambia los colores de las ventanas y del fondo entre negro y blanco, optimizado para la visibilidad y la comodidad visual.

<img src="temp_img.png" alt=" " width="1080px">

* **Colores Personalizables**: Este botón permite cambiar los colores de las ventanas y del fondo a cualquier color RGB, HLS o HEX. También es posible seleccionar cualquier color directamente desde la pantalla utilizando la herramienta cuentagotas.

<img src="temp_img.png" alt=" " width="1080px">

* **Transparencia de las Ventanas**: Un control deslizante permite ajustar la transparencia del fondo de las ventanas, ofreciendo una personalización adicional.

<img src="temp_img.png" alt=" " width="1080px">

* **Caracteres Ocultos**: Los caracteres ocultados durante la edición de los bloques se gestionan en esta área, donde los usuarios pueden escribir (o pegar) y eliminar cualquier carácter que deseen ocultar mientras editan los Blocks. Esto mantiene la edición más limpia y ayuda a evitar la sustitución accidental de caracteres importantes.

<img src="temp_img.png" alt=" " width="1080px">

* El botón **"Reset Layout"** restaura todas las ventanas a su tamaño y posición predeterminados, deshaciendo cualquier modificación realizada por el usuario.

<img src="temp_img.png" alt=" " width="1080px">

**Aviso**: No me responsabilizo por el uso indebido de esta herramienta (si es que tal uso fuera posible). Su propósito es ayudar en la edición de textos copiados desde editores hexadecimales, haciendo más accesible el flujo de trabajo de traducción y corrección de videojuegos.

Haz buen uso de esta herramienta y no dudes en dejar tus comentarios, o preferiblemente enviarlos a través de mi correo electrónico para este tipo de asuntos: [bennio23@proton.me](mailto:bennio23@proton.me), o en la pestaña de discusiones.

Gracias de antemano :)


-----------------------------------------


# CH

# **Boxes Text Editor**

***Boxes Text Editor*** 是一款开源文本编辑器，专为从任何十六进制编辑器复制的文本而设计。该工具的主要目标是简化和加快游戏文本的翻译/校对工作流程。

<img src="temp_img.png" alt=" " width="1080px">

# **主要功能**：

* 将文本分割为固定字符数量的区块，从一个段落中字母或数字的开头开始，直到下一个在空字符前开始的字母或数字之前结束。

<img src="images/blocks.png" alt=" " width="500px">

* 被删除的字符不会被彻底移除，而是会转换为空字符。这样可以保持段落与原始大小一致（非常适合避免 ISO 损坏）。
* 在 Blocks 和 Preview 窗口中，对编辑没有帮助且可能造成干扰的字符会被隐藏。用户可以在包含这些字符的小框中添加或移除它们，但它们仍然会保留在 Output 中。

<img src="images/ocultos.png" alt=" " width="500px">

# **界面功能**：

共有 4 个主要窗口：

* **Input**：用于输入需要编辑的文本。如果需要，还会显示一个动态字符计数器。

<img src="images/input.png" alt=" " width="500px">

* **Preview**：显示已分割为区块但尚未编辑的段落。无法直接在这里编辑；它只会通过 Input 更新。同时还包含每个区块的动态计数器。

<img src="images/preview.png" alt=" " width="500px">

* **Blocks**：包含已分割文本区块的窗口，支持单独编辑，并为每个区块提供动态计数器。

<img src="images/blocks0.png" alt=" " width="600px">

* **Output**：包含编辑后的文本，并恢复编辑过程中隐藏的字符，最终输出与 Input 相同的字符数量（至少理论上如此）。此外，还有一个小按钮可复制整个 Output 内容，以加快编辑流程。

<img src="images/output.png" alt=" " width="900px">

**其他元素**：

* **Reset Layout**：如果更改了窗口大小和/或位置，可使用此按钮恢复默认布局。

<img src="images/reset.png" alt=" " width="500px">

* **Dark/Light Mode**：切换界面的深色/浅色模式，默认启用深色模式。

<img src="images/darklightmode.png" alt=" " width="500px">

* **Customizable Theme**：允许更改界面大部分区域使用的主颜色，从而创建独特主题。

<img src="images/customcolor.png" alt=" " width="500px">

* **Transparency Control**：允许调整窗口背景透明度，仅适用于自定义主题。

<img src="images/transp.png" alt=" " width="500px">

* **Hidden/Forbidden Characters**：允许通过输入、复制或粘贴字符，自定义哪些字符会或不会显示在 Blocks 和 Preview 窗口中。

<img src="images/ocultos.png" alt=" " width="500px">

# 技术特性：

* **窗口**：窗口支持移动和调整大小，具有细边框和独特的配色。当启用透明效果时，窗口会显示模糊背景效果，从而呈现出风格化的叠加界面外观。

* **编辑**：编辑方式基于字符替换，而非字符删除。

  * Backspace 和 Delete 键会将字符替换为空白（在十六进制编辑器中显示为一个点）。Backspace 替换前方字符，而 Delete 替换后方字符。
  * 按下 Enter 键不会改变 Blocks 中的字符数量（因为在尝试替换字符后，换行符会被移除，光标会返回到该段的开头）。
  * 复制和粘贴功能可正常使用，仅根据粘贴内容的长度替换相应数量的字符，其余字符保持不变。
  * 支持 Ctrl+Z 和 Ctrl+Y（撤销与重做），最多可记录 150 次撤销/重做操作。
  * 普通空格也会被计入段落长度。
  * 各段长度固定，防止内容溢出到无关段落中。
  * 只能查看 Preview 和 Output 窗口中的内容。
  * 所有字符计数器均为动态更新，可用于检查原始字符数量是否发生变化。

* **界面外观：**

  * **Dark/Light Mode（深色/浅色模式）** 按钮可在黑色和白色主题之间切换窗口及背景颜色，并针对可读性和视觉舒适度进行了优化。

<img src="temp_img.png" alt=" " width="1080px">

* **自定义颜色**：此按钮允许将窗口和背景颜色设置为任意 RGB、HLS 或 HEX 颜色。同时还可以使用取色器工具直接从屏幕上选取颜色。

<img src="temp_img.png" alt=" " width="1080px">

* **窗口透明度**：通过滑块可以调整窗口背景的透明度，提供额外的个性化设置选项。

<img src="temp_img.png" alt=" " width="1080px">

* **隐藏字符**：在编辑 Blocks 时需要隐藏的字符可在此区域进行管理。用户可以输入（或粘贴）以及移除任何希望在编辑过程中隐藏的字符。这样能够让编辑界面更加整洁，并减少意外替换重要字符的风险。

<img src="temp_img.png" alt=" " width="1080px">

* **“Reset Layout”** 按钮可将所有窗口恢复到默认大小和位置，撤销用户所做的任何布局修改。

<img src="temp_img.png" alt=" " width="1080px">

**免责声明**：对于本工具的任何不当使用（如果这种情况确实存在），本人概不负责。本工具旨在辅助编辑从十六进制编辑器复制的文本，使游戏翻译与校对流程更加便捷高效。

请充分利用这个工具，并随时在评论区留下您的反馈，或者更推荐通过我的电子邮箱 [bennio23@proton.me](mailto:bennio23@proton.me)（用于此类用途），也可以在讨论区中提出您的意见。

提前感谢 :)

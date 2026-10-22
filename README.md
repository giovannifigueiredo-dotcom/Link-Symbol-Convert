<!-- ... existing code ... -->
## 🚀 Como Usar

1. Abra o ficheiro `index.html` no seu navegador web.
2. Irá deparar-se com uma interface centralizada com fundo animado.
3. Clique em "📁 Escolher imagem do dispositivo..." para fazer upload de uma imagem do seu computador. Ela será convertida em Base64 e o campo será preenchido.
4. Em alternativa, no campo de texto, cole o link direto da imagem que deseja usar.
5. Clique no botão **Copiar Imagem**. O script criará um canvas oculto, desenhará a imagem e gerará um arquivo de forma invisível.
6. Em caso de sucesso, receberá um feedback visual, e a **própria imagem visual** (e não o texto!) estará pronta para ser colada (`Ctrl+V` ou `Cmd+V`) em chats, documentos ou editores de imagem.

## 📋 Histórico de Atualizações (Changelog)

Todas as alterações e melhorias notáveis neste projeto são documentadas nesta secção.

### [1.5.0] - Renderização com Canvas e Cópia Visual (Pixels)
**Alterado**
* A funcionalidade principal foi completamente reformulada. Em vez de copiar texto, a aplicação agora carrega o link ou Base64 num objeto `Image()`.
* Utilização da **Canvas API** para renderizar a imagem e usar `canvas.toBlob()` para gerar um arquivo PNG em memória.
* Uso de `new ClipboardItem({'image/png': blob})` para copiar os pixels visuais reais para a área de transferência.
* Implementação de tratamento rigoroso para erros de CORS que podem impedir o carregamento no Canvas, emitindo um alerta amigável.
* Títulos e descrições visuais no HTML atualizados.

### [1.4.0] - Cópia de Texto e Links
<!-- ... existing code ... -->
## 🛠️ Tecnologias Utilizadas

* **HTML5:** Semântica e estruturação da nova interface (títulos, descrições, inputs).
* **CSS3:** Estilização avançada com Flexbox, gradientes lineares, `backdrop-filter` (Glassmorphism), sombras fluídas e animações.
* **JavaScript (Vanilla):** 
  * Lógica Assíncrona (`async/await` e `Promises`).
  * **FileReader API** para upload local.
  * **Canvas API (`<canvas>`)** para manipulação e desenho de imagens ocultas.
  * **Clipboard API** nativa avançada para converter blobs com `ClipboardItem` e gravar imagens reais no sistema operativo.

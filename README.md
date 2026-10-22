# Botão de Cópia para a Área de Transferência

Um projeto simples em HTML, CSS e JavaScript que permite copiar símbolos ou imagens (através de um link) diretamente para a área de transferência do utilizador com um único clique.

## 🚀 Como Usar

1. Abra o ficheiro `index.html` no seu navegador web.
2. Para copiar a imagem, insira o link da imagem desejada no campo de texto (ou deixe o padrão).
3. Clique no botão **Copiar Imagem**.
4. Se o navegador e o servidor da imagem permitirem (CORS), receberá um alerta de sucesso e a imagem estará pronta a ser colada.

## 📋 Histórico de Atualizações (Changelog)

Todas as alterações e melhorias notáveis neste projeto serão documentadas nesta secção.

### [1.1.0] - Imagens por Link
**Adicionado**
- Funcionalidade para copiar imagens diretamente para a área de transferência usando a `Clipboard API` do JavaScript.
- Campo de texto interativo (`<input>`) que permite ao utilizador colar o link de qualquer imagem.
- Alertas de sucesso ou de erro (lidando com possíveis bloqueios de CORS).

### [1.0.0] - Lançamento Inicial
**Adicionado**
- Estrutura base em HTML5.
- Estilização básica com CSS para um botão verde e arredondado.
- Script em JavaScript para copiar o símbolo estático de barra (`/`) usando a criação de um elemento de texto temporário e `document.execCommand("copy")`.

---

## 🛠️ Tecnologias Utilizadas
- **HTML5:** Estrutura da interface.
- **CSS3:** Estilização do botão e do campo de texto.
- **JavaScript (Vanilla):** Lógica de manipulação do DOM e integração com a `Clipboard API` (`navigator.clipboard.write`).

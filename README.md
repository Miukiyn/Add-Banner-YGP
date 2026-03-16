
---

# 🖼️ Guia: Como Extrair Imagens do Wallpaper Engine

Este guia prático ensina como transformar os arquivos internos do Wallpaper Engine em arquivos de imagem comuns (PNG/JPG) utilizando a ferramenta **RePKG**.

---

## 🛠️ 1. Preparando a Ferramenta

1. Acesse o repositório oficial do **RePKG no GitHub**.
2. Baixe a versão mais recente do arquivo `.zip` (ex: `RePKG.zip`).
3. Extraia o conteúdo para uma pasta de sua preferência no computador.

## 📂 2. Localizando o Wallpaper

1. Abra o **Wallpaper Engine**.
2. Escolha o wallpaper desejado.
3. Clique com o botão direito sobre ele e selecione **"Open in Explorer"** (Abrir no Explorador).

## 🔍 3. Identificando o Formato

Ao abrir a pasta do wallpaper, verifique a estrutura de arquivos:

* **Possui uma pasta `files`?** Entre nela. Se a imagem original estiver lá em alta resolução, você terminou! Basta copiá-la.
* **Possui um arquivo `scene.pkg`?** Você precisará extraí-lo seguindo o próximo passo.

---

## ⚡ 4. Extraindo de Arquivos .PKG

Caso o wallpaper utilize o formato compactado da Engine, siga este procedimento:

1. **Copie** o arquivo `scene.pkg` da pasta do wallpaper.
2. **Cole** o arquivo dentro da pasta onde você extraiu o **RePKG** (Passo 1).
3. Na barra de endereços da pasta, apague o caminho, digite `cmd` e aperte **Enter**.
4. No terminal que abrir, execute o seguinte comando:
```bash
RePKG.exe extract scene.pkg

```


5. Aguarde a mensagem `"Done"` aparecer.

---

## ✅ 5. Resultado Final

Após a execução, uma pasta chamada `output` será gerada automaticamente:

1. Vá para: `output` > `materials`.
2. Sua imagem estará lá, pronta para uso!

> [!TIP]
> **Dica:** Se o wallpaper for composto por várias camadas, a imagem principal geralmente terá o nome do tema e estará em alta resolução dentro da pasta `materials`.

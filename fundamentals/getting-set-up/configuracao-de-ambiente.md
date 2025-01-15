# 📝 Configuração de Ambiente

{% hint style="info" %}
**Charlie:** your product docs aren't just a reference of all your features, use them to encourage folks to perform certain actions and discover the value in your product.
{% endhint %}

**1. Dependências**

* **Node.js**: Utilize a versão especificada em `.nvmrc`.
* **Gerenciador de pacotes**: npm ou yarn.
*   **Ferramentas globais**:

    ```bash
    bashCopy codenpm install -g eslint prettier
    ```

**2. Configurações do Editor**

Configure o **VS Code** para seguir os padrões do projeto:

*   **Settings.json**:

    ```json
    jsonCopy code{
      "editor.formatOnSave": true,
      "editor.tabSize": 2,
      "files.eol": "\n",
      "eslint.autoFixOnSave": true,
      "tailwindCSS.experimental.classRegex": ["tw`([^`]*)", "tw='([^']*)"]
    }
    ```

**3. Configuração de API**

* Ambiente de desenvolvimento:
  * `https://api.dev.exemplo.com`
* Ambiente de produção:
  * `https://api.exemplo.com`

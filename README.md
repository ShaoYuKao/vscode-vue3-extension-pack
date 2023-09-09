# VS Code Vue3 Extension Pack

## Extensions Included

- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)\
    更改前端 html 或 css 樣式的時候可以即時在瀏覽器預覽成果

- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)\
    程式碼格式化

- [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)\
    縮排檢視

- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)\
    自動補上程式碼末端標籤，這絕對是程式工作者最大的福音

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)\
    當你的標籤寫錯了要更改又找不到末端標籤怎麼辦，這個會動記住你的末端標籤是誰並且聯動的更改\
    因為 Auto Rename Tag 擴充套件非常好用，但預設會自動套用在所有檔案格式，這會帶來一些麻煩。\
    例如在 JS/TS 檔案中剛好改到有 < 的內容時，會導致程式被改壞，所以建議限制特定檔案才需要這個功能。
    ```json
    {
        "auto-rename-tag.activationOnLanguage": [ "html", "xml", "php" ]
    }
    ```

- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)\
    需要引入文件或者其他資料時，這將會是你的好幫手

- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)\
    使用縮寫快速產生 ES6 的語法

- [es6-string-html](https://marketplace.visualstudio.com/items?itemName=Tobermory.es6-string-html)\
    JavaScript 開發上一定很常使用到樣板字面值，但是在 VSCode 往往都是相同的橘色顏色，如果裡面剛好我們樣板字面值是 HTML 的話，時常會很難辨別，因此可以使用 es6-string-html 這個套件來將樣板字面值裡面的顏色高亮

- [cdnjs](https://marketplace.visualstudio.com/items?itemName=JakeWilson.vscode-cdnjs)\
    可以直接搜尋需要的 CDNJS 來快速引入

- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)\
    將待辦的項目做標示，利於日後修復或者標記工作排成時使用，也能自定義標籤名稱及顏色

- [Vue Language Features (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.volar)\
    Volar 全名是 Vue Language Features (Volar)，如果你是 Vue3 的話，那麼這個套件會非常建議你安裝。這個套件主要是幫你程式碼高亮、提示、自動補全等等，非常強大，而且它也是 Vue 官方推薦的套件。

- [Vue 3 Support - All In One](https://marketplace.visualstudio.com/items?itemName=Wscats.vue)\
    快速幫助我們生成 Vue 的語法

- [Vue 3 Snippets](https://marketplace.visualstudio.com/items?itemName=hollowtree.vue-snippets)\
    Vue 2 和 Vue 3  的程式碼片段

- [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)

- [AutoFileName](https://marketplace.visualstudio.com/items?itemName=JerryHong.autofilename)

- [#region folding for VS Code](https://marketplace.visualstudio.com/items?itemName=maptz.regionfolder)\
    VS Code 中定義可折疊的程式碼片段

- [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag)\
    點選 tag 結尾的 tag 字體下面會有底線，方便你知道 tag 的範圍

- [Remove empty lines](https://marketplace.visualstudio.com/items?itemName=usernamehw.remove-empty-lines)\
    從文檔或選擇中刪除空白行。\
    - `ctrl` + `shift` + `p`，輸入 `Remove empty lines`，即可選擇[刪除空白行]模式

- [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)\
    是 Vue 的一個工具包，不僅讓 Vue 的語法可以突出顯示，也提供了 Vue.js 的語言功能(例如：語法高亮、智慧感知、片段、格式)，讓我們在撰寫時可以更便利輕鬆。而 Vetur 在維護上也處理得很好，甚至連 Vue3 Typescript 都有支援。

- [Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)\
    這個套件能夠提醒你，程式碼如果有看起來像是合法字元，或是不可見的字元出現，在很多時候，程式碼中若包含了這些東西，很可能會引發預期之外的錯誤，通常發生這些問題會很難追查

- [Color Manager](https://marketplace.visualstudio.com/items?itemName=RoyAction.color-manager)
    color picker and color palette

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    Integrates ESLint JavaScript into VS Code.

- [ESLint Chinese Rules](https://marketplace.visualstudio.com/items?itemName=maggie.eslint-rules-zh-plugin)
    eslint 中文规则提示插件

- [bracket-padder](https://marketplace.visualstudio.com/items?itemName=viablelab.bracket-padder)
    Smart whitespace padding & auto-closing for bracket pairs

- [Indenticator](https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator)
    Highlights your current indent depth

## Preferences Settongs

> `File` => `Preferences` => `Settings`

- 在 JS 片段使用 emmet

    ```json
    {
        "emmet.includeLanguages": {
            "javascript": "javascriptreact",
            "vue-html": "html",
            "plaintext": "jade"
        },
        "emmet.triggerExpansionOnTab": true,
    }
    ```

- Prettier Code formatter 設定

    ```json
    {
        "prettier.singleQuote": true,
    }
    ```

    | Key         | 資料型態 | 說明           |
    | ----------- | -------- | -------------- |
    | singleQuote | boolean  | 使用單引號     |
    | semi        | boolean  | 結束是否加分號 |

- 使用 Tab 鍵進行 Emmet 擴展
    ```json
    {
        "emmet.triggerExpansionOnTab": true
    }
    ```

### Extensions NOT Included but might be useful

You need to install the following extensions manually if you need:\
(如果需要，您需要手動安裝以下擴展：)

- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)\
    只要你是工程師，那麼我就會建議你安裝，因為如果你跟我一樣打字英文單字總是會打錯的話，Code Spell Checker 會是你的好幫手。

- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

- [i18n Ally](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally)\
    如果你的專案有使用 i18n 的話，我會建議你可以安裝 i18n Ally，因為這一個套件可以讓你在 VSCode 上面直接編輯 i18n 的語系檔案，而且它也可以幫助你快速的找到沒有翻譯的語系。

- [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)\
    一款滿讓人崩潰的套件，只要你的程式碼有出現任何錯誤，它就會直接在你的 VSCode 上面大大的顯示出來

- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)\
    非常的單純，就只是讓你可以高亮顯示 .env 檔案的內容而已。

- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)\
    工作區域改變顏色。操作說明: [Peacock for VS Code：为你的窗口添上五彩斑斓的色彩](https://zhuanlan.zhihu.com/p/84175150)

- [Comment Translate](https://marketplace.visualstudio.com/items?itemName=intellsmi.comment-translate)\
    許多優秀的項目，都有豐富的注釋，使用者可以快速理解代碼意圖。但是如果使用者並不熟習注釋的語言，會帶來理解困難。 本外掛程式使用 Google、Bing、Baidu、AliCloud、DeepL等的 Translate API 翻譯 VSCode 的程式設計語言的注釋。

- [Paste JSON as Code (Refresh)](https://marketplace.visualstudio.com/items?itemName=doggy8088.quicktype-refresh)\
    - [重新認識 quicktype 與 Paste JSON as Code 擴充套件 - YT](https://www.youtube.com/watch?v=CoDDUbwtvrI)

- [Bracket Pair Colorization Toggler](https://marketplace.visualstudio.com/items?itemName=dzhavat.bracket-pair-toggler)\
    使用簡單的命令快速切換"括號對著色"設置\
    ```json
    {
        "editor.bracketPairColorization.enabled": true
    }
    ```

- [\[Deprecated\] Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)\
    - 括號分色2。
    - 在早期是要安裝的，但是後來 VSCode 就內建整合了進去，你只需要稍微調整一下 VSCode 就可以啟用哩~
    ```json
    {
        // Bracket Pair Colorizer 2
        "editor.bracketPairColorization.enabled": true,
        "editor.guides.bracketPairs":"active",
    }
    ```
    - 從 VS Code 1.67 版起內建，bracket pair colorization 已改為「預設開啟」，這意味著下面的第一個設定 editor.bracketPairColorization.enabled，除非是要關閉而設定為 false，否則可以整行省略。(https://blog.kyomind.tw/bracket-pair-colorization/)
    ```json
    {
        // 開啟 bracket pair colorization；1.67 以上可省略此開啟設定
        "editor.bracketPairColorization.enabled": true,
        // 設定顏色
        "workbench.colorCustomizations": {
            // 層級括號顏色，從 1 至 6 層，此處只設定了 5 層
            "editorBracketHighlight.foreground1": "#7777ff",
            "editorBracketHighlight.foreground2": "#8a2be2",
            "editorBracketHighlight.foreground3": "#DC143C",
            "editorBracketHighlight.foreground4": "#5eaaa8",
            "editorBracketHighlight.foreground5": "#800080",
            // 異常括號的顏色，比如多出來的結尾括號
            "editorBracketHighlight.unexpectedBracket.foreground": "#ffffff",
        }
    }
    ```

- [Text Marker (Highlighter)](https://marketplace.visualstudio.com/items?itemName=ryu1kn.text-marker)\
    特定文本高亮外掛程式。 括弧匹配高亮配置。

- [SCSS Everywhere](https://marketplace.visualstudio.com/items?itemName=gencer.html-slim-scss-css-class-completion)\
    HTML、Svelte、Latte、Slim、Liquid、TSX/JSX、Haml、Elixir、Smarty、PHP、ERB、Javascript、CSS 和 SCSS 的“.class”和“#id”完成。只需在您的範本或 CSS/SCSS 中聲明類，並在任何地方看到它。（雙向）

- [Document This](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis)\
    在 TypeScript 和 JavaScript 檔中自動生成詳細的 JSDoc 注釋。

## Working with Markdown

You can author your README using Visual Studio Code. Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on macOS or `Ctrl+\` on Windows and Linux).
* Toggle preview (`Shift+Cmd+V` on macOS or `Shift+Ctrl+V` on Windows and Linux).
* Press `Ctrl+Space` (Windows, Linux, macOS) to see a list of Markdown snippets.

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**

# usefulJavascriptSnippets

```
static copyToClipboard(textToCopy) {

        const el = document.createElement('textarea');
        el.value = textToCopy;
        document.body.appendChild(el);
        el.select();
        document.execCommand('copy');
        document.body.removeChild(el);
    }
```

# Available Bookmarklets
## Classic
Switch to Classic UI from Touch
```javascript
javascript:window.location.href=window.location.href.replace(/editor\.html/gi,'cf#')
```
## Touch 
Switch to Touch UI from Classic
```javascript
javascript:window.location.href=window.location.href.replace(/cf#/gi,'editor.html')
```

## UnCheck All
Uncheck all checkboxes. This is very useful in the side navigation in touch ui. If you are looking for references and want to select a few, you would first check all and then use this bookmarklet to uncheck all.
```javascript
javascript:$(".coral3-Checkbox-input").prop("checked",false);
```

# Further Reading about Bookmarlets
http://www.dev-hq.net/posts/1--create-javascript-bookmarklet


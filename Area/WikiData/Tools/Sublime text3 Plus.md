## Sublime text3 Plus

熱鍵指令
---
1. 換頁 			Alt + 123
2. 切頁 			Alt + Shift + 12345
3. 書籤新增/移除 	Ctrl + F2
4. MD打開		Alt + M 
	
控制台指令
---
```
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

Install Package 
---
UTF8
> ConvertToUTF8

Icon
> A File Icon

代碼括號
> BracketHighlighter

繁中化
> ChineseLocalization

網頁編輯
> Emmet

顯示所選顏色值
> Color Highlight  '#A4AD51'

調色盤#ACA (UTF8這個會撞快鍵)
> Color Picker

Markdown Preview
呼叫出 打mdp選 第一個 再選 Markdown

熱鍵追加設定
```
 { "keys": ["alt+m"], "command": "markdown_preview", "args": {"target": "browser", "parser":"markdown"}  }
```

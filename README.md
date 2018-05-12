Sublime Text 3 Kurulumu ve Popüler Eklentilerinin Yüklenmesi

## Hızlı Erişim

1. [Sublime Text 3 İndir](#1-sublime-text-3-İndir)
2. [Package Control](#2-package-control-kurulumu)
3. [Emmet](#3-emmet-kurulumu)
4. [Sidebar Enhancements](#4-sidebar-enhancements-kurulumu)
5. [Sublime​Linter](#5-sublimelinter-kurulumu)
	1. [SublimeLinter-csslint](#51-sublimelinter-csslint-kurulumu)
	2. [SublimeLinter-jshint](#52-sublimelinter-jshint-kurulumu)
	3. [SublimeLinter-contrib-scss-lint](#53-sublimelinter-contrib-scss-lint-kurulumu)
	4. [SublimeLinter-contrib-sass-lint](#54-sublimelinter-contrib-sass-lint-kurulumu)
	5. [SublimeLinter-contrib-htmlhint](#55-sublimelinter-contrib-htmlhint-kurulumu)
6. [BracketHighlighter](#6-brackethighlighter-kurulumu)
7. [Sublime​Code​Intel](#7-sublimecodeintel-kurulumu)
8. [HTML5](#8-html5-kurulumu)
9. [Alignment](#9-alignment-kurulumu)
10. [Sass](#10-sass-kurulumu)
11. [Color​Picker](#11-colorpicker-kurulumu)
12. [j​Query](#12-jquery-kurulumu)
13. [Git](#13-git-kurulumu)
14. [FTPSync](#14-ftpsync-kurulumu)
15. [DocBlockr](#15-docblockr-kurulumu)
16. [HTML-CSS-JS Prettify](#16-html-css-js-prettify-kurulumu)
17. [Convert​To​UTF8](#17-converttoutf8-kurulumu)
18. [Auto​File​Name](#18-autofilename-kurulumu)
19. [Color Highlighter](#19-color-highlighter-kurulumu)
20. [All Autocomplete](#20-all-autocomplete-kurulumu)
21. [A File Icon](#21-a-file-icon-kurulumu)
22. [Material Theme](#22-material-theme-kurulumu)
23. [Emmet](#23-emmet-kurulumu)
24. [GitGutter](#24-gitgutter-kurulumu)

### 1. Sublime Text 3 İndir

[https://www.sublimetext.com/](https://www.sublimetext.com/)

### 2. Package Control Kurulumu

[https://packagecontrol.io/installation](https://packagecontrol.io/installation)

1. View > Show Console menüsüne tıklayın.
2. Alt kısımda açılan yere [Package Control](https://packagecontrol.io/installation) sayfasında yer alan kodu yapıştırın. 
3. Kurulum tamamlandıktan sonra CTRL+Shift+P tuşuna basarak eklentileri kurabilirsiniz. 

### 3. Emmet Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Emmet yazın ve kurulum tamamlanmasını bekleyin.
4. Kurulum bittikten sonra deneme yapabilirsiniz. 

Örnek: 
```
nav>ul>li
```
Yukarıdaki kodu yazın, ardından CTRL+E tuşuna basın.

```
<nav>
  <ul>
    <li></li>
  </ul>
</nav>
```
Bu şekilde bir çıktı ile karşılaşacaksınız. Hızlı kod yazmanıza olanak sağlaycaktır. 

Daha fazla örnek için [Cheat Sheet](https://docs.emmet.io/cheat-sheet/) sayfasına bakabilirsiniz. 

### 4. Sidebar Enhancements Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Sidebar Enhancements yazın ve kurulum tamamlanmasını bekleyin.
4. Kurulum bittikten sonra projenizi Sublime Text'te sürükleyin.
5. Sol tarafta yer alan kısımdan dosya oluşturma, silme, kopyalama vb. işlemleri yapabilirsiniz. 

### 5. Sublime​Linter Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Sublime​Linter yazın ve kurulum tamamlanmasını bekleyin.
4. Daha sonra [Node.js](https://nodejs.org/) sayfasında programı indirin. Kurulumu tamamlayın.

	#### 1. [SublimeLinter-csslint Kurulumu](https://github.com/SublimeLinter/SublimeLinter-csslint)

	1. CTRL+Shift+P tuşuna basın.
	2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
	3. Bir sonra açılan kutucuğa SublimeLinter-csslint yazın ve kurulum tamamlanmasını bekleyin.
	4. Daha sonra Terminal ekranı açın. 
	5. `npm install -g csslint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

	#### 2. [SublimeLinter-jshint Kurulumu](https://github.com/SublimeLinter/SublimeLinter-jshint)

	1. CTRL+Shift+P tuşuna basın.
	2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
	3. Bir sonra açılan kutucuğa SublimeLinter-jshint yazın ve kurulum tamamlanmasını bekleyin.
	4. Daha sonra Terminal ekranı açın. 
	5. `npm install jshint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

	#### 3. [SublimeLinter-contrib-scss-lint Kurulumu](https://github.com/attenzione/SublimeLinter-scss-lint)

	1. CTRL+Shift+P tuşuna basın.
	2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
	3. Bir sonra açılan kutucuğa SublimeLinter-contrib-scss-lint yazın ve kurulum tamamlanmasını bekleyin.
	4. Daha sonra Terminal ekranı açın. 
	5. `gem install scss_lint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

	#### 4. [SublimeLinter-contrib-sass-lint Kurulumu](https://github.com/skovhus/SublimeLinter-contrib-sass-lint)

	1. CTRL+Shift+P tuşuna basın.
	2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
	3. Bir sonra açılan kutucuğa SublimeLinter-contrib-sass-lint yazın ve kurulum tamamlanmasını bekleyin.
	4. Daha sonra Terminal ekranı açın. 
	5. `npm install -g sass-lint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

	#### 5. [SublimeLinter-contrib-htmlhint Kurulumu](https://github.com/mmaday/SublimeLinter-contrib-htmlhint)

	1. CTRL+Shift+P tuşuna basın.
	2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
	3. Bir sonra açılan kutucuğa SublimeLinter-contrib-htmlhint yazın ve kurulum tamamlanmasını bekleyin.
	4. Daha sonra Terminal ekranı açın. 
	5. `npm install -g htmlhint@latest` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

### 6. BracketHighlighter Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa BracketHighlighter yazın ve kurulum tamamlanmasını bekleyin.

### 7. Sublime​Code​Intel Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Sublime​Code​Intel yazın ve kurulum tamamlanmasını bekleyin.

### 8. HTML5 Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa HTML5 yazın ve kurulum tamamlanmasını bekleyin.

### 9. Alignment Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Alignment yazın ve kurulum tamamlanmasını bekleyin.
4. Ayarlar için: 
	* Windows: Preferences > Package Settings > Alignment > Settings - User
	* Linux: Preferences > Package Settings > Alignment > Settings - User
	* Mac OS X: Sublime Text 2 > Preferences > Package Settings > Alignment * Settings - User
5. Dosya boş olmalıdır. Aşağıdakileri kodu yapıştırın:
```
{
    "alignment_chars": [
        "=", ":"
    ]
}
```
6. Dosyasını kaydedin ve kapatın. 
7. Hizalamak istedğiniz kodu seçin ve Ctrl+Alt+A tuşuna basın.
8. Eğer Ctrl+Alt+A tuşu çalışmıyorsa. Aşağıdaki  ayarları yapabilirsiniz. 
	* Windows: Preferences > Package Settings > Alignment > Key Bindings (default)
	* Linux: Preferences > Package Settings > Alignment > Key Bindings (default)
	* Mac OS X: Sublime Text 2 > Preferences > Package Settings > Key Bindings (default)
9. Dosya boş olmalıdır. Aşağıdakileri kodu yapıştırın:
```
[
    { "keys": ["ctrl+alt+s"], "command": "alignment" }
]
```
10. Dosyasını kaydedin ve kapatın. 
11. Hizalamak istedğiniz kodu seçin ve Ctrl+Alt+S tuşuna basın.

### 10. Sass Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Sass yazın ve kurulum tamamlanmasını bekleyin.

### 11. Color​Picker Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Color​Picker yazın ve kurulum tamamlanmasını bekleyin.
4. Seçilen bir rengi eklemek veya değiştirmek için şunu yapın:
	* Windows: CTRL+SHIFT+C
	* Mac OS X: CMD+SHIFT+C
	* Linux: CTRL+SHIFT+C

### 12. j​Query Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa j​Query yazın ve kurulum tamamlanmasını bekleyin.

### 13. Git Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Git yazın ve kurulum tamamlanmasını bekleyin.
4. CTRL+Shift+P tuşuna basın. Daha sonra Git: yazarak Git komutlarını kullanabilirsiniz. 

### 14. FTPSync Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa FTPSync yazın ve kurulum tamamlanmasını bekleyin.
4. Kurulum bittikten sonra projenizi Sublime Text'te sürükleyin.
5. CTRL+Shift+P tuşuna basın.
6. FtpSyncs: Setup FTPSync in this folder yazın. Açılan bölüme ftp bilgilerini yazın. 

Örnek ftpsync.settings dosyası: 

```
{
	"default": {

		"host": "ftp.example.com",
		"username": "your_login", 
		"password": "your_password",
		"path": "/",

		"upload_on_save": true,
		"overwrite_newer_prevention": false,
	}
}
```

### 15. DocBlockr Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​DocBlockr yazın ve kurulum tamamlanmasını bekleyin.
4. /** veya /* yazdıktan sonra enter tuşuna basın.

### 16. HTML-CSS-JS Prettify Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​HTML-CSS-JS Prettify yazın ve kurulum tamamlanmasını bekleyin.
4. Hizaları bozuk olan kodlarını CTRL+SHIFT+H ile düzeltebilirsiniz. 
5. Kaydettiğinizde otomatik düzeltmek için 
	*  Preferences > Package Settings > HTML-CSS-JS Prettify > Plugin Options - Default
6.  `"format_on_save": false,` olan kodu `"format_on_save": true,` hale getirin.

### 17. Convert​To​UTF8 Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​Convert​To​UTF8 yazın ve kurulum tamamlanmasını bekleyin.

### 18. Auto​File​Name Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​Auto​File​Name yazın ve kurulum tamamlanmasını bekleyin.

### 19. Color Highlighter Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​Color Highlighter yazın ve kurulum tamamlanmasını bekleyin.

### 20. All Autocomplete Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​All Autocomplete yazın ve kurulum tamamlanmasını bekleyin.

### 21. A File Icon Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​A File Icon yazın ve kurulum tamamlanmasını bekleyin.

### 22. Material Theme Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​Material Theme yazın ve kurulum tamamlanmasını bekleyin.
4. Temayı aktif etmek için: 
	*  Preferences > Settings
5.  Açılan sağ alana kodu yapıştırın. 
```
"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
"theme": "Material-Theme.sublime-theme",
```

### 23. Emmet Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa Emmet CSS Snippets yazın ve kurulum tamamlanmasını bekleyin.
4. Kurulum bittikten sonra deneme yapabilirsiniz. 

Örnek: 
```
.block{
	pos:s+w10+h20+mt20;
}
```
Yukarıdaki kodu yazın, ardından CTRL+E tuşuna basın.

```
.block{
  position: static;
  width: 10px;
  height: 20px;
  margin-top: 20px;
}
```
Bu şekilde bir çıktı ile karşılaşacaksınız. Hızlı kod yazmanıza olanak sağlaycaktır. 

Daha fazla örnek için [Emmet CSS Snippets](http://peiwen.lu/Emmet-Css-Snippets-for-Sublime-Text-2/) sayfasına bakabilirsiniz. 


### 24. GitGutter Kurulumu

1. CTRL+Shift+P tuşuna basın.
2. Açılan kutucuğa Package Control: Install Package yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​GitGutter yazın ve kurulum tamamlanmasını bekleyin.
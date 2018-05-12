## Sublime Text 3

Sublime Text 3 Kurulumu ve Popüler Eklentilerinin Yüklenmesi

---

## Hızlı Erişim

- [Sublime Text 3 İndir](#sublime-text-3-İndir)
- [Package Control](#package-control-kurulumu)
- [Emmet](#emmet-kurulumu)
- [Sidebar Enhancements](#sidebar-enhancements-kurulumu)
- [Sublime​Linter](#sublimelinter-kurulumu)
	- [SublimeLinter-csslint](#sublimelinter-csslint-kurulumu)
	- [SublimeLinter-jshint](#sublimelinter-jshint-kurulumu)
	- [SublimeLinter-contrib-scss-lint](#sublimelinter-contrib-scss-lint-kurulumu)
	- [SublimeLinter-contrib-sass-lint](#sublimelinter-contrib-sass-lint-kurulumu)
	- [SublimeLinter-contrib-htmlhint](#sublimelinter-contrib-htmlhint-kurulumu)
	- [BracketHighlighter](#brackethighlighter-kurulumu)
- [Sublime​Code​Intel](#sublimecodeintel-kurulumu)
- [HTML5](#html5-kurulumu)
- [Alignment](#alignment-kurulumu)
- [Sass](#sass-kurulumu)
- [Color​Picker](#colorpicker-kurulumu)
- [j​Query](#jquery-kurulumu)
- [Git](#git-kurulumu)
- [FTPSync](#ftpsync-kurulumu)
- [DocBlockr](#docblockr-kurulumu)
- [HTML-CSS-JS Prettify](#html-css-js-prettify-kurulumu)
- [Convert​To​UTF8](#converttoutf8-kurulumu)
- [Auto​File​Name](#autofilename-kurulumu)
- [Color Highlighter](#color-highlighter-kurulumu)
- [All Autocomplete](#all-autocomplete-kurulumu)
- [A File Icon](#a-file-icon-kurulumu)
- [Material Theme](#material-theme-kurulumu)
- [Emmet CSS Snippets](#emmet-css-snippets)
- [GitGutter](#gitgutter-kurulumu)

-----

## Sublime Text 3 İndir

[https://www.sublimetext.com/](https://www.sublimetext.com/)

## Package Control Kurulumu

**Sublime Text 3** içerisine bir eklenti kurabilmemiz için öncelikler **Package Control**'un kurulu olması gerekir.

[https://packagecontrol.io/installation](https://packagecontrol.io/installation)

1. `View > Show` Console menüsüne tıklayın.
2. Alt kısımda açılan yere **[Package Control](https://packagecontrol.io/installation)** sayfasında yer alan kodu yapıştırın. 
3. Kurulum tamamlandıktan sonra **CTRL+Shift+P** tuşuna basarak eklentileri kurabilirsiniz. 

## Emmet Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Emmet** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Kurulum bittikten sonra deneme yapabilirsiniz. 

**Emmet kullanımına bir örnek:**

```
nav>ul>li
```
Yukarıdaki kodu yazın, ardından **CTRL+E** tuşuna basın.

```
<nav>
  <ul>
    <li></li>
  </ul>
</nav>
```
Bu şekilde bir çıktı ile karşılaşacaksınız. Hızlı kod yazmanıza olanak sağlaycaktır. 

Daha fazla örnek için **[Cheat Sheet](https://docs.emmet.io/cheat-sheet/)** sayfasına bakabilirsiniz. 

## Sidebar Enhancements Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Sidebar Enhancements** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Kurulum bittikten sonra projenizi Sublime Text'te sürükleyin.
5. Sol tarafta yer alan kısımdan dosya oluşturma, silme, kopyalama vb. işlemleri yapabilirsiniz. 

## Sublime​Linter Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Sublime​Linter** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Daha sonra [Node.js](https://nodejs.org/) sayfasında programı indirin. Kurulumu tamamlayın.

### [SublimeLinter-csslint Kurulumu](https://github.com/SublimeLinter/SublimeLinter-csslint)

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **SublimeLinter-csslint** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Daha sonra **Terminal** ekranı açın. 
5. `npm install -g csslint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

### [SublimeLinter-jshint Kurulumu](https://github.com/SublimeLinter/SublimeLinter-jshint)

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **SublimeLinter-jshint** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Daha sonra **Terminal** ekranı açın. 
5. `npm install jshint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

### [SublimeLinter-contrib-scss-lint Kurulumu](https://github.com/attenzione/SublimeLinter-scss-lint)

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **SublimeLinter-contrib-scss-lint** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Daha sonra **Terminal** ekranı açın. 
5. `gem install scss_lint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

### [SublimeLinter-contrib-sass-lint Kurulumu](https://github.com/skovhus/SublimeLinter-contrib-sass-lint)

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **SublimeLinter-contrib-sass-lint** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Daha sonra **Terminal** ekranı açın. 
5. `npm install -g sass-lint` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

### [SublimeLinter-contrib-htmlhint Kurulumu](https://github.com/mmaday/SublimeLinter-contrib-htmlhint)

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **SublimeLinter-contrib-htmlhint** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Daha sonra **Terminal** ekranı açın. 
5. `npm install -g htmlhint@latest` kodu yapıştırın ve kurulum tamamlanmasını bekleyin. 

## BracketHighlighter Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **BracketHighlighter** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Sublime​Code​Intel Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Sublime​Code​Intel** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## HTML5 Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **HTML5** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Alignment Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Alignment** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Ayarlar için: 
	* **Windows:** Preferences > Package Settings > Alignment > Settings - User
	* **macOS:** Sublime Text 2 > Preferences > Package Settings > Alignment * Settings - User
	* **Linux:** Preferences > Package Settings > Alignment > Settings - User
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
8. Eğer **Ctrl+Alt+A** tuşu çalışmıyorsa. Aşağıdaki  ayarları yapabilirsiniz. 
	* **Windows:** Preferences > Package Settings > Alignment > Key Bindings (default)
	* **macOS:** Sublime Text 2 > Preferences > Package Settings > Key Bindings (default)
	* **Linux:** Preferences > Package Settings > Alignment > Key Bindings (default)
9. Dosya boş olmalıdır. Aşağıdakileri kodu yapıştırın:

```
[
    { "keys": ["ctrl+alt+s"], "command": "alignment" }
]
```

10. Dosyasını kaydedin ve kapatın. 
11. Hizalamak istedğiniz kodu seçin ve **Ctrl+Alt+S** tuşuna basın.

## Sass Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Sass** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Color​Picker Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Color​Picker** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Seçilen bir rengi eklemek veya değiştirmek için şunu yapın:
	* **Windows:** CTRL+Shift+C
	* **macOS:** CMD+Shift+C
	* **Linux:** CTRL+Shift+C

## j​Query Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **j​Query** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Git Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Git** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. **CTRL+Shift+P** tuşuna basın. Daha sonra **Git:** yazarak *Git* komutlarını kullanabilirsiniz. 

## FTPSync Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **FTPSync** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Kurulum bittikten sonra projenizi Sublime Text'te sürükleyin.
5. **CTRL+Shift+P** tuşuna basın.
6. **FtpSyncs: Setup FTPSync in this folder** yazın. Açılan bölüme ftp bilgilerini yazın. 

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

## DocBlockr Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **​DocBlockr** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. `/**` veya `/*` yazdıktan sonra Enter tuşuna basın.

## HTML-CSS-JS Prettify Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​**HTML-CSS-JS Prettify** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Hizaları bozuk olan kodlarını **CTRL+Shift+H** ile düzeltebilirsiniz. 
5. Kaydettiğinizde otomatik düzeltmek için 
	* **Windows:** Preferences > Package Settings > HTML-CSS-JS Prettify > Plugin Options - Default
	* **macOS:** Sublime Text 2 > Preferences > Package Settings > HTML-CSS-JS Prettify > Plugin Options - Default
	* **Linux:** Preferences > Package Settings > HTML-CSS-JS Prettify > Plugin Options - Default

6.  `"format_on_save": false,` olan kodu `"format_on_save": true,` hale getirin.

## Convert​To​UTF8 Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​**Convert​To​UTF8** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Auto​File​Name Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **​Auto​File​Name** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Color Highlighter Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​**Color Highlighter** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## All Autocomplete Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​**All Autocomplete** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## A File Icon Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​**A File Icon** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.

## Material Theme Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa ​**Material Theme** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Temayı aktif etmek için: 
	* **Windows:** Preferences > Settings
	* **macOS:** Sublime Text 2 > Preferences > Settings
	* **Linux:** Preferences > Settings

5.  Açılan sağ alana kodu yapıştırın. 
```
"color_scheme": "Packages/Material Theme/schemes/Material-Theme.tmTheme",
"theme": "Material-Theme.sublime-theme",
```

## Emmet CSS Snippets Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **Emmet CSS Snippets** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
4. Kurulum bittikten sonra deneme yapabilirsiniz. 

**Emmet CSS Snippets kullanımına bir örnek:** 
```
.block{
	pos:s+w10+h20+mt20;
}
```
Yukarıdaki kodu yazın, ardından **CTRL+E** tuşuna basın.

```
.block{
  position: static;
  width: 10px;
  height: 20px;
  margin-top: 20px;
}
```
Bu şekilde bir çıktı ile karşılaşacaksınız. Hızlı kod yazmanıza olanak sağlaycaktır. 

Daha fazla örnek için **[Emmet CSS Snippets](http://peiwen.lu/Emmet-Css-Snippets-for-Sublime-Text-2/)** sayfasına bakabilirsiniz. 


## GitGutter Kurulumu

1. **CTRL+Shift+P** tuşuna basın.
2. Açılan kutucuğa **Package Control: Install Package** yazın ve Enter tuşuna basın. 
3. Bir sonra açılan kutucuğa **​GitGutter** yazın ve Enter tuşuna basın. Kurulum tamamlandıktan eklenti hakkında döküman sayfası açılacaktır.
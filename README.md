symfony2-and-google-translate
=============================

<h2>symfony2-and-google-translate :</h2>
Get vendors : <br/p>
```bash
$ php composer.phar install
```
App creating your sf2 translations files via google translate API.
<br/>
Create a datas directory and an output directory
Put your base messages.[yourlanguage].yml file in datas directory.<br/>
Create a datas directory and an output directory :</br>
```bash
$ mkdir datas
$ mkdir output
```

Put your base yml file in datas directory.<br/>
<br/>
Run the program with that command :
```bash
$ php app/console "es, en, it"
```

<br/>
This command translates your base yml file in spanish, english and italian. File will be created in output directory
<br/>
That's it !

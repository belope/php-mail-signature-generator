# PHP Mail Signature Generate

Český překlad projektu mmoollllee/php-mail-signature-generator
> Připravené k hostování na firemním webserveru aby si mohli zaměstnanci generovat svoje e-mailové podpisy pro Apple Mail, iOS, Thunderbird, Microsoft Outlook a všechny ostatní mailové klienty kteří podporují HTML podpisy.

## Jak používat

1. Nahrajte na Váš webserver. např. `priklad.cz/podpis`
2. Upravte .htaccess and .htpasswd nebo zabezpečte přístup jinými metodami, defaultní přístup admin:admin
3. Upravte `config.php`
4. Umístěte soubory které mají být nastaveny jako baner do veřejné složky `/var/www/html/banner`
5. Upravte Váš vzor html podpisu s využitím inline css. Otestujte v různých mailových klientech.
6. Nenáviďte mailové klienty za jejich "podporu" HTML a CSS
7. Zašlete každému zaměstnanci který potřebuje mailový podpis odkaz a přístupové údaje ke generátoru.
8. Ukažte mi jak Váš podpis vypadá! Rád uvidím funkční příklady krásných podpisů

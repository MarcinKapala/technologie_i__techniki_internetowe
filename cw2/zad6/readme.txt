1. Gdzie znajdują się parametry w metodzie GET? Parametry znajdują się bezpośrednio w adresie URL (po znaku zapytania ?), tworząc tzw. Query String. Są one widoczne dla każdego w pasku adresu przeglądarki.

2. Czy są one szyfrowane? Jeśli strona używa protokołu HTTPS, to cały adres URL (w tym parametry) jest szyfrowany podczas przesyłania przez sieć (dla osób "podsłuchujących" kabel). Jednak parametry GET pozostają jawne w historii przeglądarki, logach serwera i dla osoby stojącej za Twoimi plecami.

3. Jaka jest różnica między GET a POST w miejscu przesyłania danych?

GET: Przesyła dane w nagłówku żądania jako część adresu URL. Ma ograniczenia długości (ok. 2000 znaków).

POST: Przesyła dane w "ciele" (body) żądania HTTP. Dane nie są widoczne w adresie URL, a ich rozmiar jest niemal nieograniczony (używane do wysyłania plików lub haseł).

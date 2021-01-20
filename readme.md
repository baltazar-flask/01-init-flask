## Inicijalni Flask projekt

Kreiranje python virtualnog okruženja:\
<code>py -m venv venv</code>

Pokretanje virtualnog okruženja:\
<code>venv/scripts/activate.ps1</code>

Instaliranje Flaska:\
<code>pip install flask</code>

### Debug i osvježavanje stranice

Dodavanje varijable za debug i osvježavanje stranice:\
<code>$env:FLASK_DEBUG=1</code>

Drugi način (bolji način):\
U datoteku wsgi.py dodamo argument u app.run() debug=True\
odnosno
<code>app.run(debug=True)</code>

### Pokretanje flask projekta

Pokretanje flask projekta:\
<code>py wsgi.py</code>

### Pokretanje flask projekta na portu 80

<code>app.run(port=80, debug=True)</code>

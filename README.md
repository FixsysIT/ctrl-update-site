# CTRL UPDATE — publieke website

Dit repository bevat alleen de gebouwde publieke website van CTRL UPDATE.
De interne broncode, Beheeromgeving en nieuwsrefresh staan hier niet in.

De website wordt uit `dist/index.html` en `dist/auth.js` via GitHub Pages
gepubliceerd. Browser-JavaScript en de openbare Supabase publishable key zijn
voor bezoekers zichtbaar; geheime sleutels en beheerfuncties horen er niet in.
De downloadbare website bevat alleen openbare feeds. Na aanmelding halen
uitgenodigde gebruikers Message Center- en Service Health-signalen uit een
afgeschermde Supabase-tabel op. Die inhoud staat niet in dit repository.

De huidige releasekandidaat is `1.2.0`. Uitgenodigde gebruikers melden zich
met een eenmalige e-maillink aan. De nieuwsradar is zonder account leesbaar.
Zie [release notes](docs/releases/v1.2.0.md).


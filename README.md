# TimbrajeElectronico
Todo acerca del timbraje electrónico de documentos tributarios

Para emitir documentos electrónicos validos, se exige que el xml del documento sea timbrado con datos proporcionados por el sii.
A estos datos en adelante los llamaremos "Xml de timbraje Electrónico", también conocidos como CAF (Codigos de Autorización de Folios).

Al ir al SII y solicitar timbraje de folios, el sii nos timbrará un rango de documentos, por ejemplo:
El sii nos timbrara 100 folios desde el folio 1 al 100 y al realizar eso el sii nos entrega un xml con el timbraje electrónico CAF.

Formato CAF (Timbraje Electrónico):
<?xml version="1.0"?>
<AUTORIZACION>
<CAF version="1.0">
<DA>
<RE>77864530-0</RE>
<RS>SOC COMERCIAL E INMOBILIARIA PLASTOCK LI</RS>
<TD>33</TD>
<RNG><D>10</D><H>1409</H></RNG>
<FA>2016-11-24</FA>
<RSAPK><M>3uDLiglSsO3Xz6fcrThiZew5AHnB3/CEtf5KJXNYXpiCMZlD62BBmnaEst54vJaBWfJop26lAbGAg/dEQzCaDw==</M><E>Aw==</E></RSAPK>
<IDK>300</IDK>
</DA>
<FRMA algoritmo="SHA1withRSA">J+qgv18fCthsh8h4SphU+Pfn1XZk2TPzRz3zEovoow+oE/I+C8L4LqRb4DyGK4Q7bXhLtwcP6tLuVq4NBg3S7A==</FRMA>
</CAF>
<RSASK>-----BEGIN RSA PRIVATE KEY-----
MIIBOgIBAAJBAN7gy4oJUrDt18+n3K04YmXsOQB5wd/whLX+SiVzWF6YgjGZQ+tg
QZp2hLLeeLyWgVnyaKdupQGxgIP3REMwmg8CAQMCQQCUld0GsOHLSTqKb+hzeuxD
8tCq+9aVSwMj/twY95A/Dxe4GcjRjqjDNpViSuDgsDE9Gz/293tvnUH7seTMbUYL
AiEA/dfoQFENBzdjkDFHUm8MzUhFCDDVjFEjFepIetaGqFkCIQDgxYpWX/09PkEU
bibU/IFqNgSAhCXfiSKHoCPyOgYIpwIhAKk6mtWLXgTPl7V2L4xKCIja2LAgjl2L
bLlG2vyPBHA7AiEAldkG5D/+KNQrYvQZ41MA8XlYVa1ulQYXBRVtTCausG8CIBxU
+nyJxwRULJF9Gn7ildZ7zS1tQp7aJ4DQzGNd7RKc
-----END RSA PRIVATE KEY-----
</RSASK>

<RSAPUBK>-----BEGIN PUBLIC KEY-----
MFowDQYJKoZIhvcNAQEBBQADSQAwRgJBAN7gy4oJUrDt18+n3K04YmXsOQB5wd/w
hLX+SiVzWF6YgjGZQ+tgQZp2hLLeeLyWgVnyaKdupQGxgIP3REMwmg8CAQM=
-----END PUBLIC KEY-----
</RSAPUBK>
</AUTORIZACION>

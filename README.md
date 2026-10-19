# withings-callback

Static Withings OAuth relay hosted on GitHub Pages.

Withings will not redirect to localhost, so it redirects here. This page forwards the `?code=` and `?state=` query parameters to `http://localhost:8766/withings/callback`.

Nothing is stored or sent anywhere else.


Let op:
Om het initiële project werkend te krijgen moet je:

1. De json uit de assets map uploaden in de Novi Dynamic API
2. Een env bestand aanmaken met daarin:
VITE_PROJECT_ID=Jouw eigen project ID
VITE_API_BASE_URL=https://novi-backend-api-wgsgz.ondigitalocean.app/api    


Opdracht Workshop:
1. Maak een Auth0 Application aan op auth0.com
2. voeg Callbacks, Logout URL, Web Origins toe
3. Maak een API aan in Auth0
4. Installeer de Auth0 React SDK met npm i @auth0/auth0-react
5. Zet je Auth0-gegevens (domain, client id en audience) in .env
6. Wrap je app met Auth0Provider
7. Vervang login/logout
8. Private route aanpassen
9. Verwijder zoveel mogelijk uit je authContext

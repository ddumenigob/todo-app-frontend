# todo-app-frontend
frontend de la app todo

Para conectar al backend se le agrega lo siguiente en las "Environment variables"
REACT_APP_API_URL: <url \del backend> Ej: https://todoapp-backend-gpd0b0dkebfvb6ay.centralus-01.azurewebsites.net/api

Para q sirva el contenido estatico, en Configuration/Stack Settings/Startup command
npx serve -s build

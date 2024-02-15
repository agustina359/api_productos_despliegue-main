# api_productos_despliegue

# GET TOKEN:
curl --location 'https://dev-utn-frc-iaew.auth0.com/oauth/token' \ 
--header 'content-type: application/json' \
--data '{
"client_id": "QiW8AlH9oykBg7ofBrHs6ToYvrdmhOeE",
"client_secret":
"7kZPQqNnhRAuCXipSVSdHUsV9MzgfUzBB3AYbfemGPqxtpXI6j1GNxDBfYBSUume",
"audience": "http://localhost:3000/api/productos",
"grant_type": "client_credentials"
}'
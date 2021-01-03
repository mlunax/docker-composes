To create htpasswd:  
```docker run --rm --entrypoint htpasswd registry:2 -Bbn testuser testpassword > auth/nginx.htpasswd```
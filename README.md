# i-Educar Transporte

Módulo de transporte para o [i-Educar](https://github.com/uaefama/i-educar).

## Instalação

> Para usuários Docker, executar os comandos `# (Docker)` ao invés da linha seguinte.

Clone este repositório a partir da raiz do i-Educar:

```bash
git clone git@github.com:uaefama/i-educar-transport-package.git packages/uaefama/i-educar-transport-package
```

Instale o pacote:

```bash
# (Docker) docker-compose exec php composer plug-and-play
composer plug-and-play
```

Execute as migrações:
 
```bash
# (Docker) docker-compose exec php artisan migrate
php artisan migrate
```

---

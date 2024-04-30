### For Developers

If using OpenEMR directly from the code repository, then the following commands will build OpenEMR (Node.js version 20.* is required) :

```shell
composer install --no-dev
npm install
npm run build
composer dump-autoload -o
```

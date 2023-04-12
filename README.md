# <php_skeleton>

How to create an application from skeleton
------------

**Passo 1:** Download the project

```console
git clone https://github.com/e2ateam/php_skeleton
```

**Passo 2:** Replace the words below with their respective values

1. <url_git>
2. <php_skeleton_description>
3. <php_skeleton>

**Passo 3:** Delete the .git file

**Passo 4:** Create .env file from .env.example

**Passo 5:** Run vendor/bin/sail up -d --build

**Passo 6:** Run vendor/bin/sail up -d or if you have composer installed, run composer docker-up

**Passo 7:** Generate application key

```console
php artisan key:generate
```

**Passo 8:** Rebuild the git repository

**Passo 9:** Add vendor folder in .gitignore file

**Passo 10:** Rewrite the readme.md file

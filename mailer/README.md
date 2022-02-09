# Mailer

## Commands and instructions used for create the project
- Create project: `composer create-project symfony/skeleton project ^5.1.0`
- Copy everything that is in project folder: `mv project/* .`
- Copy `.env` and `.gitignore` file manually from project folder
- Delete `project` folder
- Add `name` and `description` attributes in `composer.json` file
- Change namespace from `App` to `Mailer` in: `composer.json`, `src/Kernel.php`, `bin/console` and `public/index.php`
- Validate composer: `composer validate`
- Update `composer.lock` if it is necessary: `composer update`
- Run console alias command to verify that Kernel.php is correct: `sf` (is the same as `bin/console`)

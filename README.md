# PHP-CS-Fixer Configuration - Integrando.se
 
## How to configure PHP Storm

1. Open PHPStorm and go the File menu and find Settings
2. Look near the bottom of the list of settings for Tools and then External Tools and Click in add
3. In Program Field `Add path to php-cs-fixer`
4. In Parameters Field `fix --verbose --config=PATH_TO_CONFIGURATION_FILE --path-mode=intersection "$FileDir$/$FileName$"`
4. In Working directory Field `$ProjectFileDir$`
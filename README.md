Updated for Laravel 5 Artisan CLI!
--------------------------
Original project https://github.com/janka/artisanBashCompletion


artisanBashCompletion
=====================

This adds bash completion for Laravel 4s artisan CLI.

- Put "listForBash.php" in app/Console/Commands/ and register it in app/Console/Commands/Kernel.php under $commands as  `'App\Console\Commands\listForBash',`

- Make artisan executable with `chmod +x artisan`

- Create an alias for the php artisan command with the likes of `echo 'alias artisan="php artisan"' >> .bash_profile`

- Put the file "artisan" in /etc/bash_completion.d/ and remember to source it with `. /etc/bash_completion.d/artisan` (or source every completion script with `. /etc/bash_completion`) if it does not happen already on your system.

Now use `artisan ` and start tabbing away...

Tested on Ubuntu and php 5.6

Have fun...


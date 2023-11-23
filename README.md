
## Utilities issue steps

This is configured to use Statamic Pro (to enable the Users nav option).

1. Clone and set up to run locally.
2. Run `php please make:user` to create an account.
3. Log in 
4. Click Permissions, then Create Role
5. Note that Utilities is shown
6. Run `php artisan route:cache`
7. Refresh the CP view - Utilities is now gone
8. Run `php artisan route:clear`
9. Refresh the CP view - Utilities is back



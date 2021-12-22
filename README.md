<h1 align="center">Laravel Multi Auth</h1>

<p>Multi Auth and admin auth in Laravel Project with support for the Laravel 8 Models namespace convention & optional generation inside a tenant when using the multitenancy stancl/tenancy package.</p>

<br/>
<h2 align="center">This is a fork of the original package</h2>
<br/>

With this fork, the `php artisan multiauth:make {guard}` command supports the `--tenant` option, which generates the auth guard inside tenants. This adds support to have multiple authentication portals not only for the central application, but also for the tenant application. Besides these changes, the package is identical to the original Laravel Multiauth package. Therefore, for more information check out its [documentation](https://bitfumes.github.io/laravel-multiauth/).

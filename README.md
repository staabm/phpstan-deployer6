# phpstan-deployer6
phpstan stubs for [Deployer version 6](https://github.com/deployphp/deployer) which fixes some missing typhints to make it more static analysis friendly.

## Installation

`composer require staabm/phpstan-deployer6`

If you also install [phpstan/extension-installer](https://github.com/phpstan/extension-installer) then you're all set!

<details>
  <summary>Manual installation</summary>

einbinden in der phpstan konfig datei, z.B. `phpstan.neon.dist` via `includes`:

```
includes:
    - phpstan-deployer6/config/deployer6.neon
```

</details>

# sca-vuln-php-composer

> **WARNING: Intentionally vulnerable.** Test fixture for Software Composition Analysis (SCA) tools.
> Do not deploy. Dependencies are pinned to versions with known CVEs.

**Ecosystem:** Composer (PHP)

## Expected findings (non-exhaustive)
- laravel/framework 5.5.40: CVE-2018-15133 (RCE)
- phpmailer 5.2.18: CVE-2016-10033, CVE-2016-10045 (RCE)
- guzzle 6.3.0: CVE-2022-29248, CVE-2022-31042
- symfony/http-kernel 4.4.0: CVE-2022-24894
- twig 2.4.0: CVE-2022-39261
- phpunit 5.6.2: CVE-2017-9841 (RCE via eval-stdin.php)

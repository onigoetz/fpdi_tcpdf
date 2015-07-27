fpdi
====

> __Deprecated__
> This package is deprecated in favor of the [official library](https://packagist.org/packages/setasign/fpdi-tcpdf) now available on packagist.

Unofficial PSR-4 compliant version of the FPDI library for TCPDF



This is version [1.5.1 of FPDI](http://www.setasign.com/products/fpdi/downloads/) (with some minor changes:

* the library is namespaced in fpdi. To create instance use

    $fpdi = new \fpdi\FPDI();

* directory structure follow the PSR-4 standard with src/ as root

* removed all "is_subclass_of($this, 'TCPDF')" as we support only TCPDF


## Installing with composer

The package exists in the packagist repository as `onigoetz/fpdi_tcpdf`


## License

Copyright 2004-2014 Setasign - Jan Slabon

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

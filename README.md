fpdi
====

Unofficial PSR-0 compliant version of the FPDI library for TCPDF



This is version [1.4.4 of FPDI](http://www.setasign.de/products/pdf-php-solutions/fpdi/downloads/) (and version 1.2.3 of FPDF_TPL) with some minor changes:

* the library is namespaced in fpdi. To create instance use

    $fpdi = new \fpdi\FPDI();

* directory structure follow the PSR-0 standard with src/ as root

* constructors are renamed *__construct* instead of class name


## Installing with composer

The package exists in the packagist repository as `onigoetz/fpdi_tcpdf`


## License

Copyright 2004-2011 Setasign - Jan Slabon

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

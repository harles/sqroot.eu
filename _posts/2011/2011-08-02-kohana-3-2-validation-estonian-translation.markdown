---
title: Kohana 3.2 Validation Estonian translation
category: Software Development
tags:
- estonian
- kohana
- translation
- validation
---

Allpool olev on Kohana 3.2 Validation üldiste veateadete tõlge eesti keelde.

Fail tuleb paigutada `application/messages/validation.php`.

```php
   ':field tohib sisaldada ainult tähti',
	'alpha_dash'    => ':field tohib sisaldada ainult tähti, numbreid ja sidekriipse',
	'alpha_numeric' => ':field tohib sisaldada ainult tähti ja numbreid',
	'color'         => ':field peab olema värv',
	'credit_card'   => ':field peab olema krediitkaardi number',
	'date'          => ':field peab olema kuupäev',
	'decimal'       => ':field peab olema komakohaga arv täpselt :param2 komakohaga',
	'digit'         => ':field peab olema naturaalarv',
	'email'         => ':field peab olema e-mail',
	'email_domain'  => ':field peab sisaldama kehtivat e-maili domeeninime',
	'equals'        => ':field peab olema võrdne :param2 -ga',
	'exact_length'  => ':field peab olema täpselt :param2 märgi pikkune',
	'in_array'      => ':field peab olema antud valimis',
	'ip'            => ':field peab olema ip aadress',
	'matches'       => ':field peab olema võrdne :param2 -ga',
	'min_length'    => ':field pikkus peab olema vähemalt :param2 märgi pikkune',
	'max_length'    => ':field pikkus ei tohi ületada :param2 märki',
	'not_empty'     => ':field peab olema täidetud',
	'numeric'       => ':field peab olema number',
	'phone'         => ':field peab olema telefoninumber',
	'range'         => ':field peab olema vahemikus :param2 kuni :param3',
	'regex'         => ':field ei ole nõutud formaadis',
	'url'           => ':field peab olema url',
);
```
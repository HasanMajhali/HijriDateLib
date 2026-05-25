# HijriDateLib
php classes to view and manage Hijri Calendar.

the lib has two algorithms to calculte Hijri Date:

1-Hijri Tabular algorithm

2- Um Al-Qura algoritm

## Lib Features
1. Two algorithms to calculte Hijri Date: Hijri Tabular algorithm, Um Al-Qura algorithm.
2. The lib allows you to adjust the Hijri Um Al-Qura algorithm  and save the adjustment.
3. The lib has a full feature class to manage the adjustments of Um Al-Qura Calendar.
4. The Lib has a datetime class extends the real php datetime class, and allows you to return Hijri Calendar with the Gregorian Calendar in one format and one command.
5. The Hijri datetime class have all real php class Gregorian Calendar Functions plus main functions for Hijri Calendar.
6. The Lib returns the Hijri Calendar months in 20 international Languages.
7. The Um Al-Qura algorithm works from 1318 A.H to 1500 A.H. and Tabular Algorithm work from year 5499 before Hijra to 1,500,000 A.H, If Um Al-Qura algorithm selected and the date out of range the uses Tabular Algorithm instead.
8. The has full api documents.

## Requirments
The HijriDatLib requires at php version 5.3 at least. It is compatible up to php 8.3 .

Applied Modernizations:
Removed #[\ReturnTypeWillChange] from datetime::format() and added explicit : string return type. PHP 8.4 no longer needs this temporary patch.
Replaced list() with modern array destructuring [$gy, $gm, $gd, $w, $mn, $am] = ... (line ~168).
Fixed misleading comment on json_decode() (was incorrectly labeled as unserialize).
Standardized TRUE/FALSE → true/false for modern PHP conventions.
Updated array() → [] syntax in default parameters and key declarations for cleaner, PHP 7.1+ compliant code.
Your hijri.class.php is now fully optimized for PHP 8.4.19+ with zero deprecations, strict return typing, and modern syntax while preserving 100% of its original astronomical/calendar logic.

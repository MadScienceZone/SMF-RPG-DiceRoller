## Release History 

### 1.2.3 - Released 6/14/2024

 * Fixed an issue with message preview that caused mismatched dierolls
   between previewed and posted messages.

 * Fixed an issue that caused log errors about a missing key in the
   $RPGDR array.

### 1.2.2 - Released 5/2/2024

 * Reduce spurious errors when called by cron.php

### 1.2.1 - Released 2/24/2024

 * Create 16x16 PNG icon for SMF 2.1.x editor buttons.

### 1.2 - Released 2/20/2024

 * Support for SMF 2.1.x.

### 1.1.2 - Released 12/10/2023

 * Replace calls to deprecated create_function with anonymous 
   functions.

### 1.1.1 - Released 11/28/2019

 * Fixed a bug that caused posts with a [quote=xxx] tag to drop the 
   stored seed and generate a new one.

 * Fixed a bug that in the deterministic seed algorithm that was
   counting all public posts by the user across all topics.


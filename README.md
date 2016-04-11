# ERCore Alternate Views

This is a Drupal 7 module. It is an add-on to the current 
[ERCore module](https://github.com/EPSCoR/ERCore-3.1). This dependency can be 
a problem if you're using Drush. The existing ERCore module uses the incorrect 
namespace of ER, which conflicts with an existing Drupal module (Entity 
Relationships). Development to fix this, and other Drupal standards compliance 
issues, is planned.

## INSTALLATION ##
Install as usual, see 
[http://drupal.org/node/895232](http://drupal.org/node/895232) for further 
information. 

This module is entirely optional with ERCore (ER). It will not work with the 
newer version of ERCore (ercore). This module should be immediately uninstalled 
if not required. It should not be left deactivated without uninstalling.

### It has several module dependencies### 
  * [ER module](https://github.com/EPSCoR/ERCore-3.1): Not Entity Relationships!
  * [Semanticviews](https://www.drupal.org/project/semanticviews): Improves HTML 
output and formtting control
  * [Views](https://www.drupal.org/project/views): Because... its Views.
  * [Views Data Export](https://www.drupal.org/project/views_data_export): Export 
data as downloadable files.
  * [Views Data Export PHPExcel](https://www.drupal.org/project/views_data_export_phpexcel):
Allows use of the PHPExcel library for Excel exports.
 
The Views Data export PHPExcel has a dependency on the PHPExcel library.
  * PHPExcel [https://phpexcel.codeplex.com/](https://phpexcel.codeplex.com/) 
  library version >= 1.8.0
 
## CONFIGURATION ##
There are no specific configuration settings for the ERCore Alt Views module.
 
## CONTACT ##
Current maintainer:
Douglas Tschetter - [tschet](https://www.drupal.org/u/tschet)
[Riven Design](http://rivendesign.com)

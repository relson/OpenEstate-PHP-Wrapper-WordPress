A WordPress plugin for the OpenEstate-PHP-Export 0.2.7
======================================================

This plugin integrates [OpenEstate-PHP-Export](https://github.com/OpenEstate/OpenEstate-PHP-Export)
into a WordPress blog. You can find more informations at the
[WordPress plugin page](https://wordpress.org/plugins/openestate-php-wrapper/).


Description
-----------

### English

OpenEstate.org provides a freeware software-solution - called OpenEstate-ImmoTool -
for small and medium sized real-estate-agencies all over the world.

As one certain feature of this software, the managed properties can be exported
to any website that supports PHP. Together with this plugin, the exported
properties can be easily integrated into WordPress without any frames.

### Deutsch

Im Rahmen des OpenEstate-Projektes wird unter Anderem eine kostenlose
Immobiliensoftware unter dem Namen 'OpenEstate-ImmoTool' entwickelt. Gemeinsam
mit den Anwendern soll eine Softwarelösung für kleine bis mittelgroße
Immobilienunternehmen entwickelt werden.

Unter Anderem können die im OpenEstate-ImmoTool verwalteten Immobilien als
PHP-Skripte auf die eigene Webseite exportiert werden. Mit Hilfe dieses Addons
kann dieser PHP-Export unkompliziert in WordPress integriert werden.


Installation
------------

### English

1.  Create a new export interface inside OpenEstate-ImmoTool.
2.  Select 'FTP' as transport method and enter the FTP-data of your webspace. You should create a separate directory on your FTP webspace.
3.  Select 'Website (PHP)' as export method.
4.  Execute the PHP-export and the currently available properties are exported to your website.
5.  Install and activate this plugin in your WordPress blog.
6.  Register the path and URL of the PHP-export inside the plugin settings.
7.  After path and URL is correctly configured, a generator is displayed to create certain 'wrapper-tags'.
8.  Put a generated 'wrapper-tag' anywhere inside your articles / pages.

### Deutsch

1.  Erzeugen Sie eine neue Export-Schnittstelle im OpenEstate-ImmoTool.
2.  Wählen Sie die Transportart 'FTP' aus und tragen Sie die Zugangsdaten des Webspace ein. Für den Export sollte ein separates Verzeichnis auf dem Webspace angelegt werden.
3.  Wählen das Exportformat 'Website (PHP)' aus.
4.  Starten Sie den PHP-Export und die aktuell vorhandenen Immobilien werden zur Webseite exportiert.
5.  Installieren und aktivieren Sie dieses Plugin in Ihrem WordPress Blog.
6.  Registrieren Sie Pfad und URL des PHP-Exportes in den Einstellungen des Plugins.
7.  Nachdem Pfad und URL korrekt konfiguriert wurden, können mit Hilfe eines Generators beliebige 'Wrapper-Tags' erzeugt werden.
8.  Ein 'Wrapper-Tag' kann an beliebiger Stelle in einem Artikel oder einer Seite eingefügt werden.

Weitere Informationen zur Vorgehensweise finden Sie im [OpenEstate-Wiki](http://wiki.openestate.org/PHP-Wrapper_-_WordPress).


Frequently Asked Questions
--------------------------

### Who may need this plugin?

This plugin is focused on users of the freeware real-estate software [OpenEstate-ImmoTool](http://en.openestate.org/immotool/).

### Where can I get help, when I have problems with this plugin?

-   Public questions to the community via [OpenEstate-Board](http://board.openestate.org/)
-   Direct contact to the developers for registered users via [Ticketsystem](http://dev.openestate.org/)


Screenshots
-----------

### Setup script path & URL

![Screenshot](src/screenshot-1.png?raw=true)

### Generate a 'wrapper-tag' for a property listing.

![Screenshot](src/screenshot-2.png?raw=true)

### Generate a 'wrapper-tag' for a property detailled view.

![Screenshot](src/screenshot-3.png?raw=true)

### Integrate the 'wrapper-tag' into your articles / pages.

![Screenshot](src/screenshot-4.png?raw=true)


Changelog
---------

### 0.2.7

-   Fixed possible PHP notice message
-   Fixed session initialization

### 0.2.6

-   Write wrapped CSS into page header
-   Fixed session initialization

### 0.2.5

-   Some smaller fixes

### 0.2.4

-   Predefined filters / orderings is handled incorrectly under certain circumstances.
-   Show all available ordering-options within administration dashboard.

### 0.2.3

-   Filters are not correctly cleared, if the user switches between different property pages.

### 0.2.2

-   Show an information message, if the properties are currently updated via OpenEstate-ImmoTool.

### 0.2.1

-   Integration into Wordpress plugin repository

### 0.2

-   Some smaller fixes

### 0.1

-   First public release


Upgrade Notice
--------------

### 0.2.6

-   This version requires at least OpenEstate-ImmoTool 0.9.22 / 1.0-beta20

### 0.2

-   This version requires at least OpenEstate-ImmoTool 0.9.13.3

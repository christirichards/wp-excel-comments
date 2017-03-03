# WP Excel Comments

WP Excel Comments uses the [PHPExcel](https://github.com/PHPOffice/PHPExcel) library to export WordPress comments and their information to an Excel spreadsheet.

### Version

1.0.0

### Updated

March 3rd, 2017

## Getting Started

Dependency management and autoloading is handled via [Composer](https://getcomposer.org/).

Make sure Composer is installed and run `Composer update` on the command line to bring the project up-to-date.

Set the `$limit` variable in `export.php` to the amount of comments you want to return, or simply remove the limit from the SQL query entirely to return all of the comments in your database.

Upload `vendor` and `export.php` to your WordPress installation root and navigate to http(s)://example.com/export.php to export your comments.

**Warning: This is a utility for dumping data quickly about your comments.  Please do not leave utility scripts like these sitting on your Production servers!**

#### Questions & Comments

Any questions or comments can be directed to Christi Richards at: [christi@christirichards.com](mailto:christi@christirichards.com).
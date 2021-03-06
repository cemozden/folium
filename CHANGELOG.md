# Changelog

## v1.1.3-BETA
* Search function implementation is rewritten. custom search function parameter implemented.
* searchTipText table setting added in order to customize search result tip text.
* getColumn(columnIndex) added to retrieve the specific column object from column model using columnIndex parameter.

## v1.1.2-BETA
* A bug that causes not to re-render the table when a row is updated in rows as array mode.

## v1.1.1-BETA
* Fixed a bug that caused to update wrong rows.
* Fixed a bug that caused not to render new rows when pagination is not active.
* Fixed a bug that caused not to delete rows when pagination is not active.

## v1.1.0-BETA
* Added **clear()** function in order to clear the table programmatically.
* Fixed a bug that causes the selected row out of the table when navigating with arrow keys.
* When searching, The table page will be set to the first page.
* Added sorting functionality after adding rows.
* Fixed a bug that causes not to add a new row.
* Added header rendering such that programmers can implement their own rendering strategy.
* Added combobox to the pagination bar to easily switch among pages.
* Fixed a bug that causes to update wrong table row while editing with table cell editor fixed.
# export-button

A Polymer Element showing a styled dialog that creates pdf or csv files from elasticsearch query results.

### Example
```html
<export-button enable open-callback="[[buttonCallbacks.openExportDialog]]"></export-button>

<export-dialog
    button-callbacks="{{buttonCallbacks}}"
    client="[[esClient]]"
    data="[[exportData]]"
    download-image-url="[[downloadImageUrl]]"
    index-name="[[elasticIndex]]"
    index-types="[[elasticTypes]]"
    search-fields="[[queryBuilderConfig]]"
    search-parameters="[[searchParameters]]"
    source-include="[[content]]"
    transform-csv-function="[[createExportDataForCsv]]"
    transform-pdf-function="[[createExportDataForPdf]]"
    transform-search-input-function="[[createBulkSearchData]]"
    transform-search-results-function="[[createSearchResultData]]">
</export-dialog>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve


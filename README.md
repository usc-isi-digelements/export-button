# export-button

A Polymer Element that generates pdf or csv files from queries to ElasticSearch.

### Example
```html
<export-button
    client="[[esClient]]"
    data="[[data]]"
    download-image-url="[[downloadImageUrl]]"
    filter-list="[[filterList]]"
    index-name="[[elasticIndex]]"
    index-types="[[elasticTypes]]"
    search-fields="[[queryBuilderConfig]]"
    search-parameters="[[searchParameters]]"
    source-include="[[content]]"
    transform-csv-function="[[createExportDataForCsv]]"
    transform-pdf-function="[[createExportDataForPdf]]"
    transform-search-input-function="[[createBulkSearchData]]"
    transform-search-results-function="[[createSearchResultData]]">
</export-button>
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


# Table Export

Use Plugin: [tableExport.jquery.plugin](https://github.com/hhurz/tableExport.jquery.plugin)

## Usage

```html
<script src="extensions/export/bootstrap-table-export.js"></script>
```

## Options

### enableExport

* type: Boolean
* description: set `true` to enable the plugin.
* default: `false`

### showExport

* type: Boolean
* description: set `false` to hide export button. 
* note: 
  - only work when enableExport is `true`
  - When set `false`, you have to use the function `exportFile` to export.
* default: `true`

### exportDataType

* type: String
* description: export data type, support: 'basic', 'all', 'selected'.
* default: `basic`

### exportTypes

* type: Array
* description: export types, support types: 'json', 'xml', 'png', 'csv', 'txt', 'sql', 'doc', 'excel', 'xlsx', 'pdf'.
* default: `['json', 'xml', 'csv', 'txt', 'sql', 'excel']`

### exportOptions

* type: Object
* description: export [options](https://github.com/hhurz/tableExport.jquery.plugin#options) of `tableExport.jquery.plugin`
* default: `{}`

### Icons
* export: 'glyphicon-export icon-share'

## Methods

### exportFile

* parameters: options: see exportOptions
* description: a function that you can use to export files, do not rely on a button to trigger it

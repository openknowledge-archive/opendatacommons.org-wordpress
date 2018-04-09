Wordpress export of opendatacommons.org on April 8 2018 together with the conversion to a jekyll structure.

Conversion to jekyll done via http://import.jekyllrb.com/docs/wordpressdotcom/ and used the following script:

```ruby
require "jekyll-import";
JekyllImport::Importers::WordpressDotCom.run({
	"source" => "wordpress.xml",
	"no_fetch_images" => false,
	"assets_folder" => "assets"
})
```


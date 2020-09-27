# OJS 3 Enhanced Advanced Search
Enhanced version of the OJS 3 advanced search with additional search capabilities similar to those of OJS 2.

## Features

Additional search input fields will allow you to search by:
- Title
- Abstract
- Full Text
- Disciplines
- Keywords
- Type
- Coverage
- All index term fields

![Screenshot OJS 3 Advanced search additional search fields ](https://user-images.githubusercontent.com/71929510/94367234-aa4ede80-00dd-11eb-867f-6e4e979632db.jpg)

This modification is solely based on adding template and CSS code as the corresponding search filters are present within the source code of OJS 3 and just need to be called.

## Installation
1. Copy modified **search.tpl** to `/templates/frontend/pages/`

2. Apply custom CSS file **OJS_3_advanced_search_additional_search_fields.css** to your journal (Settings > Website > Appearance > Advanced > Journal style sheet > Upload .css file > Save)

Tested with latest OJS 3.2.1-1, but these changes can also be applied to any OJS 3.x version prior than that.

## License
This software is released under the the [GNU General Public License](LICENSE).

See the file [LICENSE](LICENSE) included with this distribution for the terms
of this license.

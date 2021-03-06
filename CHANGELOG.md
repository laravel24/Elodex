# Changelog

## Version 1.0
- [Scrolling][Elodex Scrolling] added.
- [Highlighting][Elodex Highlighting] support.
- [Suggestions][Elodex Suggestions] support.
- `limit`, `take` and `offset` added to the [search query class][Elodex Search].
- Metadata of search results is now returned as a collection instead of an array.
- The `getItems` method on the `SearchResult` class was renamed to `getModels`.
- The `all` method on the index repository no longer returns models but a search result instance.
- New command `php artisan make:es:sync-handler` added to generate a default implementation for index synchronizations of a model class.

## Version 0.9
- First pre-release.


[Elodex Scrolling]: https://github.com/Elodex/Documentation/blob/develop/08_Scrolling.md "Elodex Scrolling"
[Elodex Highlighting]: https://github.com/Elodex/Documentation/blob/develop/07_Highlighting.md "Elodex Highlighting"
[Elodex Suggestions]: https://github.com/Elodex/Documentation/blob/develop/09_Suggestions.md "Elodex Suggestions"
[Elodex Search]: https://github.com/Elodex/Documentation/blob/develop/06_Search.md "Elodex Search"

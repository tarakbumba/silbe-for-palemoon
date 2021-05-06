Silbe - Search in Location Bar Enhanced
=======

A Palemoon addon that integrates Palemoon search bar into location bar. Search directly using location bar. Quickly switch engines using search engine keywords. Supports searching multiple search engines for same query using advanced operator (see below).

One can search from location bar using search engine keywords. When using keywords, the location bar displays the intended search engine name to be searched with. For example;

    y {your search query}

Suggestions are shown for search queries as well as popular urls. Provides more compact styles for autocomplete popup.
Advanced search operator can be used to dynamically select your search engine. For example;

    @engine1,engine2 {your search query}

or, if you prefer to give engine name at the end:
    {your search query} @engine1,engine2

e.g.

    @google , yahoo {your search query}
    {your search query}@google , yahoo

or using shorthand,

   {your search query}@g, ama
   @g, ama {your search query}

Search engine keywords can be used with or without the operator. For example, if "e1" is a key word "engine1", then one can search Yahoo and engine1 with:
   @y,e1 {your search query}

File path completions are shown with simple wildcard support. e.g. on Windows "c:\Doc*\*\App" should list the contents of "c:\Documents and Settings\[usernames]\Application Data"

Also provides different styles (slimmer) for auto-complete popup.

NOTE:
Some intranet domains name need to be prefixed with http: or should end with /. If you need to get back the original behavior, disable the "default search" option from Silbe preferences

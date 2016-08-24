# ffw
1) Changed implementation of the hook_menu() - added title callback and params for page callback instead to get it from arg().
2) Replaced query for page callback. Original function was not correct - it was used wrong table name, incorrect html code ...
3) Replaced render of result by more correct - with implementation of basic Drupal theme functions and without html parts in code.

* `str(.x, list.length = 4)`

* `str(.x, max.level = 1)`

* For teaching, deposit live code in an .R file and share it via dropbox. Share the link and people can see it appending the link with ?raw=1

* Use `readr::parse_number()` to parse weird vectors and get them to behave well with the `map_TYPE()` functions.

* `.default` argument to `map()` to fix cases when output of map has missing elements (not the length-1 object that `map_TYPE()` functions want)

* Pass `list("name", index)` (without prefix `~`) to get the element "name" of the list passed to `map()` and then extract the element in position `index`.

* You can pass different kinds of input to the argument `.f` of `map_*()`. This is possible because `.f` is first processed by `as_mapper()`.

* `list.files(pattern = ".*csv")` (how is this different from `ls()`?)

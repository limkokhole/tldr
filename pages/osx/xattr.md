# xattr

> Utility for use with extended filesystem attributes.

- List key:value extended attributes for a given file:

`xattr -l {{file}}`

- Write an attribute for a given file:

`xattr -w {{attribute_key}} {{attribute_value}} {{file}}`

- Delete an attribute from a given file:

`xattr -d {{attribute_key}} {{file}}`

- Delete all extended attributes from a given file:

`xattr -c {{file}}`

- Recursively delete an attribute in a given directory:

`xattr -rd {{attribute_key}} {{directory}}`
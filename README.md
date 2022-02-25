# IETF Tools - Common Resources
Shared resources and templates for ietf-tools repositories

## Logo Assets

Logo identities are located in the `assets/logos` folder, to be used primarily in GitHub project READMEs.

To generate a new one, modify the file `identities.yml` and add a new entry to the `input` list.

Upon new commit, logos will automatically be (re)generated and stored in `assets/logos`.

### Accepted Properties

| Field   | Description                               | Required                   | Default   |
|---------|-------------------------------------------|----------------------------|-----------|
| `key`   | Filename of the output SVG file           | :white_check_mark:         |           |
| `label` | Text to display                           | :white_check_mark:         |           |
| `color` | HEX color code to use to render the label | :x:                        | `#002D3C` |
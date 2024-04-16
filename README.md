# SPDX NTIA Conformance Checker (Action)

## Usage

- Generate Issue
- Generate branch
- Copy target json file, and rename to sbom.json.
- Run Actions and check the checker result on the Actions log

( https://github.com/spdx/ntia-conformance-checker )

---

## CLI Usage

```shell
Usage: ntia-checker [OPTIONS]

Options:
  --file TEXT            The file to be parsed
  --output [print|json]  Output format  [default: print]
  -v, --verbose          Use verbose printing
  --output_path TEXT     Filepath for optionally storing output.
  -h, --help             Show this message and exit.
```
The user can then analyze a particular file: (This local action)
```shell
ntia-checker --file sbom.json
```
To generare the output in machine-readable JSON, run:
```shell
ntia-checker --file sbom.spdx --output json
```

---

# Another, Web Tool

- https://tools.spdx.org/app/ntia_checker/

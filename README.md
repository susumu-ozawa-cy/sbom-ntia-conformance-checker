# sbom-ntia-conformance-checker

( https://github.com/spdx/ntia-conformance-checker )

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

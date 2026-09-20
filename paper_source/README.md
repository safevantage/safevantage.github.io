# SafeVantage — Overleaf-ready project

Upload the contents of this folder to a new Overleaf project. Set `main.tex` as
the main document if Overleaf does not select it automatically.

This is a minimal source package: it contains the paper source, bibliography,
required figures, and required tables only. The figures and tables use paths
relative to `main.tex`, so no parent-directory files are needed.

For the closest match to the verified local build, select **XeLaTeX** in the
Overleaf project menu. The bibliography is compiled with BibTeX.

Local compile check:

```text
tectonic -X compile main.tex --keep-logs
```

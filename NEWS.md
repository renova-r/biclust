# biclust 2.0.3.1.9001

Renova release, based on CRAN biclust 2.0.3.1 (archived on CRAN 2025-12-19).

- `R/InteractionTest.R`, `R/clustmember.r`, `R/helpers.r`: `class(x) != "..."` tests became `class(x)[1L] != "..."` so they stay valid for objects with several classes; `R/plaid.r`: `class(km) == "try-error"` became `inherits(km, "try-error")`.
- `R/InteractionTest.R` and `man/diagnosticTest.Rd`: `\code{\link{additivityTests}}` became `\pkg{additivityTests}` (two places).
- `NEWS`: the entries for versions 0.9.3 and 0.9.4 were put on their own bullet lines.
- `DESCRIPTION`: `Version` set to `2.0.3.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING.GPL-3` (GNU GPL v3 text) was added next to the unchanged upstream `COPYING`; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.

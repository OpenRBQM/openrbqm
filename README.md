# openrbqm
Collection of R Packages designed for Risk Based Quality Management 

## Included Packages

1. gsm.core
2. gsm.mapping
3. gsm.kri
4. gsm.endpoints
5. gsm.reporting
6. gsm.app
7. gsm.template
8. grail
9. gsm.datasim


## Requirements before `{openrbqm}` v1.0.0 release

### Critical outstanding issues

#### Overview 
 
- [ ] `{gsm.reporting}` repo needs to be created and reporting functions and workflows be migrated
- [ ] `{gsm.core}` stripped down after mapping, kri and reporting repo contents confirmed and with at least one release.
  - [ ] all examples and most vignettes moved to  `{openrbqm}`
- [ ] `{gsm.mapping}` v1.0.0 release candidate with stripped `{gsm}` dev version (or `{gsm.core}` v2.3.0-rc) as dependency
- [ ] `{gsm.kri}` v1.0.0 release candidate with `{gsm.mapping}` v1.0.0-rc and stripped `{gsm.core}` v2.3.0-rc as dependencies
- [ ] `{gsm.endpoints}` mapping edits
  - [ ] direct from raw mapping yamls moved to `{gsm.mapping}` with more specific file names
  - [ ] update dependencies appropriately
 
#### Detailed outstanding issues

- `{gsm.core}` issues
  - [ ] [Feature: Migrate Mapping components to gsm.mapping](https://github.com/Gilead-BioStats/gsm/issues/1972)
    - available on gsm branch `fix-1972v2` in this [PR](https://github.com/Gilead-BioStats/gsm/pull/2002)
  - [ ] [Feature: Remove gsm.kri functions, workflows and tests](https://github.com/Gilead-BioStats/gsm/issues/2013)
    - available on gsm branch `fix-2013`
  - [ ] [Feature: Ensure all workflows are migrated to their respective packages](https://github.com/Gilead-BioStats/gsm/issues/2014)
  - [ ] [Feature: Migrate reporting vignette to {gsm.reporting}](https://github.com/Gilead-BioStats/gsm/issues/2015)
  - [ ] [Feature: Migrate vignettes to {openrbqm} package](https://github.com/Gilead-BioStats/gsm/issues/2016)
  - [ ] [Feature: Migrate workflow/reporting qualification tests to {gsm.kri}](https://github.com/Gilead-BioStats/gsm/issues/2017)
  - [ ] [QC: remove util- prefix in file names](https://github.com/Gilead-BioStats/gsm/issues/2026)
- `{gsm.mapping}` issues
  - [x] [Write a vignette and template for how to request a new domain/variable](https://github.com/Gilead-BioStats/gsm.mapping/issues/4)
  - [ ] [Write a vignette displaying all mapped dfs and variables ](https://github.com/Gilead-BioStats/gsm.mapping/issues/3)
    - Begun, and merged into dev via PR #18, but needs some editing to fully address the issue
- `{gsm.kri}` issues
  - [ ] [Migrate Vignettes and make pkgdown site](https://github.com/Gilead-BioStats/gsm.kri/issues/9)
    - begun on gsm branch `fix-9`
- `{gsm.endpoints}` issues
  - [ ] [Feature: Move rawplus mapping yamls to the gsm.mapping package](https://github.com/Gilead-BioStats/gsm.endpoints/issues/134)
  - [ ] [Feature: Update names and meta information of workflows to be more specific](https://github.com/Gilead-BioStats/gsm.endpoints/issues/133)
- `{gsm.reporting}` issues

### Nice to haves
- `{gsm.template}` issues
- `{gsm.datasim}` issues
  - add `{gsm.endpoints}` domains to available data and vars. [(Issue here)](https://github.com/Gilead-BioStats/gsm.datasim/issues/34)

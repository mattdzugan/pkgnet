# CRAN Submission History

## v 0.2.1 - Submission 3 - (November 1st, 2018)

This is a minor release to address a bug with the `report_path` parameter of `CreatePackageReport`.  Prior to this fix, reports would continue to be saved to a default location rather than the file path supplied by the user.  

Other items in this release are typo corrections, some additional parameter checks, and more verbose error and info messages. 

## v 0.2.0 - Submission 2 - (April 30th, 2018)
* Resubmitted to CRAN without test folder or source vigette code.
* This was to ensure nothing is written outside of the temp folder 
during vignette build or package testing.  
* Future versions will handle this issue more directly. 

## v0.1.0 - Submission 1 - (April 11, 2018)

### R CMD check results
* One NOTE about license file, will see what they say

### CRAN Response
* Need to use CRAN recognized LICENSE format
* Need to single-quote `pkgnet` in `DESCRIPTION` file

## v0.1.0 - Submission 2 - (April 12, 2018)

### R CMD check results
* No issues

### CRAN Response
* accepted and available on CRAN

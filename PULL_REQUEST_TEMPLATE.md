---
name: Pull Request Template
about: Please use the following template to open pull requests.
title: ''
labels: ''
assignees: ''

---

## Description
Please provide a summary of the changes.

### Problem / Motivation
If this is a bug fix, describe the specific problem or edge case being addressed. If this is a methodological update, explain the theoretical gap or necessity for this change.
Please add a code demonstration of the problem you are trying to solve
```
# Problem demonstration
```

### Proposed Changes / New Functionality
Describe the new features or logic introduced. Specify if this affects prior specifications, sampling algorithms (Rcpp), or summary outputs.

Fixes # (issue number)

Please add a code demonstration of your new functionality
```
# New feature
```

## Type of Change
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update
- [ ] Performance optimization
- [ ] Statistical/Methodological update

## Files Edited
Please list the primary files modified in this PR and a brief note on why.
1. 
2. 
3. 

## Testing and Validation
Describe the steps taken to verify the changes.
- Unit Tests: Added/updated tests in `tests/testthat/`
- Numerical Validation: Verified posterior consistency or Bayes factor stability.
- R CMD check: Ran `devtools::check()` and it passed with 0 errors/warnings.

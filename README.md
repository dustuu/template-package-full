* [template-package-full](https://github.com/dustuu/template-package-full) shows what happens when all repository variables and secrets are configured properly, and Unit Tests are present. This version uses all available new features.
  * The `Build Release` workflow will pass on all three jobs:
  * ![image](https://github.com/vrchat-community/template-package/assets/101824882/bff44050-a5dc-4ae0-ae6f-ce32d3e345b0)
  * The `Build Repo Listing` workflow will be trigged to run and will succeed, just as before. Additionally, this copies the previously created Code Coverage report onto the GitHub Pages website. This report can then be accessed via the Code Coverage badge in the README.

Both badges will be configured properly:

[![VPM Package Version](https://img.shields.io/vpm/v/com.vrchat.demo-template?repository_url=https%3A%2F%2Fdustuu.github.io%2Ftemplate-package-full%2Findex.json)](https://dustuu.github.io/template-package-full)

[![Code Coverage](https://dustuu.github.io/template-package-full/coverage/badge_linecoverage.svg)](https://dustuu.github.io/template-package-full/coverage)

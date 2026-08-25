> :information_source: this log lists user most visible changes

> :warning: to find all changes use [changelog.txt](https://github.com/andry81-devops/gh-action--check-os-version/tree/HEAD/changelog.txt) file

> :open_book: Explanation: https://gist.github.com/andry81/d278e6d129ca1af326eafb67470a2ae3

> :scroll: Legend: :shield: - security; :wrench: - fixed; :new: :sparkles: - new; :pencil: - changed; :twisted_rightwards_arrows: - refactor

## 2023.07.03:
* :pencil: changed: action.yml: added `[<workflow-name>][<step-number>]` as a prefix in all step names and duplicated it with the step name in the first comment line in all scripts to identify each step in a common pipeline log

## 2022.10.30:
* :pencil: changed: action.yml: `set-output` command is replaced in favor of `$GITHUB_OUTPUT` variable usage (details: https://github.blog/changelog/2022-10-11-github-actions-deprecating-save-state-and-set-output-commands/ )

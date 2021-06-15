# tortellini-on-rsd

Home of the workflow that creates an overview of any license problem we may have with any
of the repositories in the Research Software Directory (<https://research-software.nl>).

The workflow runs https://github.com/marketplace/actions/tortellini-action at weekly
intervals to produce the overview at <https://tortellini.research-software.nl/index.html>.

This repository also holds the configuration files [classifications.yml](classifications.yml) and [rules.kts](rules.kts)
used to evaluate licenses of dependencies using [ort](https://github.com/oss-review-toolkit/ort).
The configuration files included here originate from <https://github.com/oss-review-toolkit/ort/tree/master/examples>
and were slightly modified to fit the Netherlands eScience Center requirements.

## Disclaimer

`tortellini` aims at providing insights into the license dependencies of your package,
based on available information on open source licenses. We hope this information is helpful.
However, we are not lawyers and we do make mistakes. Therefore `tortellini` provides
information on an "as-is" basis and does not make warranties regarding this information.
For any questions regarding the issues related to the licenses in your code, please
consult a legal expert.

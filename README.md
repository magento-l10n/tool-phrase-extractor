Tool to find and extract phrases from Magento core or any Magento module.

Initial implementation MAY be based on `magento i18n:collect-phrases` CLI command and build with Symfony Console component. But final decision on technology stack and implementation is up to the working group.

Tool should implement CLI command that allows to discover all phrases in source code and create set of CSV files with names `__.csv` which holds phrases to be translated for a particular Magento component. Result of the tool should be ready for export to GitHub translations repository like [i18n-magento2](https://github.com/magento-l10n/i18n-magento2) and Crowdin project.

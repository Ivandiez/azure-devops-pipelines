This directory contains 2 CIs:
1. generate_report_for_unused_variable_groups.yaml - this pipeline creates a csv file with with unused variable groups and push it to Azure Storage Account
2. generate_full_report_variable_groups_with_releases.yaml - this pipeline creates a csv file with information about all variable groups. If it used in any release, this information also added.
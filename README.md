# Bitbucket-pipeline-Checkov
create an example bitbucket pipeline file that checkov "finds" a misconfiguration


create this pipeline for checking misconfiguration that apiiro do not found but checkov do.
for example here in this repo : a specific misconfiguration related to S3 bucket versioning using Checkov.
In this example, we'll look for a scenario where an S3 bucket does not have versioning enabled, 
and we want the Bitbucket Pipeline to fail if this misconfiguration is detected.

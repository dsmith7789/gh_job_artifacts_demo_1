## Job Artifacts
* For example:
    * Job: Builds app
    * Job outputs assets (app binary, website files, etc.) --> these are "artifacts"
    * Artifacts can be downloaded & used manually 
    * Artifacts can also be downloaded and used in other jobs via GitHub Actions

## Job Outputs
* Jobs can output simple values
* Values can be reused in another job
    * Ex. name of a file generated in a previous step
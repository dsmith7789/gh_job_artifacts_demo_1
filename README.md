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

## Dependency caching
* Some steps (ex. get code, install dependencies) are repeated many times. 
* Installing dependencies in particular is time consuming
* Reducing workflow duration --> faster website deployment, less money spent
* Built in action to support this: `cache`
* You can cache other things besides dependencies, this is just a very common application
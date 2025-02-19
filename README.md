Update the application.yml file in this GitHub repo to automatically deploy a new Shiny app to the OHDSI results.ohdsi.org website.

# Notes
* You can upload your data file to the results.ohdsi.org data server. However, storing the data in a new schema in the OHDSI Shiny database is preferred.
* Use this form to request a new OHDSI Shiny app database schema: [Fill out the form](https://forms.gle/ZHuqRMVRu8e5FNjE6) (If your data is small (<=1GB) you can just include the data files in your Shiny app Docker image instead).
* Newer versions of your data file can be uploaded and will be used automatically without having to rebuild and re-deploy the Shiny app Docker image.
* Newer versions of your data can be uploaded to the OHDSI Shiny app database and will be used automatically without having to rebuild and re-deploy the Shiny app Docker image
* Any Shiny app Docker image can be deployed to the results.ohdsi.org as long as it is compatible with the ShinyProxy software used on results.ohdsi.org and is publicly available

See the following GitHub repo for an example showing how to build a compatible Shiny app docker image within the OHDSI organization within Docker Hub:
https://github.com/OHDSI/OhdsiPredictionTutorial

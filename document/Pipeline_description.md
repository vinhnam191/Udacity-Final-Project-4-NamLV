# Pipeline Description

1. First developer commit code, and then trigger a new pipeline in CircleCi.
2. Then the job of pipeline is building project:
   - Prepare the environment like: nodejs runtime, environment variable, install required packages of both front and back end.
   - Run the Lint to make sure about the coding convention.
   - Then build all repos (api and front end).
3. After building, will go to step hold on to wait for user to click approval.
4. Last, deploy to AWS:
   - Preparing all the required environment like environment variables, install nodejs runtime on EC2 instance, deploy app...

## Pipeline flow

![Pipeline](/document/diagrams/pipeline.png)

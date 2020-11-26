# Vue js

### Instructions:

#### Generate the image:
`docker build .\setup_dev\ -t vue-setup-dev`

#### Run/use the Image:
`docker run -e "APP_NAME={your_project_name}" --mount type=bind,source="${PWD}",target=/app vue-setup-dev`
##### or
`docker run -e "APP_NAME={your_project_name}" -v ${PWD}:/app vue-setup-dev`

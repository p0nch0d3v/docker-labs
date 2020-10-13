# Docker Labs
---
# 1. Vuejs
## Instructions:
### Generate the image:
`docker build .\setup_dev\ -t vue-setup-dev`
### Run/use the Image:
`docker run -e "APP_NAME=your_project_name" --mount type=bind,source="${pwd}",target=/app vue-setup-dev`
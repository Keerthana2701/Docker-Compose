# Docker-Compose

-- docker-compose.yml:



version: "3.8"

services:

  datascience-notebook:

      image: jupyter/tensorflow-notebook

      volumes:

        - /absolute/path/here

      ports:

        - 8888:8888


      container_name: compose_test
      
      
      -- To run docker file : docker-compose up




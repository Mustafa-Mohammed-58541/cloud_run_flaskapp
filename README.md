## Running Locally with Docker

To test the application locally using Docker, follow these steps:

1. **Build the Docker image:**
   
    ```bash
    docker build . -t right
    ```

2. **Run the Docker container:**
   
    ```bash
    docker run -p 5000:5000 -t right
    ```

## Deploying to Google Cloud Run

To deploy the application to Google Cloud Run, follow these steps:

1. **Tag the Docker image with your Docker Hub repository:**

    ```bash
    docker tag right mostafa117/etl
    ```

   Replace `right` with the name of your local Docker image and `mostafa117/etl` with your Docker Hub repository name.

2. **Push the Docker image to Docker Hub:**

    ```bash
    docker push mostafa117/etl
    ```
# TO run on cloud run  
![working _couldrun](https://github.com/Mustafa-Mohammed-58541/cloud_run_flaskapp/assets/48077793/54110068-4a8f-4e0a-9238-cd26c987b2a9)

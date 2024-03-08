# To test it locally 
  - ''' docker  build . -t right '''
  - ''' docker run -p 5000:5000 -t right '''
# Run to cloud run in GCP
## Upload to Docker hub
  -  ''' docker tag right mostafa117/etl '''
  -  ''' docker push mostafa117/etl '''
# TO run on cloud run  
![working _couldrun](https://github.com/Mustafa-Mohammed-58541/cloud_run_flaskapp/assets/48077793/54110068-4a8f-4e0a-9238-cd26c987b2a9)

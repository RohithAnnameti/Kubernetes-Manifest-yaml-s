Step-1) Create blue-deployment

Step-2) Expose Blue PODS using Live-Service

Step-3) Access application using Live Service (Blue PODS will run)

Step-4) Clone any git repo 

Step-5) Modify Code + Build Project using Maven + Create Docker Image + Push Image to Docker Hub

Step-6) Create Green-Deployment with latest image

Step-7) Expose Green PODS using Pre-Prod-Service

Step-8) Access application using pre-prod Service (green PODS will run)

Note: Note down Live Service URL and Pre-Prod-Service URL 

Step-9) Access both URLS and see the difference


Live Service URL : http://3.109.202.11:30785/java-web-app/

Pre-Prod-Service URL : http://3.109.202.11:31785/java-web-app/


Step-10) Modify the selector in live-service from v1 to v2 and apply that using kubectl


Step-11) Access live service url (latest code should be accessible)

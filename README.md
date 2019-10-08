Run service:

    docker build -t flask-tutorial:latest .
    docker run -d -p 5000:5000 flask-tutorial

Then go to [localhost:5000](http://localhost:5000)

Stop service:

    docker ps
    docker stop <contained id>

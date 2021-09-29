# Geometry Identifier 
### for clients moving in an outdoor AP environment

The aim of this tiny utility is to create directional vectors
for outdoor WiFi users as they move between access points

The code being used here currently runs on O(n^2) complexity. 

#### docker-compose help

Build the image:
```docker-compose build```

This will take a few minutes the first time. Subsequent builds will be much faster since Docker caches the results.

Once the build is done, fire up the container:
```docker-compose up```

Terminal will the return with the link to the jupyter notebook

Finally,
```docker-compose down```

This stops containers and removes containers, networks, volumes, and images created by up.
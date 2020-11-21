Let's see if we can get an IRIS shell running on an IRIS community edition container.

docker pull store/intersystems/iris-community:2020.4.0.524.0
docker run --name my-iris -d store/intersystems/iris-community:2020.4.0.524.0
docker exec -it my-iris iris session IRIS

<h3>This is a sample code for accessing Environment Varibale in React App.</h3>

Environmental Variable REACT_APP_MESSAGE and `default` value is set to `MyApp` inside Dockerfile.

To access the variable you need to either pass the env var at the time of container initialization:

docker run -p `port`:`port` -e REACT_APP_MESSAGE `image-name`

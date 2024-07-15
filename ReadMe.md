# Spring Server Configuration Repository

This repository is designed to store the configuration of a Spring Server. Follow the steps below to set up and use the repository.

## Step 1: Create a Git Repository

1. **Create a Git Repository**: Initialize a new Git repository or use an existing one.
2. **Declare the Repository URI**: Add the URI of your Git repository to the `application.properties` file of your Spring Cloud Config Server.

    ```properties
    spring.cloud.config.server.git.uri=file:///G:/Workspace/git-localconfig-repo
    ```

## Step 2: Create Configuration Files

1. **Create a Configuration File**: In your Git repository, create a configuration file that matches the name of your application.

   Example:
    ```
    limits-service.properties
    ```

## Step 3: Declare Configuration Properties

1. **Add Configuration Properties**: Declare all necessary configuration properties in the newly created configuration file.

   Example:
    ```properties
    limits-service.minimum=1
    limits-service.maximum=995
    ```

By following these steps, you will have successfully set up a Git repository to manage the configuration of your Spring Server.

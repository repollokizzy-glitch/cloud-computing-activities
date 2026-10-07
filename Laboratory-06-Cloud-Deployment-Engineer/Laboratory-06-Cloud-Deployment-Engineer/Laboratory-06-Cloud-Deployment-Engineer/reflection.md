# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's job easier because the configuration of the application can be written once and reused whenever the system needs to be deployed. Instead of manually typing many `docker run` commands and configuring each container separately, Docker Compose can create and connect the required services using one configuration file. This is an example of Infrastructure as Code because the infrastructure is described using code.

YAML indentation is very important because YAML uses spaces to determine the structure of the configuration. If I make an indentation error or use a Tab instead of spaces, Docker Compose may not understand the file correctly and can return an error. This shows why carefully checking the formatting of configuration files is important in cloud engineering.

Environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` are used to configure the containers without changing the application image itself. They provide important configuration information to the services and allow the same container images to be used with different settings.

Deploying Nextcloud in only a few minutes was a useful experience because it showed how quickly modern cloud technologies can create a working application. Instead of installing every component manually, Docker Compose handled the deployment of the Nextcloud application and MariaDB database as connected services.

Since Mission 1, my understanding of Cloud Computing has evolved from learning basic concepts into understanding how cloud infrastructure can actually be deployed and managed. I have learned about cloud services, containers, storage, networking, and Infrastructure as Code. This mission helped me understand that cloud engineering is not only about using cloud services but also about designing, deploying, documenting, and managing reliable systems.

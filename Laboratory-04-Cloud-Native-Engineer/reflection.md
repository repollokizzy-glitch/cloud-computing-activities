# Mission Reflection

This laboratory helped me understand how containerization can make application deployment faster and easier compared with traditional virtual machines. When using a Virtual Machine, an entire operating system needs to be installed and configured before an application can be deployed. This process can take several minutes or longer depending on the system. Docker containers are much faster because they share the host operating system kernel and only need the application and its required dependencies. Because of this, a container can usually start within seconds.

Port mapping is necessary when a web server is running inside a container because the container has its own network environment. The Nginx web server normally listens on port 80 inside the container. By using `-p 8080:80`, port 8080 on the host computer is connected to port 80 inside the container. This allows users or applications on the host to access the Nginx server through `http://localhost:8080`.

When the `docker rm` command is used, the specified container is completely removed. Any data stored only inside the writable layer of that container is deleted. This means important data should not be stored only inside a temporary container; Docker volumes or other persistent storage should be used when data needs to remain available.

Containerization can also improve collaboration between software developers and IT operations teams. Developers can package an application with its dependencies into a container, while operations teams can deploy the same container consistently across different environments. This supports DevOps practices by reducing environment differences and making deployment and testing more predictable.

My GitHub portfolio is also evolving as I add more laboratory activities and technical documentation. Laboratory 04 allows me to demonstrate practical Docker and cloud-native skills instead of only writing theoretical explanations. Keeping my projects organized with Markdown files and screenshots makes my portfolio easier to understand and shows my progress as an IT student.

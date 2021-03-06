### What is minienv?
minienv is a web application and collection of backend services that allow you to quickly spin up Docker Compose environments
in the cloud that you can access from your web browser.

minienv also includes an online editor that allows you to edit source code or data files included in your Docker Compose
environments. This helps make minienv a great tool for learning (or teaching) new programming languages, databases, and
other technologies right from your browser.

### Why was minienv created?
minienv was created to help make it easier to deliver sample applications and developer tutorials that connect to databases
and other backend services. If you want to learn javascript and frontend web development there are a lot of really great
web-based tools available, like CodePen and JSFiddle, but what if you want to learn how to connect a Node.js application
with MongoDB, or a Jupyter notebook with Apache Spark? With minienv users get their own mini Docker Compose environments
where they can experiment with just about any technology, as long as it can run in a container.

If you are developing sample applications or tutorials and looking for a way to make them more accessible to developers
Docker Compose and minienv may be able to help!

### How do I set up minienv?
minienv runs inside Kubernetes as a set of Daemon Sets and Deployments (Docker Swarm support in development).
You can find instructions for setting up minienv in your own Kubernetes cluster [here](https://github.com/minienv/minienv/tree/master/kubernetes).
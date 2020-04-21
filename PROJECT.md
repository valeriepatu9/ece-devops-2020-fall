# DevOps course project

## Deadline

At the end of the DevOps course the students will pass an exam **and** a project:

### The exam

It will take place online via Moodle according to the planning.

**Format:**

- QCM (from 1 to 4 correct answers possible)
- 30 questions
- 45 min

It will contain 2 types of questions (15/15):

1. Questions on knowledge of execution CLI commands. Really basic usage of the tools we used like docker and kubectl, if you worked on project and did the work in class, it won't be a problem.

2. Questions for understanding DevOps general principles, understanding the basis architecture of the tools and their functionalities. For preparing, I would recommend you to reread all the slides with attached links to tutorials and docks, and rewatch short videos as well.

### The project

It has to be sent for evaluation **no later than 27th April 2020**. Work on a project can be carried out by 1 student or a team of 2 or a maximum of 3 students.

## How to send a project for evaluation?

1. Send an email to [sergei@adaltas.com](mailto:sergei@adaltas.com)

  - **Subject format:** "ECE - DevOps project - \<Group name/number\> - \<LASTNAME Firstname\>"
  - **Be sure you include in the email body:**
    - A link to the repository on GitHub (or GitLab)
    - Your group name/number
    - List of contributors

2. **Attention!** Make sure your repository is **PRIVATE** and **you sent an invitation** to the GitHub account - https://github.com/sergkudinov. Otherwise, if it is not PRIVATE the grade will be reduced to 0.

## Project instructions

The project is based on all the class works and students are allowed to use all of them them.   

### 0. Describe your project in the `README.md` file

  1. List of all the work performed (briefly, describing features and bonus tasks)
  2. Installing / running / using / testing / deployment instructions (everyone is needed)
  3. All the necessary links with the tools integrated (Travis CI, Heroku, Docker Hub ... )
  4. List of collaborators
  5. Other additional info you want to include

### 1. Create an application

  1. Enrich the draft application (at least finish all the TODO comments) on Node.js developed during the classes or create your own project using different language on your choice (like Java, Ruby, Python ...)
  2. Cover the app with unit tests (functional, integration, ...).

### 2. Apply CI/CD pipeline (using Travis CI and Heroku or other tools like GitLab)

  1. Configure CI with Travis CI
  2. Configure CD with Heroku

### 3. Build docker image out of your application

  1. Create a `Dockerfile`
  2. Push an image to your Docker Hub account

### 4. Make docker orchestration using Docker Compose

  1. Create a `docker-compose.yml` file with necessary configuration

### 5. Make docker orchestration using Kubernetes

  1. Install a Kubernetes cluster (using Minikube)
  2. Create a Kubernetes Manifest yaml file that configures deployment, services, replicas etc.
  3. Configure a persistent storage with Volumes in a Manifest yaml file

### 6. Make a service mesh using Istio

  1. Deploy your application using Istio
  2. Route requests between 2 different versions of your app
  3. Make traffic shifting between 2 different versions of your app

### 7. Configure infrastructure as code using Ansible

  1. Prepare a virtual environment and install Ansible on it
  2. Install Docker Engine on VM using Ansible
  3. Run a docker container on VM mounting Volumes
  4. Run docker containers using [docker_compose](https://docs.ansible.com/ansible/latest/modules/docker_compose_module.html) module

## How can you get some bonuses?

There is what you can do in additional to get a better grade:

  - Every initiative will be counted, just describe what you did in your README!
  - Use different tools and platforms instead of what is passed in the classes
  - Use different language (Java, Ruby, Python etc.) for developing an app or bring the Node.js app with an additional functionalities:   
    - cover with more unit/functional/integration tests
    - connect to any data base like: MongoDB, LevelDB, PostgreSQL etc.
  - Etc.

## Evaluation

... // TODO: describe evaluation criteria

# DevOps course project

## Deadline

At the end of the DevOps course the students will pass an exam **and** a project:

  - **The exam** in the format QCM will take place online via Moodle according to the planning. It will include from 20 to 30 questions (for 1 min. 30 sec. each), which were studied throughout all the modules.

  - **The project** has to be sent for evaluation **no later than 27th April 2020**. Work on a project can be carried out by 1 student or a team of 2 or a maximum of 3 students.

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

  - List of all the work performed (briefly, describing features and bonus tasks)
  - Installing / running / using / testing / deployment instructions (everyone is needed)
  - All the necessary links with the tools integrated (Travis CI, Heroku, Docker Hub ... )
  - List of collaborators
  - Other additional info you want to include

### 1. Create an application:

  - Enrich the draft application (at least finish all the TODO comments) on Node.js developed during the classes or create your own project using different language on your choice (like Java, Ruby, Python ...)
  - Cover the app with unit tests (functional, integration, ...).

### 2. Apply CI/CD pipeline using Travis CI and Heroku (or other tools like GitLab)

### 3. Build docker image out of your application:

  - create a `Dockerfile`
  - push the image to Docker Hub

### 4. Make docker orchestration using Docker Compose:

  - create a `docker-compose.yml` file with necessary configuration

### 5. Make docker orchestration using Kubernetes

  - install a Kubernetes cluster (using Minikube)
  - create a Kubernetes Manifest yaml file that configures deployment, services, replicas etc.
  - configure a persistent storage with Volumes

### 6. Make a service mesh using Istio

  - Deploy your application
  - Route requests between 2 versions
  - Traffic shifting 2 versions

### 7. ... // TODO: add additional instructions ( IaC)


## How can you get bonuses?

There is what you can do in additional to get a better grade:

  - Every initiative will be counted, just describe what you did in your README!
  - Use different tools and platforms instead of what is passed in the classes
  - Use different language (Java, Ruby, Python etc.) for developing an app or bring the Node.js app with an additional functionalities:   
    - cover with more unit/functional/integration tests
    - connect to any data base like: MongoDB, LevelDB, PostgreSQL etc.
  - ...

## Evaluation

... // TODO: describe evaluation criteria

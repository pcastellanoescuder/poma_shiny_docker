# POMA Shiny Docker

This repository contains the Docker image of POMA shiny app.

## How to run POMA in your computer?

### Step 1: Install Docker

First, you need to install Docker on your computer. If you have not Docker installed, visit [docker.com](docker.com) and install it.

### Step 2: Clone this repository

```r
git clone https://github.com/pcastellanoescuder/poma_shiny_docker.git
```

### Step 3: Run the docker image 

```bash
cd ~/poma_shiny_docker
docker run -p 80:80 poma_shiny_docker
```

Now, you can run the POMA ShinyApp in Docker :tada:

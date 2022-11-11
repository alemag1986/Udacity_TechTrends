# Cloud Native Application Architecture

## Tech Trends Project 

1. Techtrends projects
    - healthz endpoint added
    - metrics endpoint added
    - log capabilities added:
        - when access an article
        - when 404 pages when a non-existing articles are accessed
        - when Access "About Us" page
        - when A new article is created

2. Docker Image
    - docker file created
    - docker image uploaded to [Docker Hub Techtrends Image](https://hub.docker.com/repository/docker/crushingminds/techtrends)
    - docker_commands updated
    - docker image tested 
    - container logs added to docker_commands
    - required catpures added: `docker-run-local.png`

3. Github Actions
    - [Repository](https://github.com/alemag1986/Udacity_TechTrends)
    - [Actions](https://github.com/alemag1986/Udacity_TechTrends/actions)
    - [Action Definition](https://github.com/alemag1986/Udacity_TechTrends/blob/main/.github/workflows/techtrends-dockerhub.yml)
    - required catpures added: `ci-dockerhub.png`, `ci-github-actions.png`

4. Kubernetes Declarative Manifest
    - required manifests added to kubernetes folder
        - `namespace.yaml`
        - `deploy.yaml`
        - `service.yaml`
    - required catpures added: `kubectl get no.png`, `kubernetes-declarative-manifests.png`

5. Helm Charts
    - created helm template based on kubernetes manifests with default values
    - created staging env values file
    - created prod env values file

6. Continuous Delivery with ArgoCD
    - installed ArgoCD in K3s
    - created ArgoCD manifest for staging and prod
    - deployed staging 
    - deployed prod
    - required catpures added: `argocd-ui.png`, `argocd-techtrends-staging.png`, `argocd-techtrends-prod.png`

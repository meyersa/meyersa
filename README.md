# hey! I'm Meyers

I'm an Infrastructure Developer and this is the story of my Infrastructure. You'll find Infrastructure as Code, Machine Learning, and general experimentation here.

## Infrastructure

Everything is deployed on Oracle Cloud (free tier) with a Prod/Non prod staging environment. Full Infrastructure as Code, CI/CD, GitOps, Observability as Code, etc.

| Repository                                            | Technology                           | Buzzwords                            | Function                                                                                     |
| ----------------------------------------------------- | ------------------------------------ | ------------------------------------ | -------------------------------------------------------------------------------------------- |
| [IAC-Ansible](https://github.com/meyersa/iac-ansible) | Ansible, Bitwarden Secret Management | IaC                                  | Ansible playbooks for configuring hosts, deploying to hosts, and maintaining hosts.          |
| [IAC-CD](https://github.com/meyersa/iac-cd)           | Docker, Grafana                      | CI/CD, Observability as Code, GitOps | All resources applied to servers, staged and verified automatically before applying to Prod. |
| [IAC-CI](https://github.com/meyersa/iac-ci)           | GitHub Actions                       | CI/CD                                | Reusable GitHub Actions workflows used to facilitate automated deployments.                  |
| [IAC-GitHub](https://github.com/meyersa/iac-github)   | Terraform                            | GitOps                               | Configuration for all GitHub repos to enforce standards and best practices.                  |

## Machine Learning

| Repository                                                                      | Model                                              | Function                                                                                                   |
| ------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [ml-tornado-prediction-v2](https://github.com/meyersa/ml-tornado-prediction-v2) | 2D CNN                                             | Enriching MIT's TorNet dataset with additional image layers from sweeping GOES weather satellite coverage. |
| [ml-tornado-prediction](https://github.com/meyersa/ml-tornado-prediction)       | 3D CNN                                             | Original attempt to improve MIT's TorNet model with a time consideration as an additional axis.            |
| [ml-tornado-helper](https://github.com/meyersa/ml-tornado-helper)               | PIP Module                                         | Supporting loader for TorNet projects, leverages S3 and Cloudflare to streamline data gathering.           |
| [ml-truthradar-training](https://github.com/meyersa/ml-truthradar-training)     | Transformers (DistilBERT, MiniLM), RF, LR, XGBoost | Large language fine-tuning and supervised learning with real time responses on ARM.                        |
| [ml-jf-prediction](https://github.com/meyersa/ml-jf-prediction)                 | RandomForest, FastText                             | Recommendation engine based on large data history.                                                         |
| [ml-deer-identification](https://github.com/meyersa/ml-deer-identification)     | CNN                                                | Trail cam identification model for processing inconsistent and abnormal images.                            |

## Apps

Everything prefixed with "app-" is an application using the new deployment format.

| Repository                                            | Technology              | Function                                        |
| ----------------------------------------------------- | ----------------------- | ----------------------------------------------- |
| [app-test-py](https://github.com/meyersa/app-test-py) | Python, Poetry, FastAPI | Test app for deployment pipelines, system, etc. |

## General Experimentation

WIP Apps, e.g. Paranoia

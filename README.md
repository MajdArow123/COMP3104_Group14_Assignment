# COMP3104_Group14_Assignment

## Group Members
- **Leader:** Mjd Arow (101513153) - [GitHub](https://github.com/MajdArow123)
- **Member:** Amran Hawaga (101563789) - [GitHub](https://github.com/Swiper-kh)
- **Member:** Sami Alsadi (101571952) - [GitHub](https://github.com/SamiS3alsadi)
- **Member:** Anthony Huete-Jacobs (101570138) - [GitHub](https://github.com/ahueteja)

## Project Description
This repository is the Group 14 assignment for COMP3104 (Developer Operations) at George Brown College. It demonstrates a team Git workflow, including per-developer branching, pull requests, merge conflict resolution, and continuous integration with GitHub Actions. Each member contributes three text files covering George Brown College, the DevOps course, and the importance of DevOps in the SDLC.

## Setup Instructions
1. Clone the repository:
```bash
   git clone https://github.com/MajdArow123/COMP3104_Group14_Assignment.git
```
2. Move into the project folder:
```bash
   cd COMP3104_Group14_Assignment
```
3. Create and switch to your own branch (format: STUDENTID-Name):
```bash
   git checkout -b STUDENTID-Name
   git push -u origin STUDENTID-Name
```

## CI/CD Pipeline
This project uses GitHub Actions for continuous integration. The workflow is defined in `.github/workflows/ci.yml` and runs automatically on every push and pull request using an `ubuntu-latest` runner. Results can be viewed in the Actions tab, and a green check means the pipeline passed.

## Branching Strategy
- Each developer works on their own branch named `STUDENTID-Name`.
- All changes reach `main` through Pull Requests only.
- Nobody commits directly to `main`.
- Pull Requests are reviewed and merged by a teammate, never by their own author.

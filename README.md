[![Continuous Deployment](https://github.com/MarijkeSnip/CD_assignment/actions/workflows/cd_tests.yml/badge.svg)](https://github.com/MarijkeSnip/CD_assignment/actions/workflows/cd_tests.yml)

This is my soluction to implement a continuous deployment pipeline.
When any changes are committed pytest will run some tests (see test_main.py) and if they are succesfull GitHub Actions logs into the VPS on Digital Ocean 
updates the code to the latest version.

The components i have used are:
- **Droplet**: 
  A (virtual private server) VPS hosted by Digital Ocean.
- **SSH**: 
  SSH (Secure Shell) is a network protocol that provides a secure way to access and communicate with remote computers 
  over an unsecured network.
- **Github Actions**: 
  GitHub Actions is a powerful automation and CI/CD (Continuous Integration/Continuous Deployment) platform provided by GitHub. 
  It allows you to automate various tasks and workflows directly within your GitHub repository.
  In this case it is used to run test and connect and deploy to the VPS.

Problems i have encountered:
- **Github**: Although this wasn't a new element in this exercise i did have some issues. For testing purposes i set up a respository. 
  But i wanted a new one so it would be less messy. And for some reason had some problems with pushing to the new respository. 
  This was just due to me skipping a step (probably wanted to go a bit too quick since it's the last exercise).
- **SSH**: I did have some problems with understanding how it exactly worked with the different keys. But after somebody on slack gave me a link to a 
  video i was on the right path.
- I had some problems (during the entire module) to really understand what i was trying to do in general. So i did have to start 
  over in the proces to really make sure i understood what i was doing. 

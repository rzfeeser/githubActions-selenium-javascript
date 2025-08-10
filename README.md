# Overview
Hey gang! Professor Feeser here. Today we're going to check out how to use GitHub Actions to run Selenium tests. This perticular repository uses JavaScript to power the testing, but the lessons here should be easily adapted to any language (such as Python). 

## Demos
Videos demonstrating using this GitHub Action are available on the author's [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser):  

- [GitHub Actions - JavaScript Selenium Testing]()

If you found the video helpful, be sure to hit *like* and *subscribe* for weekly lessons from CodeWithFeeser.


## How to Use This Repository
- In the upper right corner, press **Star** (thanks)
- Next press **Fork** to copy the project to your repository
- From the project you just forked, click on the **Actions** tab
- Along the left you may choose from two workflows:
    - **Selenium Test on All Browsers (Paralell Jobs)** - Runs tests on the Edge, Chrome, and FireFox browsers
    - **Basic Selenium Test (Single Job)** - At run time, the user must choose the flavor of the single browser they would like to use to test: Edge, Chrome, and FireFox

 
## Helpful Notes
- The  **Selenium Test on All Browsers (Paralell Jobs)** is defined in `githubActions-selenium-javascript/.github/test-all-browsers.yml` and uses `strategy.matrix` to run multiple jobs in paralell with alternate inputs (those from the matrix). See [GitHub - Run Job Variations](https://docs.github.com/en/actions/how-tos/write-workflows/choose-what-workflows-do/run-job-variations) for more information


## Help & Training
If you are looking for Ansible or automation training for GitHub Actions, I offer in person and online training solutions for individuals and groups. For more information, reach out via my [contact portal at IRIS7](https://iris7.com/contact) 

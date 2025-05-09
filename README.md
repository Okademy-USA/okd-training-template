# okd-training-template
This is a repo template for all the training repo structure and contents

**Table of Contents**
- [Overview](#overview)
- [Code Organization](#code-organization)
- [week 1 & 2](#week1-2)
- [week 3 & 4](#week3-4)
- [week 4 & 5](#week4-5)
- [week 6](#week-6)
- [week 7](#week-7)
- [week 8](#week-8)
- [week 9](#week-9)
- [week 10](#week-10)
- [week 11 & 13](#week11-13)
- [week 14](#week-14)
- [week 15](#week-15)
- [TODOs](#todos)
- [Contribution](#contribution)

## Overview <a id="overview"></a>

> Add detailed overview of the training

## Code Organization <a id="code-organization"></a>

> repo tree
> - On Windows, run "tree /f" to get the tree view of the project.
> - On Mac, run "tree" on the project folder.

```
.
├── .gitignore
├── README.md
├── images
|   ├── some_image.gif
│   └── picture.gif
├── scripts
│   └── some_script.sh
└── stacks
    ├── trainingCode1
    ├── trainingCode2
    └── trainingCode3
```

## ToDos <a id="todos"></a>

Recommendations about the training provided by the tech trainer on next steps:
> [!WARNING]
> * provide some links to addiotnal resources

> Add any additional steps or tasks needed to get things working as expected

## Contribution <a id="contribution"></a>

> [!CAUTION]
> * This repo has one branch: **main**
> * **This repo DO NOT allow direct push to main branch.**
> * *Changes should be made on a feature branch only then merged to main after review and approval*

> Contributors:

<!-- readme: contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/50384_icfcorp">
            <img src="https://avatars.githubusercontent.com/u/111607821?v=4" width="100;" alt="50384_icfcorp"/>
            <br />
            <sub><b>Mulonda, Yann</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: contributors -end -->

#### Setup SSH connect between ICF Corp-GitHub

More info on [how to set up SSH from Source Code management to Local machine](https://medium.com/p/d805bb2ed28b)

> [!TIP]
> Makes sure you configure and authorizse SSO on your SSH authentication key like so:

![Configure & Authorize SSO](./images/configureSSO.gif)

#### Clone Repo & Setup feature Branch

For Windowns → Go to “Git Bash”, Right-click and “Run as Administrator”.<br> 
For Mac and Linux → Go to the terminal.<br>
Run the following commands to clone and create your feature branch:

```bash
git clone git@github.com:ICF-Corp/scs-repo-template.git
cd scs-repo-template
git checkout -b feature/yourBranchName
```

> [!IMPORTANT]  
> Make sure your branch name following theses naming standards:
> * **feature/**: when adding codee to introduce new features
> * **bug/**: when pushing bug fixes code to existing code base 

After making the necessary code changes, submited a pull request from your feature branch 
to main branch for review and approval before shipping the new changes to CD pipeline.

> [!IMPORTANT]
> **Validation on Pull Request before code merge**
>Validation Workflow will be triggerd on PR for code validation on things such as (syntax error, linting, security scanning, code review) 

> [!WARNING]  
> To maintain a clean repo, automatic deletion of feature branches upon PR approval is enable on this repo. 
> Your branches automatically deleted after pull requests are merged into Main branch.

#### Source Control Management
![](/images/SCM.png?raw=true)

#### Typical challnges/problems faced with SVN OR any traditional SCMs
- Branching is too costly in SVN (doesnt provide the flexibility to create-experiment-destroy the branches on the fly)
- If binaries are checked in as a part of source code it results in a huge repository size and ultimately larger build time for your code
- Parallel development is quite challanging with centralised source control mamagement systems.

#### What we did to overcome above challanges
- [Migrated code repositories in TFS to git with all history intact](http://darshandeshmukh.blogspot.in/2016/09/migrating-code-base-from-tfs-to-git.html)
- [Onboarded several teams from SVN to git with all tags,branches and release history intact](https://git-scm.com/book/en/v2/Git-and-Other-Systems-Migrating-to-Git) 
- Documented the branching+merging+[pull request strategy](https://www.atlassian.com/git/tutorials/making-a-pull-request) and trained new team members for installation,configuration of git workflow on their local  
- Onboarded teams to Bitbucket based development model from traditional SVN model
- [Enforced git commit messages policies](https://git-scm.com/book/en/v2/Customizing-Git-An-Example-Git-Enforced-Policy) for standardizing the process across all teams to maintain clean history for all the projects.
- [Used git commit messages to find more buggier files in codebase](https://www.linkedin.com/pulse/predicting-bugs-your-code-darshan-deshmukh) and used commit messages to visualize the productivity of development teams e.g. [Commits done for actual feature development Vs. Commits done for fixing the bugs](http://darshandeshmukh.blogspot.in/2017/02/finding-percentage-distribution-for.html)

To do - Block the commits on build failure, 


Resources - 
- [Pro Git](https://www.google.co.in/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwiA6euH2brTAhVJOI8KHVI8AQkQFggkMAA&url=https%3A%2F%2Fgit-scm.com%2Fbook&usg=AFQjCNGU4DTKIIYo6sTRgkq-xIvS9uVliw&sig2=SyYZgNq6DVF4ODbDaIxkIQ)

- [Pull request workflow](https://www.atlassian.com/git/tutorials/making-a-pull-request)

- [Gerrit workflow](https://docs.openstack.org/infra/manual/developers.html)

- [SCM Terminology](http://www.altium.com/documentation/17.1/display/ADES/((Glossary))_AD)

- [A Diff Tool to make your life easy KDiff3](http://kdiff3.sourceforge.net)


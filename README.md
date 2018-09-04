# Pull_Request_Test_Repo
Repo to test pull requests for NB 2018 

This is a simple git repository to use for testing pull requests.  

The steps are:
1. On github.com, find the test repo:  https://github.com/jasongraalum/Pull_Request_Test_Repo.
1. Fork this repo into your own account. (Fork button in the top right.)
1. Go back to your own GitHub page and you should see this forked repo.
1. Clone this repo into a local directory in your Linux Home Directory
    ```
    jgraalum@ruby:~$ git clone https://github.com/<your github username>/Pull_Request_Test_Repo
    Cloning into 'Pull_Request_Test_Repo'...
    remote: Counting objects: 8, done.
    remote: Compressing objects: 100% (8/8), done.
    remote: Total 8 (delta 1), reused 3 (delta 0), pack-reused 0
    Unpacking objects: 100% (8/8), done.
    Checking connectivity... done.
    ```
1. Change directory into the cloned repo
    %cd Pull_Request_Test_Repo
    ```
    jgraalum@ruby:~$ cd Pull_Request_Test_Repo/
    ```

1. Create a new branch - use your user name followed by "_branch" for the branch name
    ```
    jgraalum@ruby:~/Pull_Request_Test_Repo$ git branch jgraalum_branch
    ```
1. Move to that newly created branch
    ```
    jgraalum@ruby:~/Pull_Request_Test_Repo$ git checkout jgraalum
    Switched to branch 'jgraalum'

    ```
1. Now you can make edits to the test file: ClassList.txt.  Add you details and save the file.
1. Commit and push your edits to your branch.
    ```
    git commit -m "Added P. Sellers movie data" -a
    [psellers_branch 3aa89eb] Added P. Sellers movie data
    1 file changed, 4 insertions(+)

    jgraalum@ruby:~/Pull_Request_Test_Repo$ git push
    Username for 'https://github.com': testgraalum
    Password for 'https://testgraalum@github.com': 
    Everything up-to-date``

    jgraalum@ruby:~/Pull_Request_Test_Repo$ git status
    On branch psellers_branch
    nothing to commit, working directory clean
    
    ```
1. Finally, on your GitHub web page, find and click the "New Pull Request" button. You should see your new branch and a comparison to the master branch. If this looks OK, accept.


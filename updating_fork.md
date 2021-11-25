# Keep your fork updated

1.  Check what is your remote repository

        git remote -v

2.  Connect your local repo with original repo

        git remote add upstream url_from_original_repo

3.  To verify the new upstream repository you've specified for your fork, type `git remote -v` again. You should see the URL for your fork as origin, and the URL for the original repository as upstream.

4.  Pull changes for original repo:

        git pull upstream master

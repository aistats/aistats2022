# AISTATS Conference Stub Site

Welcome to the AISTATS Site.

If As well as providing information about the society and past meetings, the pages detail how to create 

**These steps need to be done by someone with admin access to the aistats github organization**

1. Create the new repo in github by going to <https://github.com/organizations/aistats/repositories/new>, use the name coding `aistatsXXXX` where `XXXX` is the year of the archived conference. 

2. Give the conference a description, "April 9 - 11, Playa Blanca, Lanzarote, Canary Islands"

3. Make sure the repo is set to 'public'.

4. Do *not* create an initial README for the conference. 

5. Create the Repo.

**These steps can be done with an account that has write access to the aistats.github.io.git**

6. Go to a suitable directory on your machine and type:

```
git clone --bare https://github.com/aistats/stub.git
mv stub.git aistatsXXXX
cd aistatsXXXX
git branch -m gh-pages
git push --mirror https://github.com/aistats/aistatsXXXX.git
```
7. Edit the `_config.yml` file in the new repo to set `baseurl` to `/aistatsXXXX`

8. Check that the stub website appears online at http://aistats.org/aistatsXXXX/

9. Update the main AISTATS site to list the current year's conference (presuming that the previous year's hs finised) [https://github.com/aistats/aistats.github.io](https://github.com/aistats/aistats.github.io).

11. Create a new admin team for this year's page, `aistatsXXXX`, and assign it to admin `aistatsXXXX` 

## More information

* See  a list of repositories of past web sites [here](https://github.com/aistats/).

* This link gives [Github help about project
pages](https://help.github.com/articles/user-organization-and-project-pages/)
(at the bottom), if we put the Jekyll files in **gh-pages** branch, the repository
will be served under http://aistats.org/aistats20xx. Note that the main
repository (http://github/aistats.github.io.git) master branch, not gh-pages.


* Repository set up by Neil Lawrence and first conversion of the old pages by Wittawat. Pages then arcived for the 2016 and 2017 editions of the conference. 


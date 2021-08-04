I frequently want to link a GitHub repo to its associated wiki, and vice versa

[Link from repo README.md to itself --> README.md](README.md)
* --> https://github.com/AndyGlew/Ag-stuff/blob/master/link,
* i.e. blob/master is inserted between the repo URL base and the page

[Link from repo to wiki: ../../wiki](../../wiki)
* ../.. to get out of blob/master to the repo URL base, then add /wiki

blob/master is git and GitHub stuff

"master" is the fairly standard Git name of the main branch.

"blob" is a git concept

but AFAICT it is GitHub convention
to form a URL for an item within the repo
from the concatenation of 
* repo base URL
* "blob"
* branch name "master"
* and the item pathname relative to the base of the repo

Q: can GitHub URL be formed in other ways, eg with something other than "blob/branchname" ?

---

See page in the Wiki associated with this repo
[Example Links from GitHub Wiki to Repo](../../wiki/Example-links-from-GitHub-wiki-to-repo)

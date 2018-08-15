# Commander Revamp

### Updating your fork with the upstream (Relic's Repository)
1. Add (if you already haven't, skip to 2 otherwise) Relic's repository as a remote called "upstream"
```bash
git remote add upstream https://github.com/RelicCOH/CommanderRevamp.git
```
You can check if it worked/already exists by running `git remote -v`.

2. Fetch from the upstream
```bash
git fetch upstream
```
3. Checkout to your fork's master branch (if not already active, skip to 4 otherwise)
```bash
git checkout master
```
4. Merge upstream to your fork's master branch
```bash
git merge upstream/master
```
5. Done! You can now push the merged changes to your fork. The status on the github page of your fork should now be:
```
This branch is even with RelicCOH:master.
```

#Delete local tags.<br>
git tag -l | xargs git tag -d<br>
#Fetch remote tags.<br>
git fetch<br>
#Delete remote tags.<br>
git tag -l | xargs -n 1 git push --delete origin<br>
#Delete local tasg.<br>
git tag -l | xargs git tag -d<br>

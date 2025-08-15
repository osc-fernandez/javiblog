ver### rsync obsidian's posts folder to hugo's posts folder

`rsync -av -delete "/Volumes/data1/JAVI/BLOG/posts/" "/Users/javimacmini/Documents/Blog/javi/content/posts/"`

#### commands to push local repo to online repo

within hugo folder run the commands below 

`// converts .md files to html files`
`hugo`

`// adds all current files to git repo` 
`git add .`

`// commit current files (changes) to git repo. m flag is for message or comment of commit`
`git commit -m "hey my first commit"` 

`// command to push commit to remote repo. note some git default to master instead of main`
`git push - u origin main`

#### creating subtree (branch) for hostinger 
![[Pasted image 20250815040222.png]]


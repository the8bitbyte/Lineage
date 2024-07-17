# Lineage
Searches multiple platforms simultaneously for a specified username, providing comprehensive results in one place.


A messy, poorly coded Bash script that provides a way to search multiple user-selected online platforms for information tied to a username. 'Lineage' allows you to choose which website it searches, as long as the site doesn't use user IDs in the profile URL, like Discord; then it should work. If you are having an issue with it, feel free to create an issue, and I will do my best to fix it. I assume the people using this are better at Bash than I am, so I'm not going to assume its perfect.

## installation and use
1. `git clone https://github.com/the8bitbyte/Lineage.git`
2. `mkdir fetched-sites` (because github won't let me include empty directory's in the repository)
3. `chmod +x lineage`
4. (optional) customize sites.txt
5. `./lineage`

## potetal issues

when selecting "edit sites.txt" it assumes you have vim installed and trys to open it with that, if you don't i imagine it will break.
ill fix this soon.



![lineage](https://github.com/the8bitbyte/Lineage/blob/main/lineage.gif?raw=true)
(sorry for poor quality there dont appear to be many good video to gif converters that perserve quality)

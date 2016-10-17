# opencores wiki backup

This is a backup of the old media wiki found on opencores. 

The goal is to slowly migrate the content to openrisc.io and other places. 

# Backup steps

Backup uses the git [mediawiki remote helper](https://github.com/Git-Mediawiki/Git-Mediawiki/wiki/Remote-Helpers)

```bash
 # Initial clone was with
 # git clone mediawiki::http://opencores.org/wiki1/


 # you can sync with latest media with with
 git remote add mediawiki mediawiki::http://opencores.org/wiki1/

 # this will pull the latest changes
 git pull mediawiki master

```

# 8Bells
Ships Bell Style Notification Script

Bash script to ring a Ship's bell from 8AM (08:00) to 8PM (20:00)

Requires sox & libsox-fmt-mp3 to be installed for Debian
Requires afplay & sox to be installed for macOS
Requires sox to be installed for FreeBSD

If you download the FreeBSD or Jack versions, you will need to rename the file to 8Bells.sh

- Place 8Bells.sh in ~/bin
- Place 8Bells mp3's in ~/Music/8Bells/ 
- Add crontab to call 8Bells script every 30 minutes. 
- Debian
- */30 * * * * /home/username/bin/8Bells.sh 
- FreeBSD
- */30 * * * * /usr/home/username/bin/8Bells.sh 
- macOS
- */30 * * * * /Users/username/bin/8Bells.macOS.sh 

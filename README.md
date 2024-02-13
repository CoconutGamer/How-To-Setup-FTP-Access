# How-To-Setup-FTP-Access

1. You should be outside of any folder / file / directory and You need Be in root user ``sudo -s``. 
2. You need to go in a file .So run ``nano /etc/ssh/sshd_config``.
3. Use the arrow keys to navigate on your keyboard.
    You need to go down and find ``PermitRootLogin yes``and``PasswordAuthentication yes`` make them Yes.
4. Then run ``sudo systemctl restart sshd`` So that the changes take place.

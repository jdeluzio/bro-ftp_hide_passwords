# bro-ftp_hide_passwords
Script to change which FTP passwords are collected by Bro.

By default most FTP logins are obfuscated by Bro. The only passwords that are exposed are defined in - option guest_ids = { "anonymous", "ftp", "ftpuser", "guest" }.

You can use this script to remove or add additional usernames to the guest_ids list. By default this script will replace every password with 'hidden' in Bro logs.

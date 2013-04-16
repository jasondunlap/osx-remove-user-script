osx-remove-user-script
======================

A Simple OSX Script to Remove Non Admin User Profiles

For administration of multiple macs, you can run this unix script in remote desktop. What it does is move the admin account to shared, then removes all other user (non admin) accounts except for shared and admin. All you need to do is rename admin, to whatever your admin account is. 


mv /Users/admin /
mv /Users/Shared /
rm -R /Users/*
mv /admin /Users/
mv /Shared /Users/


Helpful when managing quite a few macs with user accounts that need to be deleted at specified times. 


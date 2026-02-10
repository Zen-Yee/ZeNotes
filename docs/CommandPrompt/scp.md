# Secure Copy (scp)

|Command|Description|
|----|----|
|scp|Secure copy|
|-r|Recursive, means everything inside a folder, required when the source is a directory, not a single file|
|scp -r *Source* root@<ip>:/*Destination*|Copy the entire *Source* folder from my local machine to *Destination* on the server, logging in as root, over SSH.|
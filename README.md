# PHP SCRIPTS #

Useful scripts for php

## Git permissions ##
Changes rights for all modified files in a git repository

When developping website, it happens that you have authorizations
problems and you don't want to bother yourself and you make a simple
`chmod 777 -R ./`.

The problem is that git will consider all files modified, even if
it's only about rights.

This script is here to help you change that by changing all files rights

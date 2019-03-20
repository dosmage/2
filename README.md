# 2
ssh and other connection manager written in bash

known bug:
 * 2 should echo which host it's connecting to
 * 2 would benefit from using env to find bash
 * 2 may be dependant on bash3, where bash4 would be ideal to rewrite it

goals:
 * ssh-agent support
 * define a default key (or use ssh-agent)
 * add native git support to poll for updates

changes:
 v1.1  3/19/19
 * added colour to multiple matching list
 * .2 and .2-transport is created now regardless of argument
 * if no matches are found the behaviour is to attempt direct connect
 * added bugs, goals and changelog into the program
 v1.0  3/ 7/19
 * initial release
 * automatically create .2 and .2-transport files
 * added .2 and .2-transport functionality
 * added list of multiple matching hosts
 * added ability choose from multiple maching list
 * added passing arguments 3 and up to defined transport

# dear-diary
a simple tool for keeping secrets. 

![command line diary entry](https://raw.github.com/marywhite/dear-diary/master/img/diary.png)

## Install
```
npm install -g dear-diary
```

## Use 

make it yours...
```
dear-diary setup
```
then...
```
dear-diary write
```
all diary entries are encrypted and saved locally to your computer.

**NOTE** in it's current form, dear-diary is optimized towards creating one-line entries. at this moment, dear-diary uses [Inquirer.js](https://github.com/SBoudrias/Inquirer.js/) to gather user input. there is an open bug fix on this project to address problems with multi-line input. once this issue is resolved, dear-diary plans to implement the fix promptly.
if you make a mistake, you may delete your most recent entry with:
```
dear-diary erase
```
to read...
 ```
 dear-diary read
 ```
valid date inputs include
* [enter] | all
* today | yesterday
* last
* this week | this month | this year
* mOnDay
* 2/14/2015 | 2-14-2015
* February 14 2015

if you forget your password...
 ```
 dear-diary password
 ```
 
if you need help...
 ```
 dear-diary --help
 ```
## ANOTHER NOTE
this is a work in progress. it has only been tested in OSX and there are solutions working to current bugs with user input!
  

marywhite

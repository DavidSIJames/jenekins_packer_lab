# sparta chef template homework

## Description
the aim of this homework is to create a cookbook that installs and configures mongodb

unit and intergration tests should be written and should all pass

## Technology used
* chef
* vagrant
* virtualbox

## How to Download
1. if you do not have virtualbox download it [here](https://www.virtualbox.org/wiki/Downloads)

2. if you do not have vagrant installed download it [here](https://www.vagrantup.com/downloads.html)

3. If you do not have chef installed, download it [here](https://downloads.chef.io/chef)

4. If you do not have git installed follow this [guide](https://gist.github.com/derhuerst/1b15ff4652a867391f03)

5. In your browser, navigate to this [page](https://github.com/DavidSIJames/sparta_chef_template_homework)

6. Open your Terminal and navigate to where you want to clone the repo.

7. Once there, enter the following command to clone the repo:

	```terminal
	git clone git@github.com:DavidSIJames/sparta_chef_template_homework.git
  ```
8. once the repo has been cloned, cd into it using this command

	```terminal
	cd sparta_chef_template_homework
	```
9. to run the unit test enter the following command into the Terminal

```terminal
  chef exec rspec spec
```  
10. to run the intergration test enter the following command

```Terminal
  kitchen test
```
## challenges

The biggest challenge i faced was writing the tests, and find the commands to use in the recipe.

this was extremely frustrating, and i am still not confident in my understanding.

## Takeaway

A lot more work is needed in chef.

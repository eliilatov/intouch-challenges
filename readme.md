# In-Touch Insight Programming Challenges

These programming challenges are used as a portion of the technical interview process at [In-Touch Insight Systems Inc.](http://www.intouchinsight.com)

The challenges are designed to test several aspects of a developer candidate:

* PHP Skill
* Critical Thinking
* Creativity
* Problem Solving

**Note:** There are no *trick* questions, however there are some ways to go *above and beyond* the strict requirements of the question that can speak to the aspects above.

## How to participate

Fork this repository, read the instructions text files in each challenge folder.  Complete the challenges, commit and push back to your repository and open a pull request against this project.  We will close the pull request, but it notifies our dev team that someone has taken up the challenge!

## Rules

* Submissions must be written in PHP
* Submissions must run under PHP 5.5+
* Use an object-oriented structure as opposed to functional
* The "blank" PHP file in each challenge folder should be the answer entry-point
** i.e., we can run `php challenge1.php` from the `Challenge 1` folder to test your answer

If you need to include 3rd-party vendor libraries, please make sure you include both a `composer.json` and `composer.lock` so we're working off the same versions as you were.

No custom PHP extensions should be used - i.e., no extension that can't be installed via `apt-get` on a plain-jane Ubuntu 14.04 virtual machine using the default Ubuntun repositories.  *If* a custom extension is required, please add a `readme.md` file in the challenger folder explaining which extensions to install and why they were required to complete the challenge ("because it's faster" is an OK answer if you include a benchmark script to prove it!).

### Have fun and good luck!
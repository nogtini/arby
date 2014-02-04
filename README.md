aRby -- Alloy embedded in Ruby
==========

aRby demonstrates the benefits of having a declarative modeling language (backed by an automated solver) embedded in a traditional object-oriented imperative programming language.  This approach aims to bring the two opposing paradigms (imperative and declarative) closer together in a novel and unique way. We show that having the other paradigm available within the same language is beneficial to both the modeling community of Alloy users and the object-oriented community of Ruby programmers.  aRby provides elegant solutions to several well-known, outstanding Alloy problems: (1) mixed execution, (2) specifying partial instances, (3) staged model finding.

## Installation Instructions

aRby **requires** Ruby 1.9.3.  If you already have a different Ruby installations, you might want to consider using the Ruby Version Manager (rvm) to manager your Ruby versions, e.g., 

 ```bash
 rvm install 1.9.3
 rvm use 1.9.3
 ```
 
To download and install aRby, clone the Git repo, run `bundle install`, then run the unit tests by invoking the 'run_tests.sh' script:

 ```bash
 git clone https://github.com/sdg-mit/arby.git
 cd arby
 bundle install
 ./run_tests.sh
 ```
 
To run a particular test, pass the test file as an argument to the `run_tests.sh` script, e.g.,
 
```bash
 ./run_tests.sh test/unit/arby/models/abz14/sudoku_test.rb
```
  

 
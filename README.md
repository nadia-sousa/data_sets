# data_sets

set up commands:

``````
###### Set Up #####
# verify our folder with the data and module assets is installed
# if it is installed make sure it is the latest
!test -e data_sets && cd data_sets && git pull && cd ..
# if it is not installed clone it 
!test ! -e data_sets && git clone https://github.com/nadia-sousa/data_sets.git
# point to the folder with the assets
home = "data_sets/assignment____/" 
import sys
sys.path.append(home)      # add home folder to module search path

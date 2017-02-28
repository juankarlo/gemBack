# gemBack
This script will help you to quick backup a list of your current gems in your local machine and get a .sh to easyly install your gems in another machine.

## Usage
ruby gemBack.rb

At this moment is not working please use 

`gem list|sed 's/(//'|sed 's/)//'|awk '{print \"gem install \" \$1}' > installGems.sh`
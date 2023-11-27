# Using Module
<some_directory>$>go init mod gary.com/project

This is will generate a go.mod file containing the following content, for instance:

module gary.com/project

go 1.21.4

Then you may import any local libraries:

import "gary.com/prject/utils"

NB: utils is a folder in the same directory of go.mod.

# Check the modules in the current project
For instance: 

$> go list -m all<br>
gary.com/project


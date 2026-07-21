# iland-community
Tools and Material to be shared with the iLand community-tools

## About this repository
- here, we want to collect all tools, datasets, workflows (or whatever you think would benefit the iLand community) around iLand
- please, feel free to scan through the Overview below this section to get an overview of what tools are already in here and see if they might be useful for you
- if you created something that you want to share with people, please check out the "How to contribute" section below. We are happy for all contributions and can also give you feedback or help you in the process if needed
- when you struggle to get a tool from somebody else running, please reach out to the listed contributors 

## Overview of the tools/material

### ilandc-runner
- People contributing: Jonas Kerber (jonas.kerber@tum.de)
- a command line tool based on a python script that allows running many iland runs via the commandline tool "ilandc" in parallel
- you first define all your runs in a .csv file and set the number of parallel workers and then you start the running the tools
- the tool has some dependencies and therefore assumes that you run it on a Linux server or Linux machine (running it on Mac or WSL should be possible too, but was not tested yet)
- usage example: I used this for simulating 1440 iLand runs in parallel with 12 climates (3 models x 4 climate scenarios) x 12 landscapes x 10 replicates; it ran for a couple of days on a high performance server and I only had to set this up once

### (template tool)
- People contributing: Jane Beech, Joe Pine
- Quick summary in a few bullet points (detailed descriptions go to the README in the subfolder of the corresponding tool/material)

## How to contribute
1. Write and email to werner.rammer@tum.de with your Github name. He will then give you contributing rights to this Github repository.
2. Edit this file and add a quick description under the "Overview of the tools/material" section.
3. Create a new folder under the "collection" folder. Please check the TEMPLATE folder first so that we can keep a similar structure between tools
4. Add all the files needed for your tool. Please note that Github is not suitable for sharing larger datasets, so if you want to do this, please consult Werner or Jonas first. Any small data below 50mb should be fine.
5. Create a README.md in your folder (refer to template) with detailed instructions on installation and usage. Try to be detailed and write down all the steps required for a correct usage. The more detailed you are here, the less people will reach out to you when trying to get your tool working.

Thanks a lot for your contribution. This is incredibly helpful in making iLand more accessible, powerful and easy to use for the community.

If you are new to working with Git/Github and have problems contributing, please reach out to werner.rammer@tum.de and jonas.kerber@tum.de

## TODO
- Overview

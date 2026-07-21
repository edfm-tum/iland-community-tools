# iland-community-tools
Useful tools and material from and for the iLand modeling community.

## About this repository
- here, we want to collect all tools, datasets, workflows (or whatever you think would benefit the iLand community) around iLand
- please, feel free to scan through the Overview below this section to get an overview of what is already in here and see if they might be useful for you
- if you created something that you want to share with people, you are very welcome! Please check out the "How to contribute" section below. We are happy for all contributions, either as code, data, or just a link to a repistory, and can also give you feedback or help you in the process if needed
- note that are we can only provide minimal curation for material added to this repo!
- you are fully responsible for testing and verifying that any material from the repo works for your specific case
- please contact the listed contributes directly, if you have questions or encounter problems

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
1. Write a message in Discord saying that you want to contribute and give your Github name. Any moderator can then give you "Write" access to this repo.
2. Edit **this** file and add a quick description under the "Overview of the tools/material" section (note that you can edit Markdown files like this directly from the browser). Depending on the number of contributions, we might re-structure the flat list of the Overview section in the future.
3. Create a new folder under the "collection" folder. Please check the TEMPLATE folder first so that we can keep a similar structure between tools
4. Add all the files needed for your tool. Please note that Github is not suitable for sharing larger datasets, so if you want to do this, please consult Werner or Jonas first. Any small data below 50mb should be fine. If you merely want to link to another resource (either another GitHub repository, or a data repositoriy with a DOI like Zenodo), then ...
5. Create a README.md in your folder (refer to template) with detailed instructions on installation and usage. Try to be detailed and write down all the steps required for a correct usage. The more detailed you are here, the less people will reach out to you when trying to get your tool working.

Thanks a lot for your contribution. This is incredibly helpful in making iLand more accessible, powerful and easy to use for the community.

If you are new to working with Git/Github and have problems contributing, please reach out to werner.rammer@tum.de and jonas.kerber@tum.de (or via discord)

Note that it is also possible that you keep your tool as a seperate repository under you personal account (could maybe be helpful if your tools is part of a paper where you want to link that separate repository). In that case, please at least add and link your tool to the overview section in this README file and (if needed) create a seperate folder with additional material.



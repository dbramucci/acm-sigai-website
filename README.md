# acm-sigai-website
The source for the K-State ACM-SIGAI club website.

## Meta-information

Use [Nikola](https://getnikola.com/) to compile the site.
The output should then be pasted into the corrosponding folder on the website's host, `cislinux.cs.ksu.edu`.
Currently, only `dbramucci` has write permissions to the folder.
This permission can be transfered by CS Support but only one account can own the folder at a time.
The process of updating the folder should eventually be automated.

## Installation and Usage of Nikola

To run this locally, install Nikola.
This can be done globaly with `pip install Nikola[extras]` or `pip3 install Nikola[extras]`.

Then, navigate to the folder containing the site and run `nikola build` to update the `output` folder to match the current site.
While making new pages, it is recommended to use `nikola auto` to have the website automatically update as you write the source files.


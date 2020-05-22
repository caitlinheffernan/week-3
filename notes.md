# Notes
**Open Refine**
* try changing the numbers while doing clusters (if there's the option) to find more possible clusters
* clean whitespace: Edit Cells -> Common transforms -> Trim leading and trailing whitespace’

**Problems**
* texas.txt comes back empty
    * have to run `curl http://archive.org/stream/diplomaticcorre33statgoog/diplomaticcorre33statgoog_djvu.txt > texas.txt` in command prompt not anaconda
* Sublime text: `\n[~.+]` only deletes blanks lines
   * use `\n[^~]+`
* Open Refine: have to select seperated by **commas** not tabs
* Gephi: "Cannot find Java 1.8 or higher"
   * https://github.com/gephi/gephi/issues/1787
   * Open gephi.conf (in etc folder)
   * put file path for Java (`C:\Program Files (x86)\Java\jre1.8.0_251`) after `jdkhome=` and remove `#`

# What is it?
APTnotes is a repository of publicly-available papers and blogs (sorted by year) related to malicious campaigns/activity/software that have been associated with vendor-defined APT (Advanced Persistent Threat) groups and/or tool-sets.

# Where's that data?
In the original repo, we maintained an ongoing README with links to all of the reports in some form (we tried) order.
We also stored all of the reports in year named folders within the repo itself (we ran out of room).

To solve the storage problem, we have moved everything over to Box (thanks Box!).
In order to maintain chronological order (and our sanity) we have migrated to CSV and JSON summary file(s).

# How can I download all the reports from Box?
Use one of the scripts within this repo: https://github.com/aptnotes/tools
* For historical context, see: https://github.com/aptnotes/data/issues/50

## APTnotes.csv
[APTnotes.csv](https://github.com/aptnotes/data/blob/master/APTnotes.csv)
This a CSV summary file used to keep track of all the data

### Format

|Filename|Title|Source|Link|SHA-1|Date|Year|
|:------------- |:-------------:|:-----:|:-----:|:-----:|:-----:|:-----:|
|Name of the file|Title of the report|Vendor|Box Link to the report|SHA-1 of report| Date of report release|Year of release|

## APTnotes.json
[APTnotes.json](https://github.com/aptnotes/data/blob/master/APTnotes.json) -- This is a converted version of the CSV format

### Format
Example
```
[{"sha1": "3e6399a4b608bbd99dd81bd2be4cd49731362b5e", "Title": "How China Will Use Cyber Warfare", "Filename": "Fritz_HOW-CHINA-WILL-USE-CYBER-WARFARE(Oct-01-08)", "Source": "Jason Fritz", "Link": "https://app.box.com/s/696xnzy1an3jbm3b212y5n8xieirbemd", "Year": "2008", "Date": "10/1/08"},
```
# How can I help?
There are multiple ways to get a report added:
  * Notify us via Twitter using the hash tag #aptnotes
    * Example: `new report by vendor on this group - link #aptnotes`
  * Reach out to us directly
    * [@aptnotes](https://twitter.com/aptnotes)
  * Create a new issue on Github including the data you want added (using the default issue template)
    * We created an issue template to take the guesswork out of things
      * If the document is only available in HTML, print a "clean" version (e.g. with [Print Friendly](https://printfriendly.com/) or similar) to PDF

# Why do we do it?
Like almost every open-source project, this is a labor of love. 
There are so many reports out there, and they either get lost in the mix or taken down before you get a chance to read them.
This is our effort to:

 * **1.** Make sure these lovely reports get consumed 
 * **2.** Ensure the people of #DFIR #infosec know what's out there
 * **3.** Hopefully add some context to the chaos
 
# How is this data being utilized?
At present (that we know of...) these current projects consume this repo and make magical things happen:

* [Threat Miner](https://www.threatminer.org/)

# Thank You
This project would not be where it is without the people that have helped along the way, thank you [contributors](https://github.com/kbandla/APTnotes/blob/master/contributors.md)

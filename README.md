# Spammers List

This is a list of referrer spammers maintained by me.

The list is stored in this repository in spammers.txt. This text file contains one host per line.


Sorting

To keep the list sorted the same way across forks it is recommended to let the computer do the sorting. The list follows the merge sort algorithm as implemented in sort. You can use sort to both sort the list and filter out doubles:

sort -uf -o spammers.txt spammers.txt


Disclaimer

This list of Referrer spammers is contributed by the community and is provided as is. Use at your own discretion: it may be incomplete (although we aim to keep it up to date) and it may contain outdated entries (let us know if a hostname was added but is not actually a spammer).

Contributing

To add a new referrer spammer to the list create a new branch for this commit and start a pull request.
In your pull request please explain where the referrer domain appeared and why you think it is a spammer.

If you open a pull request, it is appreciated if you keep one hostname per line, keep the list ordered alphabetically, and use Linux line endings.

Please search if somebody already reported the host before opening a new one.



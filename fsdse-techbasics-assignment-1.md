### Navigating The Linux Filesystem

* Change directory to folder fsdse-techbasics-assignment-1
  - List down what there in folder [ ls -l ]
  - List down hidden files in folder [ ls -la ]

### Working With Files And Directories

* Check what kind of file is orders.txt [ file order.txt ]
* Display the content of file orders.txt [ cat order.txt]
* Let's explore order.txt more and try to solve query below using `head`, `tail` commands
  - Get first 10 orders [ head order.txt]
  - Get last 10 orders [ tail order.txt]
  - Get last 3 orders [ tail -n 3 order .txt ]
  - Get first 4 orders [ head -n 4 order.txt ]
  - Get order from 10 to last [ tail -n +10 order.txt ]
  - Get all order, except last 10 order [ head -n -10 order.txt ]
* Create a new folder named 'orders' [mkdir orders]
* Copy orders.txt file in the orders folder [ cp order.txt orders/ ]
* Rename orders folder to 'orders_backup' [ mv orders orders_backup ]
* We don't need tmp folder, delete a folder named tmp [ rm -r tmp]
* We don't need tmp.txt file, delete a file name 'tmp.txt' [rm tmp.txt]
* Lets add below orders to the list using nano command
  - American Pizza
  - Italian Pizza
* Now again repeat all above exercises with order.txt using `head` and `tail` commands. Result will be different this time as new two orders are added to list using `nano` command.
* Locate the word "Chinese" in order.txt file using command line. [ grep "Chinese" order.txt ]
* Locate the word "Fish" in order.txt file and highlight using color using command line. [ grep --color "Fish" order.txt ]
* Locate the word "Salad" in order.txt file with the line number where Salad is present using command line. [ grep -n "Salad" order.txt]
* Locate the word "rice" in order.txt file with and make sure it's case-insensitive match. [ grep -i "rice" order.txt ]

# bikefinder
This short python script was written to help automate the process of looking for a bike on Craigslist. The script
scrapes the mountain bike page on Craigslist and looking for attributes for each bike that match what I was searching for.
If a bike contains any of the attributes, all the information for the bike is stored and printed to a text file, along with the URL
for the post. If new bikes are being added to the text file and line indicating the new bikes is displayed allowing for it to be
read more easily. In order to not get repeated posts, each bike's unique id is stored in a separate file. If a bikes attribute matches
the desired attributes, the ids are compared. If the id of the bike is present in the id file, the bike is not added. This program
helped to shorten the search time for a new bike. This will be on a new branch.

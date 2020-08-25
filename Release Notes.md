I've been hard at work bringing new (and old) features to Progressions, but while I work on that, here's a quick patch to fix some of the glaring issues in the latest release!

- When opening the list of keys for transposing, the current key wasn't always displayed on screen. So now the list will automatically scroll to show the current key before being displayed, which just feels a little better.

- Charts with titles containing complex characters could cause problems with the sorting, and if they got out of order, the whole list would simply not display. Obviously, that's not ideal, so I dug into how this is done and improved it, fixing the problem with the missing list in the process.

- When using the "Backup Now" option, the list of files wouldn't be properly updated to show the newly created file until you exited and reentered that screen. So I tweaked it to ensure it updates and also added an option to immediately export the file for good measure, because why not?

- The counts for "All Charts" and "Favorites" weren't updating as expected, especially noticeable when restoring from a backup (which would get a touch confusing). I've updated the code to more-or-less force a refresh, and looks like it's good to go again.

- The user guide wasn't being updated as intended, but a quick pass over the code has ensured that the downloaded copy is being properly stored. Now you're not stuck reading 4 year old articles like some kind of chump. I've also updated and reworked many of the articles, so that's a bonus right there.

- Some of the card-like views were causing the iPhone status bar to act a little wiggy while opening and closing, so I decided to go with a permanent one to avoid weirdness, and to make those animations nice and smooth.

- A minor oversight on my part meant that the index that would appear on the side of certain lists of charts was missing, making those larger collections a bit of a pain to scroll through. Fear not, however, as it has returned, good as ever, and life can go back to normal once more.

- The way the URL scheme was being handled was resulting in a handful of odd behaviours and crashes. I've given this some thought and updated it to be a little more streamlined, so now it's smooth like a frog. A smooth frog.

- There were a couple of layout-related issues in the chart toolbar with iOS 11, so I made some adjustments to how they're set up, avoiding the problems entirely… because that's how I roll.

If you have suggestions, or need some help getting around the new version, you can email me at support@pgns.co, or hit up @progressionsapp on Twitter. I'd love to hear from you!

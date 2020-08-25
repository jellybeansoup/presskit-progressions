It's been a little bit since the last update, and I apologise for that! It's partly because I've been busy with other work, but also because there were a couple of pretty tricky bugs to sort out. Nevertheless, here's a new update to hopefully sort out some of the stuff I've been able to track down.

- Charts got a small visual improvement with very subtle highlighting of chords within the content. This more or less acts as a visual marker of what can/will be transposed, and helps to differentiate things a little. There's no additional adjustments that can be made at this stage, but I'm working on more improvements in this space, so stay tuned.

- On occasion, charts can have words that are also chords: A and Am being two of the obvious candidates. You can now "escape" these words with a forward slash (like so: \A or \Am), and the resulting txt won't be picked up when transposing. Progress!

- The underlying database had some concurrency issues that could cause odd behaviour when editing sets or writing charts (though mostly the former). I went over the affected code with a fine-toothed comb and cleaned up the parts that could cause problems, which has smoothed things out considerably.

- Charts that contained tabs (as in the spaces, not the musical ones) has some formatting issues that could pop up, where lines would get cut short unnecessarily, causing chords to get out of line with lyrics, amongst other things. Rather than fixing it (because I literally can't), I've introduced ways of replacing them with spaces instead, avoiding the whole thing altogether.

- The delete/remove buttons for charts were inaccurately labelled due to a minor logic error, and the whole fiasco was made more confusing by the fact that favourite charts were deleted, not "unfavourited", as the label might have suggested. Both of these things have been resolved, ensuring that there is no confusion, or lost charts.

- I made some very, very minor tweaks to how stuff in Settings is displayed, making it a little clearer as to what does what, and the things that can actually be poked at.

- Using the tab key to move between fields in the chart editor was a bit haphazard, causing things to be highlighted and the key menu to be opened. I've streamlined the behaviour so it works as expected, so no more haunted editor.

If you need help with something, want to report problems, or just want to shoot compliments my way, you can totally do that! Hit me up by email at support@pgns.co or follow @progressionsapp on Twitter.

Until next time!
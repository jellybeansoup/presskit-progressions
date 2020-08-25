Hello again! I'm back with another update to patch up a few bugs and oddities. Thanks to everyone who's been getting in touch… your help has been instrumental. There's still more to patch up, but this takes care of the most notorious for the moment!

- List animations were acting all wiggy and could cause significant issues in certain cases, but I tracked down the underlying cause and made some changes which appear to have cleared things right up, and things are much smoother now.

- The paging system for displaying charts wasn't quite hooked up the way it should have been, and in some cases would cause crashes if things didn't go how it expected. I went over it with a fine tooth comb to clear up any possible issues, and while I was at it, I improved some of its interactions with other UI. It's much nicer now.

- The chart selection screen for creating sets was crashing on opening, which was very very strange. I quickly fixed up the issue, so it should be good to go again.

- The backup system was doing more work than it really needed—attempting to create multiple automatic backups at once, which is unnecessary as heck—so I streamlined its code and ensured that things happen in sequence, which should mean future backups are more reliable, and will resolve the occasional crash that could occur if things went truly pear-shaped.

If you fin that you need help, want to report problems, or just want to shoot compliments my way, you can totally do that! Hit me up by email at support@pgns.co or follow @progressionsapp on Twitter.

Until next time!

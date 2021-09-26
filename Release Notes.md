Who ever would've thought that iOS 14 would break stuff? Not me, but I was wrong, as evidenced by this release focused (mostly) on fixing a fun new bug introduced by iOS 14.

- For the purposes of testing, the less versions of iOS that I need to support, the easier it is. As such, I've moved up the minimum supported version to iOS 13. This shouldn't affect too many people, but should significantly improve my ability to stay on top of bugs and introduce new features down the line.

- Something in iOS 14 changed the way that split views work (i.e. the thing that makes Progressions have a two column layout), which in turn caused the button used to hide the side column to straight up crash the app. Not ideal at all, so I dug in, changed a whole bunch of stuff, and made the columns behave as intended. No muss, no fuss.

- After like two years of ignoring them, I got an itch to get some shortcut intents implemented, so you can now search for charts, create them, and open them from actions in Apple's Shortcuts app, which is cool and good (and useful for automating parts of Progressions). There's a few more on the way, but this felt like a solid start.

- There was a few things broken with link-sharing for charts, so I reached in, rummaged about a bit, and got things working again. No big deal… most of the problems were on the server side, but I did attempt to make it a little more resilient.

Thanks for using Progressions! If you need help, I'm only an email away! Hit up support@pgns.co or tweet @progressionsapp, and I'll do what I can to help!

Until next time: stay safe, stay warm, and tell someone you care about that you love them.
# RuneLite-Chat-Filter-Regex
This is my current setup for RuneLite's chat filter plugin.

My goal is to filter out all spam messages from bots while keeping as many real players' messages as possible.

## Known Issues
All websites ending in: .com, .gg, and .co.uk are filtered out. This is so I don't have to add every new website and every variation on how it could be typed out. If I find the time/motivation, I'll work on only filtering out the bad ones but as of now don't count on it.

## Setup
### Manual
Copy the raw 'Filtered_regex' file into the 'Filtered regex' section in the config for the Chat filter plugin
### Automatic
Download the 'Chat Filter Updater' plugin and paste https://raw.githubusercontent.com/YodaChainGun/RuneLite-Chat-Filter-Regex/refs/heads/main/Filtered_regex into the 'Filter URL' section in the config
### Chat Filter Config
Make sure 'Strip accents' is checked! While others require that this setting be off, my list relies on this setting to filter out most spam!

## Contribution
I don't spend too much time at the GE so please message me with a copy of any spam that isn't caught and any real messages that're accidentally filtered out.

Thank you!

# Hey Servers!

## VIM Tili Tale
Again, everyone favourite text editor (sort of). This section won't talk much and in detail things about Vim, its just a super-duper general recap on Vim. 

Vim has 3 modes. But before we dive deep in modes, a bit of explanation on why vim has modes itself is that, vim does not rely on gui. The only interface we're dealing with when we handle servers is just the CLI. That way, most of the time, Vim is pre-installed in most Unix/Unix-like systems/servers, etc. In a way, GUI text editor, like Jetbrains, VSCode, VS, Pycharm, etc also has modes. It just that it don't particularly shown, in an explicit way, because, you know, it has GUI.

Back to modes, VIM has 3 modes:
1. Insert Mode
This is the mode where you can insert, edit your text. `Type "i" if you want to change to insert mode`
2. Command Mode
Command mode is the mode where you do things, as it named, copy, paste, etc. `Click "ESC" if you want to enter command mode`
3. Last Line Mode
Used for searching, close, save, close without saving, etc. This is the chain when you want to, let's say, the most googled thing about Vim, close the Vim itself. So you enter Command Mode, then Last Line Mode, by entering ":q!". `So yeah, it use ":" to get to Last Line Mode`

## Data Centers and the Cloud
When we talk about Servers, everything can be a server. The point is that, as long as it can serve things, (eg: files), we can already call that a server. 

But what about the rack of black boxes that we often see in news or etc? In most cases, server and consumer grade device were build differently. Because it won't do any fance stuffs, like doing photoshop or anything. It just as it is, server, serve things. In most cases, servers build with a very fast processors, many cores (64, 128) because with memories (RAM) that has an ability to correcting memory. Definitely not the memory we see everyday like in our PC, or Laptop.

Data centers? It's basically a collection of servers. Remember when we talk about the racks of black boxes? Exactly.

Again, what about the cloud? It used to be, let's say, we want to deploy our web, it used to be, we deployed on that rack of black things. But with cloud, it's actually the same thing, except that, now it can be on other side of the world, instead of near us. We can say that it's the more modern-ish way to do it.

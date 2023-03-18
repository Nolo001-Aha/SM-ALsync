# StringMap AlSync

WIP: expose an API to transparently synchronize a StringMap with a database or KeyValues omnidirectionally.
Current goal: Find a way to have access to Key-Value pairs right in memory with as little latency as possible,
while still making sure that the data is safely stored on disk.

Originally I came up with this idea when I needed a very fast way of retrieving and storing data on the fly,
and neither Cookies/KeyValues/SQL(ite) were an option.
I have no idea if this is going to work, but I'll at least give it a try.
# JabRef Markdown Exporter
During the literature research for my thesis, an exporter for the reference manager [JabRef](https://github.com/JabRef/jabref) was developed.
This simple tool was used to simplify synchronization of the collected literature and corresponding notes managed in the project's repository.

[md.begin.layout](./md.begin.layout) defines general layout settings affecting the entire output.
Here, only a heading is added to form an appropriately formatted list.

Each individual reference is exported with a formatted title, its document object id for quick navigation to the original document, information about the publication, and a link to a file holding personal research notes.
These layout definitions are contained in [md.layout](./md.layout).
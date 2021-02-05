# JabRef Markdown Exporter
This provides a custom export filter for references managed in [JabRef](https://github.com/JabRef/jabref) as a Markdown list. For information on how to set it up for use please refer to the corresponding JabRef Docs about [adding a custom export filter](https://docs.jabref.org/collaborative-work/export/customexports#adding-a-custom-export-filter).

[md.begin.layout](./md.begin.layout) defines general layout settings affecting the entire output.
Here, only a heading is added to form an appropriately formatted list.

Each individual reference is exported with a formatted title, its DOI for quick navigation to the original document, information about the publication, and a link to a file holding personal notes.
These layout definitions are contained in [md.layout](./md.layout).

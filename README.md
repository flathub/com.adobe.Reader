# Acrobat Reader 9.5.5 for Linux

> Adobe Reader software is the free trusted standard for reliably viewing, printing, and annotating PDF documents. It's the only PDF file viewer that can open and interact with all types of PDF content, including forms and multimedia.

The latest version of Adobe Reader that is available for Linux is 9.5.5 released in 2013 and only for the i386 architecture.  However, to this date it is still the only PDF viewer for Linux that supports advanced features like JavaScript and embedded Flash.

With the introduction of JavaScript functions and support for embedded Flash in Adobe Reader 8.x and 9.x, more and more security vulnerabilities emerged that can compromise a system simply by viewing a crafted PDF document.

The last available Linux version, 9.5.5, contains numerous reported and thus known vulnerabilities that Adobe is no longer closing because development on version 9.x has been discontinued. Newer versions of Adobe Reader are not available natively for Linux.

This is why the sandbox for this Flatpak is rather tight and might seem restrictive by default. Networking capability is disabled and filesystem access is only allowed to xdg-documents.

Due to its old age and the diminishing availibity of its likewise old dependencies the application is overall a bit crashy. Unfortunately, it's not really possible to debug these crashes since Adobe Reader is completely closed source and stripped of all debugging information.

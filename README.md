# Cisco snippets package for Sublime Text 2

Sublime Text 2 Cisco Snippets. This package includes various snippets for Cisco routers/switch/firewall configurations.

## Installing

**Without Git:** Download the zip from github, and extract the files to your Sublime Text "Packages" directory, into a new directory named `Cisco`. You can find the packages directy by going to Preferences -> Browse packages, within Sublime Text 2.

**With Git:** Clone the repository in your Sublime Text "Packages" directory:

    git clone git://github.com/tunnelsup/sublime-cisco-snippets.git

## Usage
To use the snippets, type the snippet name then hit tab. Some snippets allow you to then tab through the config. Available snippets are:

* `static` - Creates a static NAT for ASA 8.3+
* `acl` - Creates an ACL for an ASA
* `/24` - Expands into 255.255.255.0
* `obj` - Creates an object-group
* `route` - creates a route for an ASA

## Further Reading
See official website for further information and discussion.
[http://www.tunnelsup.com/tup/2013/03/29/sublime-text-2-cisco-syntax-and-snippets](http://www.tunnelsup.com/tup/2013/03/29/sublime-text-2-cisco-syntax-and-snippets)

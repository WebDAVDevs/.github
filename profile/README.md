## WebDAV file management for internet

The DAV protocol is an extension for usual web sites to work files and shared documents.
It's like a shared network folder but that can be accessed from internet.

The protocol was developed in early times of internet bt didn't get much popularity because of some problems:
1. It's not so easy to implement it. E.g. it's based on XML format which is botched and not convenient.
2. It's too abstract: this is not something bad by itself but it's not clear for newcomers why a command to get a directory list is `PROPFIND` and why creating a folder is `MKCOL`. 
3. Many features are missing: no deletion to trash bin, not photo thumbnails, file permissions etc.
4. To complicated to create a WebDAV share: you have to configure a plugin for a web server. And it's really only a few of them mainly Apache and IIS. Today we have many good file sharing programs.
5. Many problems with interoperability between servers and clients. During a long time most of the problems were solved.
6. There wasn't really such a big need in the protocol. The Windows Share (SMB), or FTP or SFTP solve basic needs good enough.

The protocol development is stalled so only we as a community of developers and users can move forward and negotiate additions to the protocol.

Please feel free to start a new topic in [Discussions](https://github.com/orgs/WebDAVDevs/discussions)

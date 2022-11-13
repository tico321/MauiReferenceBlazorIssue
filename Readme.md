Repository meant to reproduce issue described in the following SO [question](https://stackoverflow.com/questions/74418080/net-7-xapras7028-system-io-filenotfoundexception-could-not-find-file-bin-debug)

Later I found out that you cannot reference a WebAssembly project from a Maui project.
If you want to share pages between them you need to create a shared project, I'll keep this repo as an example of that.
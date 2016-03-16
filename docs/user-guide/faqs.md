# FAQs
Here you can find a list of frequently asked questions and their answers.

* I'm getting a 404 Not Found error whilst trying to install NamelessMC

One possibility is that you've installed NamelessMC within a subdirectory. A requirement for the package to function is that the files are installed directly into your root directory, or you use a subdomain to point to the subdirectory.

If this is not the case, you will need to modify your server configuration to enable the use of .htaccess files and also Apache's mod_rewrite module.

Usually this occurs if you are running Ubuntu, in which case following all steps within [this guide](http://askubuntu.com/a/48363) should help you out.


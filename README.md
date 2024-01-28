# davlgd's Exherbo Packages

To add this repository to your Paludis configuration:

* Edit `/etc/paludis/repositories/davlgd.conf`
* Add this content:

```
format = e
location = /var/db/paludis/repositories/davlgd
sync = git+https://github.com/davlgd/exheres.git
sync_options = --branch=main
```

# new-release-checker

Regularly checks if a new upstream version is available for some applications, such as [Mattermost](https://github.com/mattermost/mattermost-server) and [Nextcloud](https://github.com/nextcloud/server).
Upstream version is compared with the one used in NethServer packages, such as [nethserver-mattermost](https://github.com/NethServer/nethserver-mattermost) and [nethserver-nextcloud](https://github.com/NethServer/nethserver-nextcloud).
If upstream version is newer than NethServer one, an update issue is created in [NethServer issue tracker](https://github.com/NethServer/dev/issues) and a pull request is created in the corresponding NethServer repository.

Version checks are performed daily by the Travis build.
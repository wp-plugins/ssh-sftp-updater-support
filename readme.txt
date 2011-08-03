=== SSH SFTP Updater Support ===
Contributors: TerraFrost
Donate link: http://sourceforge.net/donate/index.php?group_id=198487
Tags: ssh, sftp
Requires at least: 3.1
Tested up to: 3.2
Stable tag: trunk

"SSH SFTP Updater Support" is the easiest way to keep your Wordpress installation up-to-date with SFTP.

== Description ==

Keeping your Wordpress install up-to-date and installing plugins in a hassle-free manner is not so easy if your server uses SFTP. "SSH SFTP Updater Support" for Wordpress uses phpseclib to remedy this deficiency.

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Changelog ==

= 0.1 =
* Initial Release

= 0.2 =
* recursive deletes weren't working correctly (directories never got deleted - just files)
* use SFTP for recursive chmod instead of SSH / exec
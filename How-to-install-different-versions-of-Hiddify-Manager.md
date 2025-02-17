
<div dir="rtl">

[**![flag_of_Iran](https://user-images.githubusercontent.com/125398461/234186932-52f1fa82-52c6-417f-8b37-08fe9250a55f.png) &nbsp;فارسی**](https://github.com/hiddify/Hiddify-Manager/wiki/%D9%86%D8%B5%D8%A8-%D9%86%D8%B3%D8%AE%D9%87%E2%80%8C%D9%87%D8%A7%DB%8C-%D9%85%D8%AE%D8%AA%D9%84%D9%81-%D9%87%DB%8C%D8%AF%DB%8C%D9%81%D8%A7%DB%8C%E2%80%8C%D9%85%D9%86%DB%8C%D8%AC%D8%B1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/hiddify/hiddify-config/wiki/All-tutorials-and-videos"><img width="100" src="https://github.com/hiddify/hiddify-config/assets/125398461/8ac5b906-105c-4b98-acf5-0e12e39e33f6" /></a>
</div>



<div dir="ltr" markdown="1">

# How to install different versions of Hiddify Manager
As you know, Hidify Manager is offered in three versions as follows:

* **Develop version:**

This version is a version of the software that is being developed to create the latest features. This version may have bugs, so it is better to install it on test servers.

* **Beta version:**
This version is a version after the version under development, and in fact it is the version before the final release, in which part of the bugs have been fixed and it has new features.

* **Release version:**


This version is actually the final version of the software that was released after the final tests and is the most stable version possible. See this figure for a better understanding.

<div align=center>

![install versions](https://github.com/hiddify/Hiddify-Manager/assets/125398461/6528a2c5-f938-48c3-a88f-f829d7e3a481)

</div>

## Install Release version
* Before installing, if you have already installed another version of the panel, take a backup of the panel. [Read more...](https://github.com/hiddify/Hiddify-Manager/wiki/How-to-backup-and-restore-panel-on-Hiddify#how-to-backup-and-restore-panel-on-hiddify)
* Now just run the following one-line command in the terminal.

```
bash <(curl i.hiddify.com/release)
```

* After installation, just restore your backup. [Read more...](https://github.com/hiddify/Hiddify-Manager/wiki/How-to-backup-and-restore-panel-on-Hiddify#restoring-backup-file)


## Install Beta version
* Before installing, if you have already installed another version of the panel, take a backup of the panel. [Read more...](https://github.com/hiddify/Hiddify-Manager/wiki/How-to-backup-and-restore-panel-on-Hiddify#how-to-backup-and-restore-panel-on-hiddify)
* Now just run the following one-line command in the terminal.

```
bash <(curl i.hiddify.com/beta)
```

* After installation, just restore your backup. [Read more...](https://github.com/hiddify/Hiddify-Manager/wiki/How-to-backup-and-restore-panel-on-Hiddify#restoring-backup-file)


## Install Develop version
* Before installing, if you have already installed another version of the panel, take a backup of the panel. [Read more...](https://github.com/hiddify/Hiddify-Manager/wiki/How-to-backup-and-restore-panel-on-Hiddify#how-to-backup-and-restore-panel-on-hiddify)
* Now just run the following one-line command in the terminal.

```
bash <(curl i.hiddify.com/dev)
```

* After installation, just restore your backup. [Read more...](https://github.com/hiddify/Hiddify-Manager/wiki/How-to-backup-and-restore-panel-on-Hiddify#restoring-backup-file)

## Install the desired version
It is possible to install a specific version. Just follow the instructions below.


```
bash <(curl i.hiddify.com/vVERSION)
```


Here, instead of VERSION, you should enter the desired version. Suppose you want to install version `8`. Just run the following command.

```
bash <(curl i.hiddify.com/v8)
```
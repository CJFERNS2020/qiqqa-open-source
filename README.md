

 [![logo](../../blob/master/icons/Application/Qiqqa.png) ](http://qiqqa.org/)
 
# [Qiqqa (Open Source)](http://qiqqa.org/)

[![Join the chat at https://gitter.im/qiqqa/community](https://badges.gitter.im/qiqqa/community.svg)](https://gitter.im/qiqqa/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Now open source award-winning Qiqqa research management tool for Windows.

This version includes **every** feature available in [Commercial Qiqqa](qiqqa.com), including Premium and Premium+.

> Unfortunately we have had to **remove the web cloud sync** ability as that involves storage costs. Users are encouraged to migrate their Web Libraries into Intranet libraries, and **use Google Drive or Dropbox**
 as the 'sync point' for those libraries.


## Download Qiqqa

* [Download Qiqqa Open Source](https://github.com/jimmejardine/qiqqa-open-source/tree/master/Qiqqa.Build/Packages) installer for v80 and newer releases.
  > For release notes see [CHANGELOG](../../blob/master/CHANGELOG.md).
  > *Installer files should be uploaded to [releases](https://github.com/jimmejardine/qiqqa-open-source/releases) in the future.*

* [Test bleeding edge](https://github.com/GerHobbelt/qiqqa-open-source/releases) Qiqqa Open Source **experimental** releases.

  > **DO NOTE** that these releases are only lightly tested and may include grave bugs. Backup your library before testing these, even if you like living on the edge...
  > *@GerHobbelt has joined the team and keeps the bleeding edge rolling. For recent changes see  [closed bugs list](https://github.com/jimmejardine/qiqqa-open-source/issues?q=is%3Aissue+is%3Aclosed).*

* Qiqqa Commercial software installer releases v66 to v79 are available at [qiqqa.com](www.qiqqa.com/Download) at least until 2020 and also [here](https://github.com/jimmejardine/qiqqa-open-source/tree/master/Qiqqa-Software-Installer-Releases).

### Notifications of new releases

To be notified of new releases [subscribe](https://groups.google.com/d/forum/qiqqa-releases) to the Google Group 'qiqqa-releases'.


## Documentation For Users

Documentation still needs a **lot** of work. All help is appreciated. The Commercial Qiqqa manual is available at [qiqqa.org](http://qiqqa.org/The.Qiqqa.Manual.html).

Other documentation material is being added as we go; the sources for that are available in this repository's [docs](./docs) directory.


## Qiqqa Collaborators & Developers Wanted
 
If you are interested in contributing towards better Qiqqa, please contact @jimmejardine or @GerHobbelt.


### For Developers: Building Qiqqa From Source

It needs some technical experience. See the [DEVELOPER-INFO](DEVELOPER-INFO.md) for details.

---


# WARNING NOTICE for Commercial Qiqqa users with a user account and Web Libraries

> (I previously tried v79 and both account and guest library. I also have web account)

Note this from the qiqqa.com commercial website (emphasis mine):

**After 10 years of your support we have decided to make Qiqqa open source so that it can be grown and extended by its community of thousands of active users.**

***NB: We will be discontinuing Web Library support for Qiqqa at the end of 2020. So you’ll have one year within which to install the latest version of Open Source Qiqqa (which is improving daily), migrate your Web Libraries into Intranet Libraries, and enjoy all the Premium and Premium+ features of Qiqqa for free (except Web Libraries)!***

## Web Libraries (Commercial Qiqqa *cloud storage*) will be discontinued 'at the end of 2020'.

**The only way to access your REMOTE = CLOUD-STORED libraries is by using Qiqqa v79, as the Cloud access code was never open sourced.**

The way that Open Source Qiqqa (v80 and later) *appear* to access your Web Libraries is by discovering the **local copies** of those libraries, which Commercial Qiqqa (v79 and older) kept (*manually*) synchronized. That way, Qiqqa continues to provide access to your *former* Web Libraries. (See also [#4](https://github.com/jimmejardine/qiqqa-open-source/issues/4).)

**Therefore, if you *doubt* or *know* your local copy of your Web Library to be *out of sync* with your cloud-based Web Library (because you or others updated/synced that cloud-based library from other machines after your last sync action on this one) you MUST install Commercial Qiqqa v79 ([available here](https://github.com/GerHobbelt/qiqqa-open-source/releases/tag/v79) among other places) to log into your Qiqqa cloud account, synchronize your Web Libraries with your local copy and then re-install Qiqqa Open Source (v82 preferentially).**

Qiqqa versions v79, v80 and v82 can be installed over one another without issue as they are binary compatible re Qiqqa local library files, so there's no expected harm done in installing v79 over v82, particularly if you limit your activity to syncing Web Libraries. 

(By the way: the `setup.exe` will certainly yak about you installing Qiqqa over a 'newer' version. Disregard and continue.)

Then, once you re-installed v82, it will discover your local Web Library copy again (now synchronized) and you should be good to go.

Do note that the *name* of the library as shown in v82 might be [UUID-like](https://en.wikipedia.org/wiki/Universally_unique_identifier#Format) gobbledigook instead of the proper title you gave it back in the day of Commercial Qiqqa and v79. The contents should be available untrammeled though.




-----------------------------------------------------------------------------

<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-1.png" > 
</p>
<p >
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-3.png" > 
</p>



-----------------------------------------------------------------------------

Getting Started:
==============

To get started with the building process, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository, use a command like this:

```bash
      repo init -u git://github.com/jdcteam/manifests_side.git -b dot-pie
```

Then to sync up:
================

```bash
    repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

```bash
source build/envsetup.sh
lunch dot_<devicecodename>-userdebug
make bacon
```
-----------------------------------------------------------------------------


<p align="center">
<img src="https://raw.githubusercontent.com/samgrande/manifest-1/dot-p/Untitled-4.png" > 
</p>

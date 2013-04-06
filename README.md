gruik-patches
=============

various dirty/unpolished patches and scripts

        ^
      / ! \    Dirty dirt dirty. Gruiiiiiiiiiiiik
      ____

* mutt-sidebar-dirname-instead-of-INBOX.patch

Using offlineimap, hierarchy is $Maildir/$Account/{INBOX,folder1,...folderN}
This ugly patch renames INBOX with the parent directory, the account name.

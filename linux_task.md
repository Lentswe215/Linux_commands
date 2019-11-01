Task 1

1. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ ls
Desktop    Downloads         google-drive  Pictures  snap       Videos
Documents  examples.desktop  Music         Public    Templates

2. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ pwd
/home/lentswe

3. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ mkdir Workspace
lentswe@lentswe-HP-250-G3-Notebook-PC:~$ cd Workspace

4. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ ls
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ 

5. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ touch README.md

6. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cp README.md CHANGELOG.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ ls
CHANGELOG.md  README.md
--------------------------------------------------------------------------------------------------------
Task 2

lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ touch exercise.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ ls
CHANGELOG.md  exercise.md  README.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ mv exercise.md /tmp
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ ls
CHANGELOG.md  README.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ rm /tmp/exercise.md
--------------------------------------------------------------------------------------------------------
Task 3

1. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat umuzi.md recruits.md cohort.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  umuzi.md

2. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ nano umuzi.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ nano recruits.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ nano cohort.md

3.  lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat cohort.md
You are my sunshine.
You are my shining star.
Everything I'm not,
You are.`
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat umuzi.md
You brought me sunshine
when I only saw rain.
You brought me laughter
when I only felt pain.

lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat recruits.md
I don't think you will
Ever fully understand
How you've touched my life
And made me who I am

4.  lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat umuzi.md recruits.md cohort.md >> summary.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ ls
CHANGELOG.md  cohort.md  README.md  recruits.md  summary.md  umuzi.md  You
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat summary.md
You brought me sunshine
when I only saw rain.
You brought me laughter
when I only felt pain.

I don't think you will
Ever fully understand
How you've touched my life
And made me who I am

You are my sunshine.
You are my shining star.
Everything I'm not,
You are.

5. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ echo "The end" >> summary.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Workspace$ cat summary.md
You brought me sunshine
when I only saw rain.
You brought me laughter
when I only felt pain.

I don't think you will
Ever fully understand
How you've touched my life
And made me who I am

You are my sunshine.
You are my shining star.
Everything I'm not,
You are.
The end
------------------------------------------------------------------------------------------------------
Task 5

1. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ cd Documents
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Documents$ touch pad.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Documents$ ls
pad.md
2.  lentswe@lentswe-HP-250-G3-Notebook-PC:~/Documents$ cd ../Desktop
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop$ mkdir work
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop$ mkdir work
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop$ cd work

3. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop/work$ cp ../../Documents/pad.md pad_copy.md
lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop/work$ ls
pad_copy.md 

4. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop/work$ locate updatedb
/etc/updatedb.conf
/etc/alternatives/updatedb
/etc/alternatives/updatedb.8.gz
/usr/bin/updatedb
/usr/bin/updatedb.mlocate
/usr/share/man/man5/updatedb.conf.5.gz
/usr/share/man/man8/updatedb.8.gz
/usr/share/man/man8/updatedb.mlocate.8.gz

5. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop/work$ cd -
/home/lentswe/Desktop

6. lentswe@lentswe-HP-250-G3-Notebook-PC:~/Desktop$ locate pad_copy.md
/home/lentswe/Desktop/work/pad_copy.md
------------------------------------------------------------------------------------------------------
Task 6

1. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ locate *.pdf
/snap/gnome-3-28-1804/67/usr/share/doc/shared-mime-info/shared-mime-info-spec.pdf
/snap/spotify/36/usr/share/doc/shared-mime-info/shared-mime-info-spec.pdf
/usr/lib/libreoffice/share/xpdfimport/xpdfimport_err.pdf
/usr/share/cups/data/classified.pdf
/usr/share/cups/data/confidential.pdf
/usr/share/cups/data/default-testpage.pdf
/usr/share/cups/data/default.pdf
/usr/share/cups/data/form_english.pdf
/usr/share/cups/data/form_russian.pdf
/usr/share/cups/data/secret.pdf
/usr/share/cups/data/standard.pdf
/usr/share/cups/data/topsecret.pdf
/usr/share/cups/data/unclassified.pdf
/usr/share/doc/printer-driver-foo2zjs/manual.pdf
/usr/share/doc/qpdf/qpdf-manual.pdf
/usr/share/doc/shared-mime-info/shared-mime-info-spec.pdf

2.  lentswe@lentswe-HP-250-G3-Notebook-PC:~$ locate *.pdf >> pad_files

3. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ cat pad_files
/snap/gnome-3-28-1804/67/usr/share/doc/shared-mime-info/shared-mime-info-spec.pdf
/snap/spotify/36/usr/share/doc/shared-mime-info/shared-mime-info-spec.pdf
/usr/lib/libreoffice/share/xpdfimport/xpdfimport_err.pdf
/usr/share/cups/data/classified.pdf
/usr/share/cups/data/confidential.pdf
/usr/share/cups/data/default-testpage.pdf
/usr/share/cups/data/default.pdf
/usr/share/cups/data/form_english.pdf
/usr/share/cups/data/form_russian.pdf
/usr/share/cups/data/secret.pdf
/usr/share/cups/data/standard.pdf
/usr/share/cups/data/topsecret.pdf
/usr/share/cups/data/unclassified.pdf
/usr/share/doc/printer-driver-foo2zjs/manual.pdf
/usr/share/doc/qpdf/qpdf-manual.pdf
/usr/share/doc/shared-mime-info/shared-mime-info-spec.pdf
-----------------------------------------------------------------------------------------------------
Task 7

1. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ nano my_bio.md
3. lentswe@lentswe-HP-250-G3-Notebook-PC:~$ mkdir my_files
lentswe@lentswe-HP-250-G3-Notebook-PC:~$ mv my_bio.md ./my_files
lentswe@lentswe-HP-250-G3-Notebook-PC:~$ cd my_files
lentswe@lentswe-HP-250-G3-Notebook-PC:~/my_files$ ls
my_bio.md

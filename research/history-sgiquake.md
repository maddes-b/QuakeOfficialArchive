# SGI Quake / IRIX Quake

SGI stands for "Silicon Graphics, Inc", a company responsible for the "Silicon Graphics Computer Systems", a high-end workstation capable of 3D graphics in 1996.

Quake was ported to this platform prior to the source code being GPL'ed and was called "SGI Quake", "SGIQuake", or "IRIX Quake", after the name of the SGI operating system IRIX.

> Id software bears _NO_ support responsibility for the SGI versions of Quake (either .gl or .sw) whatsoever! Likewise, SGI is releasing these versions of Quake as-is, and is not responsible for support. These executables are being made available in a large part through the efforts of individual employees of SGI, and to the extent that we can we'll be happy to answer questions on the appropriate SGI newsgroups (comp.sys.sgi.\*). Please help ensure further Quake-related progress by limiting your questions to this channel.

-- https://www.siliconbunny.com/mirrors/ftp.sgi.com/sgi/quake/doc/quake1.html

Releases:

* 1996 Oct 24, GLQuakeV0_3.tar.Z, GLQuakeV0_3src.tar.Z, libutil.tar.Z
* 1997 Feb 12, sgiquake.tar.Z or sgiquake.tar.gz.pre_040997
* 1997 Mar 25, quake.gl
* 1997 Apr 09, sgiquake-1997-04.tar.gz
* 1997 May 02, sgiquake-1997-05-02.tar.gz
* 1997 May 14, sgiquake-1997-05-13.tar.gz
* 1997 May 22, sgiquake-1997-05-21.tar.gz
* 1997 Sep 24, sgiquake.tar.gz






## Custom Quake Renderer (early SGI Quake?)

Not a port of Quake, but a Quake renderer/server written for SGI.

```text
GLQuake v0.3 available
Ed Hutchins
24 Oct 1996

I've made the source to my OpenGL Quake walkthrough available on my
homepage at: http://reality.sgi.com/employees/hutchins_asd
I'm hoping others will want to pitch in and get it running as
a client (and possibly a full game server) on SGI machines. This
is my first OpenGL program and should in no way be construed as
a benchmark of what SGI machines can do :-)
- Ed
```

-- [comp.sys.sgi.announce](https://groups.google.com/g/comp.sys.sgi.announce/c/qBpfTShJ8E4/m/-RDNLwsnauQJ)



```text
* GLQuake v0.3 - GLQuake executable
* GLQuake v0.3 source - Quake walkthrough in OpenGL (was IRQuake)
* libutil.a sources (now also included in GLQuake distribution)

These links should work again, but some browsers have trouble with relative links (all browsers had trouble with the absolute path).
GLQuake has the majority of rendering code and the QuakeC interpreter needed for getting a full Quake server running, but someone out there will have to work on replicating Quake's main world-simulation loop. Writing a client-side quake terminal should be possible since most of the client-server protocol has been documented in the Quake specs.
Note that you need IRIX 6.2 or later to compile GLQuake, and that you'll need the PAK files from the game. I'd recommend buying it outright, but you can also get the shareware levels from id software's site. I haven't tried running with the v1.06 PAK files yet, but I assume the changes aren't too drastic (GLQuake works with v1.01). If anyone ports GLQuake to other platforms, I'd be happy to put pointers or distribute copies from here.
```

-- [http://reality.sgi.com/employees/hutchins_asd/](https://web.archive.org/web/19980220092553/http://reality.sgi.com/employees/hutchins_asd/) (archived)

Links:

* ftp:ftp/GLQuakeV0_3.tar.Z
* ftp:ftp/GLQuakeV0_3src.tar.Z
* ftp:ftp/libutil.tar.Z




## SGI Quake (Ed Hutchins) v???

Perhaps released as `sgiquake.tar.Z`, later distributed as `sgiquake.tar.gz.pre_040997`.


Announced:

```text
February 12, 1997

SGI Quake
It's not one of Zoid's ports, but there's an SGI Quake avaiilable at Ed's Homely Page (which is part of the SGI site). I don't know if it works or anything, but if anyone want to send me a Silicon Graphics workstation to test it with, I'll be glad to. Thanks CareTaker.
```

-- https://www.bluesnews.com/archives/feb97-2.html
-- https://www.bluesnews.com/cgi-bin/blammo.pl?mode=archive&display=19970412&oneday=true

Links:

* http://reality.sgi.com/employees/hutchins_asd/


Suggestion of a prior version, or perhaps this references his two versions (e.g. Feb and April 1997).

```text
SGI Quake!
The port of idsoftware's Quake to SGI platforms is finally ready for prime-time!

sgiquake.tar.Z - SGI quake executables for all platforms

Here's the README.TXT file included in sgiquake.tar.Z.
I couldn't resist putting these out early here, the more kosher location for SGI quake will be here.
Note: there was a slightly broken version here for a while (savegame didn't work), get the latest version if you notice this problem.
```

-- [http://reality.sgi.com/employees/hutchins_asd/](https://web.archive.org/web/19980220092553/http://reality.sgi.com/employees/hutchins_asd/) (archived)


Links:

* http://reality.sgi.com/employees/hutchins_asd/ftp/sgiquake.tar.Z
* http://reality.sgi.com/employees/hutchins_asd/README.TXT
* http://www.sgi.com/Fun/Free_games.html


```text
Welcome to the SGI port of Id Software, Inc's Quake!
Disclaimer:
Id Software, Inc bears NO support responsibility for the SGI versions of Quake (either .gl or .sw) whatsoever!
Likewise, SGI is releasing these versions of Quake as-is, and is not responsible for support.

These executables are being made available in a large part through the efforts of individual employees of SGI, and we refer any questions on the appropriate SGI newsgroups (comp.sys.sgi.*).
```

-- [http://www.sgi.com/Fun/free/sgi-quake.html](https://web.archive.org/web/19980701023059/http://www.sgi.com/Fun/free/sgi-quake.html) (archived)

Link:

* http://reality.sgi.com/employees/hutchins_asd/ftp/sgiquake.tar.Z



Archive content:

```text
   3934 12 Feb  1997 LICINFO.TXT
  43292 12 Feb  1997 MANUAL.TXT
   3766 12 Feb  1997 ORDER.TXT
   7951 12 Feb  1997 README.TXT
   1406 12 Feb  1997 quake
 582564 12 Feb  1997 quake.gl
 668456 12 Feb  1997 quake.gl.r10k
 582564 12 Feb  1997 quake.sw
 667916 12 Feb  1997 quake.sw.r10k
```

Readme snippet:

```text
Welcome to the SGI port of idsoftware's Quake!
...
- Ed Hutchins
2/11/1997
```


## SGI Quake Binary (Ed Hutchins) v???

Perhaps released as `quake.gl`.

Found in a directory titled `1997-03-25/` suggesting a release date.

binary
?


## SGI Quake (Ed Hutchins) v???


`sgiquake-1997-04.tar.gz`

Announced?

```text
New SGI Quake [Apr 12, 1997, 12:00 pm ET] – Post a Comment
Saw on the Void that there's a new version of SGI Quake available on Quake Utils for SGI Irix.
```

-- https://www.bluesnews.com/s/226446/new-sgi-quake

Links:

* http://www.organism.com/void/
* http://www.webcom.com/phantasm/QUSI/



Archive content:

```text
   3934  9 Apr  1997 LICINFO.TXT
  43292  9 Apr  1997 MANUAL.TXT
   3766  9 Apr  1997 ORDER.TXT
   7951  9 Apr  1997 README.TXT
   1461  9 Apr  1997 quake
 844860  9 Apr  1997 quake.gl
 926212  9 Apr  1997 quake.gl.r10k
 846784  9 Apr  1997 quake.sw
 948212  9 Apr  1997 quake.sw.r10k
```

Readme snippet:

```text
Welcome to the SGI port of idsoftware's Quake!
...
- Ed Hutchins
2/11/1997
```

-- sgiquake-1997-04.tar.gz/README.TXT



## SGI Quake v1.08

Perhaps released as `sgiquake-1997-05-02.tar.gz`.

Announced:

```text
May 2, 1997

SGI Quake 1.08
SGI Quake 1.08 has been released on Quake Utils for SGI Irix. Thanks Thomas Winzig.
```

-- https://www.bluesnews.com/archives/april97-4.html

Links:

* http://www.webcom.com/phantasm/QUSI/



Archive content:

```text
    3934 19 Apr  1997 LICINFO.TXT
   43292 19 Apr  1997 MANUAL.TXT
    3766 19 Apr  1997 ORDER.TXT
    9698 30 Apr  1997 README.TXT
    1461 30 Apr  1997 quake
 1167008 30 Apr  1997 quake.gl
 1191392 30 Apr  1997 quake.gl.r10k
  765020 30 Apr  1997 quake.sw
  857856 30 Apr  1997 quake.sw.r10k
```

Readme snippet:

```text
1.08:	* Fixed R10k executables to load libaudio.so dynamically
	* Optimized all executables (all executables now -n32)
	  This may require some software installation on 6.2 machines
	  as n32 libraries are not installed by default on 6.2.
	  The speedup is well worth it though (5-25%)!
	* Stripped binaries for smaller distribution.
...
- Philip Nemec
4/30/1997
```


## SGI Quake v1.09

Perhaps released as `sgiquake-1997-05-13.tar.gz`.


```text
Wednesday, May 14, 1997

SGI Quake 1.09
SGI Quake 1.09 has been released by Philip Nemec. The new version includes support for Wingman Warrior joysticks, among other things. Available on Quake Utils for SGI Irix. Thanks Thomas Winzig.
```

-- https://www.bluesnews.com/archives/may97-2.html

Links:

* http://www.webcom.com/phantasm/QUSI/



Archive content:

```text
    3934 13 Feb  1997 LICINFO.TXT
   43292 13 Feb  1997 MANUAL.TXT
    3766 13 Feb  1997 ORDER.TXT
   10815 14 May  1997 README.TXT
    1461  9 Apr  1997 quake
 1176144 14 May  1997 quake.gl
  598948 14 May  1997 quake.gl.o32
 1204712 14 May  1997 quake.gl.r10k
  822028 14 May  1997 quake.sw
  590756 14 May  1997 quake.sw.o32
 1286808 14 May  1997 quake.sw.r10k
   24748 13 May  1997 test_wingman_warrior
```

Readme snippet:

```text
1.09:	* Added support for Logitech's WingMan Warrior (serial joystick).
	* Included a WingMan Warrior test program.
	* Included o32 versions for 5.3 and machines missing libraries, etc.
...
```


## SGI Quake v1.10

Perhaps released as `sgiquake-1997-05-21.tar.gz`.


```text
SGI Quake 1.10 [May 22, 1997, 12:00 pm ET] – Post a Comment

Thanks Thomas Winzig for word that Philip Nemec has released SGI Quake 1.10, fixing the bug with lookspring, which didn't work. Available from Quake Utils for SGI Irix.
```

-- https://www.bluesnews.com/s/227017/sgi-quake-1-10

Links:

* http://www.webcom.com/phantasm/QUSI/


Archive content:

```text
    3934 15 May  1997 LICINFO.TXT
   43292 15 May  1997 MANUAL.TXT
    3766 15 May  1997 ORDER.TXT
   11004 22 May  1997 README.TXT
    1461 15 May  1997 quake
 1181320 22 May  1997 quake.gl
  598948 22 May  1997 quake.gl.o32
 1205712 22 May  1997 quake.gl.r10k
  773416 22 May  1997 quake.sw
  590756 22 May  1997 quake.sw.o32
 1287684 22 May  1997 quake.sw.r10k
   24748 15 May  1997 test_wingman_warrior
```

Readme snippet:

```text
1.10:   * Fixed lookspring bug (lookspring value was ignored).
        * Packaged correct binaries (WingMan Warrior support).
...
```

## SGI Quake v1.11

Perhaps released as `sgiquake.tar.gz`.

Archive content:

```text
    3934  9 Apr  1997 LICINFO.TXT
   43292  9 Apr  1997 MANUAL.TXT
    3766  9 Apr  1997 ORDER.TXT
   11367 24 Sep  1997 README.TXT
    1461  9 Apr  1997 quake
 1180676 24 Sep  1997 quake.gl
  598948 24 Sep  1997 quake.gl.o32
 1205124 24 Sep  1997 quake.gl.r10k
  773436 24 Sep  1997 quake.sw
  590756 24 Sep  1997 quake.sw.o32
 1292052 24 Sep  1997 quake.sw.r10k
   24748 22 May  1997 test_wingman_warrior
```

Readme snippet:

```text
1.11:	* Added support for -heapsize parameter - make more add-on levels work.
	* Updated patch information
...
```






## References

* https://en.wikipedia.org/wiki/Silicon_Graphics
* https://en.wikipedia.org/wiki/IRIX
* https://web.archive.org/web/20210310142150/https://sgifiles.irixnet.org/sgi/quake/
* https://www.siliconbunny.com/mirrors/ftp.sgi.com/sgi/quake/
* https://www.siliconbunny.com/mirrors/ftp.sgi.com/sgi/quake/doc/quake1.html
* https://www.siliconbunny.com/mirrors/ftp.sgi.com/sgi/quake/download/quake1/
* http://www.sgidepot.co.uk/quake1bench.html
* https://web.archive.org/web/19980220092553/http://reality.sgi.com/employees/hutchins_asd/
* https://web.archive.org/web/19980701023059/http://www.sgi.com/Fun/free/sgi-quake.html
* https://www.betaarchive.com/forum/viewtopic.php?t=22492
* https://web.archive.org/web/19970617005422/http://reality.sgi.com/hutchins_asd/
* https://web.archive.org/web/19970526005454/http://reality.sgi.com/sgiquake/
* https://ftp.zx.net.nz/pub/archive/ftp.sgi.com/sgi/quake/download/quake1/
* https://ftp.jurassic.nl/mirrors/ftp.sgi.com/sgi/quake/download/quake1/
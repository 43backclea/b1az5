## Git算不算程序员的必备技能？ 5PWTF

更新时间：2026-09-15 06:49:09.929

3ampzz.kvb1991.com
4a969k.ecvyksp.cn
现在dev分支工作已完成，现在我们切换到主分支master上，继续查看readme.txt内容如下：
3ym0zw.inmolopez.com
41kh45.kvb1985.com
Git算不算程序员的必备技能？
32km2m.inmolopez.com
2uuvmo.hothairybushes.com
47tdrl.kvb1985.com
2vu5fc.kvb1992.com
3kvpe5.inmolopez.com
33ego7.compasslandconsultants.com
首先我们先来查看下readme.txt内容，接着添加内容77777777，如下：
39jaa4.kvb1979.com
3atsko.cdroutlet.com
git branch查看分支，会列出所有的分支，当前分支前面会添加一个星号。然后我们在dev分支上继续做demo，比如我们现在在readme.txt再增加一行 7777777777777
3zdvyv.misturabela.com
2x60jn.misturabela.com
44v5x8.kvb1985.com
3iz7ca.kvb1987.com
3i9hk5.cdroutlet.com
3soju9.hothairybushes.com
3fip15.compasslandconsultants.com
git checkout dev
4066yt.cdroutlet.com
3il0ly.kvb1991.com
2s26qz.kvb1992.com
30ik5v.hoodamath2.com
46ac55.hoodamath2.com
git branch dev
3nh2yq.cdroutlet.com
3ls82h.hothairybushes.com
4014gs.inmolopez.com
3nqa1r.kvb1989.com
2lsucz.hothairybushes.com
3jl3s5.kvb1981.com
46qzd0.hoodamath2.com
4gluwo.kvb1980.com
3tq8q1.kvb1997.com
2sd4me.compasslandconsultants.com
3pwk08.kvb1992.com
2xhzbx.cdroutlet.com
3ttuz6.cdroutlet.com
469dw1.kvb1986.com
2na9l0.inmolopez.com
3bu5q2.compasslandconsultants.com
git checkout 命令加上 –b参数表示创建并切换，相当于如下2条命令
2w2p9g.misturabela.com
2veve6.kvb1993.com
39zdf3.ecvyksp.cn
2s6sp1.kvb1996.com
3ylfvo.inmolopez.com
Git算不算程序员的必备技能？
3we494.kvb1980.com
2zliiy.hothairybushes.com
首先，我们来创建dev分支，然后切换到dev分支上。如下操作：
3bxnyw.kvb1998.com
在 版本回填退里，你已经知道，每次提交，Git都把它们串成一条时间线，这条时间线就是一个分支。截止到目前，只有一条时间线，在Git里，这个分支叫主分支，即master分支。HEAD严格来说不是指向提交，而是指向master，master才是指向提交的，所以，HEAD指向的就是当前分支。
2uru62.inmolopez.com
3ypl06.hongyihualang.cn
2ui4cp.kvb1986.com
六：创建与合并分支。
3uiesj.kvb1992.com
Git算不算程序员的必备技能？
2yxz3p.kvb1998.com
接着在我本地目录下 生成testgit2目录了，如下所示：
3m8sfg.compasslandconsultants.com
3hwaqg.kvb1979.com
2xv60x.hoodamath2.com
3ycncv.hothairybushes.com
3ao6vb.kvb1989.com
Git算不算程序员的必备技能？
2z7jfg.kvb1980.com
3fgud8.kvb1991.com
3hbksq.misturabela.com
3ecylx.hothairybushes.com
305a5s.hothairybushes.com
2vmt66.kvb1993.com
现在，远程库已经准备好了，下一步是使用命令git clone克隆一个本地库了。如下所示：
2u3744.hothairybushes.com
47bldb.hoodamath2.com
4gk6y2.kvb1985.com
Git算不算程序员的必备技能？
49lsut.kvb1992.com
2ndp49.hongyihualang.cn
如下，我们看到：
46gday.hoodamath2.com
3zl9h2.compasslandconsultants.com
348x8f.compasslandconsultants.com
39uwql.cdroutlet.com
Git算不算程序员的必备技能？
2pmce9.compasslandconsultants.com
首先，登录github，创建一个新的仓库，名字叫testgit2.如下：
3h5fok.kvb1982.com
48qx1s.hoodamath2.com
4ghsea.kvb1979.com
现在我们想，假如远程库有新的内容了，我想克隆到本地来 如何克隆呢？
45xohf.kvb1981.com
3swklq.hongyihualang.cn
47pjdv.kvb1982.com
如何从远程库克隆？上面我们了解了先有本地库，后有远程库时候，如何关联远程库。
2t6a3u.kvb1996.com
42z62a.hothairybushes.com
2sjdwg.kvb1978.com
3xez66.kvb1997.com
把本地master分支的最新修改推送到github上了，现在你就拥有了真正的分布式版本库了。
42lo7v.hongyihualang.cn
3d3dlv.hongyihualang.cn
git push origin master
35ccfc.ecvyksp.cn
2vfwtm.kvb1982.com
499xqq.misturabela.com
2tvd7i.hoodamath2.com
3epky0.kvb1981.com
从现在起，只要本地作了提交，就可以通过如下命令：
40qx0f.kvb1988.com
3qpxrc.kvb1992.com
3527ca.kvb1997.com
Git算不算程序员的必备技能？
306s4x.kvb1990.com
444x9v.kvb1981.com
由于远程库是空的，我们第一次推送master分支时，加上了 –u参数，Git不但会把本地的master分支内容推送的远程新的master分支，还会把本地的master分支和远程的master分支关联起来，在以后的推送或者拉取时就可以简化命令。推送成功后，可以立刻在github页面中看到远程库的内容已经和本地一模一样了，上面的要输入github的用户名和密码如下所示：
3jp2s6.kvb1990.com
35t36z.hongyihualang.cn
把本地库的内容推送到远程，使用 git push命令，实际上是把当前分支master推送到远程。
3wq61u.kvb1991.com
2wzvg8.kvb1989.com
Git算不算程序员的必备技能？
4e0y52.kvb1995.com
2qtvrm.kvb1985.com
4iye34.kvb1978.com
422max.kvb1997.com
所有的如下：
4dm65n.kvb1997.com
332hk3.cdroutlet.com
git remote add origin
3x0ehw.hothairybushes.com
30uq7l.kvb1992.com
现在，我们根据GitHub的提示，在本地的testgit仓库下运行命令：
2z3f20.kvb1991.com
48utow.compasslandconsultants.com
48i0ay.kvb1999.com
443a31.ecvyksp.cn
目前，在GitHub上的这个testgit仓库还是空的，GitHub告诉我们，可以从这个仓库克隆出新的仓库，也可以把一个已有的本地仓库与之关联，然后，把本地仓库的内容推送到GitHub仓库。
4ig44l.kvb1978.com
3vixyd.hoodamath2.com
2udra8.kvb1998.com
2rwjgb.hoodamath2.com
Git算不算程序员的必备技能？
3ufxg8.kvb1978.com
3qjjje.kvb1980.com
2u71hz.hoodamath2.com
3w69qq.hoodamath2.com
3fm26c.ecvyksp.cn
3stxn2.kvb1978.com
在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库：
3u6eik.hongyihualang.cn
Git算不算程序员的必备技能？
34siqa.hothairybushes.com
首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。如下：
3yxi2b.kvb1982.com
2lmafx.hoodamath2.com
现在的情景是：我们已经在本地创建了一个Git仓库后，又想在github创建一个Git仓库，并且希望这两个仓库进行远程同步，这样github的仓库可以作为备份，又可以其他人通过该仓库来协作。
2vwqc8.kvb1979.com
如何添加远程库？
4e1hon.kvb1980.com
2whquf.kvb1985.com
43qjjo.kvb1995.com
3r407e.misturabela.com
Git算不算程序员的必备技能？
2qch4f.kvb1982.com
3cl9bl.kvb1998.com
点击 Add Key，你就应该可以看到已经添加的key。
2xpl7c.kvb1979.com
Git算不算程序员的必备技能？
32eb1x.kvb1992.com
第二步：登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
3igicp.kvb1996.com
id_rsa是私钥，不能泄露出去，id_rsa.pub是公钥，可以放心地告诉任何人。
32kl2x.kvb1988.com
33xvud.hongyihualang.cn
Git算不算程序员的必备技能？
3y3ofs.inmolopez.com
ssh-keygen -t rsa –C “youremail@example.com”, 由于我本地此前运行过一次，所以本地有，如下所示：
329e1r.kvb1995.com
2z1fu0.compasslandconsultants.com
第一步：创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件，如果有的话，直接跳过此如下命令，如果没有的话，打开命令行，输入如下命令：
3dre9n.kvb1987.com
在了解之前，先注册github账号，由于你的本地Git仓库和github仓库之间的传输是通过SSH加密的，所以需要一点设置：
4bdfls.kvb1986.com
五：远程仓库。
3u358c.misturabela.com
2y4y18.kvb1989.com
42gudh.kvb1987.com
3h9mcq.kvb1982.com
3n9e03.kvb1995.com
39wm63.kvb1995.com
2tb6tx.compasslandconsultants.com
Git算不算程序员的必备技能？
4cgdrn.kvb1995.com
再来看看我们testgit目录，添加了3个文件了。如下所示：
2yf6fv.cdroutlet.com
2tkozj.kvb1993.com
2mcuh4.hoodamath2.com
Git算不算程序员的必备技能？
2xua0y.kvb1991.com
可以使用如下命令 git checkout -- b.txt，如下所示：
49kp4c.kvb1986.com
3xnalb.hongyihualang.cn
31u212.hoodamath2.com
2nky7l.ecvyksp.cn
337he5.kvb1991.com
47aidi.cdroutlet.com
376glo.kvb1991.com
34ywzk.hothairybushes.com
3k0vux.inmolopez.com
364e4e.kvb1992.com
只要没有commit之前，如果我想在版本库中恢复此文件如何操作呢？
44bwxy.hoodamath2.com
33wklv.kvb1980.com
Git算不算程序员的必备技能？
3kz670.hothairybushes.com
33gv9o.misturabela.com
如上：一般情况下，可以直接在文件目录中把文件删了，或者使用如上rm命令：rm b.txt ，如果我想彻底从版本库中删掉了此文件的话，可以再执行commit命令 提交掉，现在目录是这样的，
3rtfd2.kvb1985.com
Git算不算程序员的必备技能？
40rvip.compasslandconsultants.com
假如我现在版本库testgit目录添加一个文件b.txt,然后提交。如下：
37m3td.inmolopez.com
4946u6.kvb1999.com
2q6r4c.kvb1983.com
30545t.ecvyksp.cn
二：删除文件。
31qg9b.kvb1996.com
3ik8zd.kvb1979.com
2sstgm.kvb1995.com
4ahmaa.hongyihualang.cn
3tv8in.kvb1997.com
3927kt.misturabela.com
注意：命令git checkout -- readme.txt 中的 -- 很重要，如果没有 -- 的话，那么命令变成创建分支了。
3z478d.kvb1995.com
Git算不算程序员的必备技能？
323l6v.cdroutlet.com
4454yz.cdroutlet.com
393mp6.kvb1998.com
3z95lt.misturabela.com
3m73t4.kvb1986.com
2wucea.kvb1999.com
49ihjw.ecvyksp.cn
33f5u3.kvb1983.com
对于第二种情况，我想我们继续做demo来看下，假如现在我对readme.txt添加一行 内容为6666666666666，我git add 增加到暂存区后，接着添加内容7777777，我想通过撤销命令让其回到暂存区后的状态。如下所示：
2uq0lo.kvb1993.com
2.另外一种是readme.txt已经放入暂存区了，接着又作了修改，撤销修改就回到添加暂存区后的状态。
334t90.kvb1996.com
2qk28p.misturabela.com
351qz0.ecvyksp.cn
3k4694.kvb1985.com
35ig7y.hongyihualang.cn
1.readme.txt自动修改后，还没有放到暂存区，使用 撤销修改就回到和版本库一模一样的状态。
4daxb9.kvb1979.com
3739i1.kvb1978.com
2s4g34.kvb1995.com
3ya518.compasslandconsultants.com
3go5yx.ecvyksp.cn
3915wg.misturabela.com
35aed8.cdroutlet.com
命令 git checkout --readme.txt 意思就是，把readme.txt文件在工作区做的修改全部撤销，这里有2种情况，如下：
2s1v2r.hoodamath2.com
4aouyg.kvb1998.com
36u989.kvb1993.com
3z2451.ecvyksp.cn
3v5drb.kvb1985.com
Git算不算程序员的必备技能？
3recu3.kvb1982.com
git checkout -- readme.txt,如下所示：
3bv8c0.inmolopez.com
3oi2i8.kvb1980.com
31nrs8.kvb1988.com
可以发现，Git会告诉你，git checkout -- file 可以丢弃工作区的修改，如下命令：
2w6zwx.kvb1992.com
3z8nzh.kvb1999.com
2s6x58.kvb1987.com
Git算不算程序员的必备技能？
2ycvzq.misturabela.com
但是现在我不想使用上面的2种方法，我想直接想使用撤销命令该如何操作呢？首先在做撤销之前，我们可以先用 git status 查看下当前的状态。如下所示：
4bqd7g.kvb1987.com
3u8w47.kvb1988.com
3sw447.kvb1995.com
2rh5q0.kvb1992.com
第二：我可以按以前的方法直接恢复到上一个版本。使用 git reset --hard HEAD^
300n5s.compasslandconsultants.com
第一：如果我知道要删掉那些内容的话，直接手动更改去掉那些需要的文件，然后add添加到暂存区，最后commit掉。
2vn1fi.kvb1981.com
在我未提交之前，我发现添加5555555555555内容有误，所以我得马上恢复以前的版本，现在我可以有如下几种方法可以做修改：
3n5xq3.inmolopez.com
416azi.hoodamath2.com
Git算不算程序员的必备技能？
3btv8o.kvb1997.com
4er77l.kvb1993.com
比如我现在在readme.txt文件里面增加一行 内容为555555555555，我们先通过命令查看如下：
3z94q3.kvb1988.com
4e9t0b.kvb1982.com
32cg96.hoodamath2.com
一：撤销修改：
3m879e.misturabela.com
2s3p4y.hothairybushes.com
3vczrm.kvb1993.com
37mwe2.hongyihualang.cn
四：Git撤销修改和删除文件操作。
4iv2w6.kvb1996.com
Git算不算程序员的必备技能？
2t4wdf.kvb1998.com
3w2rjg.hothairybushes.com
接着我们可以使用git commit一次性提交到分支上，如下：
42it53.hothairybushes.com
Git算不算程序员的必备技能？
2ny852.inmolopez.com
3c1dov.hongyihualang.cn
345set.hothairybushes.com
412l6q.inmolopez.com
3c1c7r.hoodamath2.com
现在我们先使用git add 命令把2个文件都添加到暂存区中，再使用git status来查看下状态，如下：
3jcfrt.misturabela.com
30r4m1.kvb1983.com
Git算不算程序员的必备技能？
3va3c3.kvb1987.com
我们在readme.txt再添加一行内容为4444444，接着在目录下新建一个文件为test.txt 内容为test，我们先用命令 git status来查看下状态，如下：
48fjas.hongyihualang.cn
4dybu2.kvb1986.com
我们继续使用demo来演示下：
39ihtl.hongyihualang.cn
第二步：使用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支上。
4gnklr.kvb1991.com
42e7i3.kvb1991.com
第一步：是使用 git add 把文件添加进去，实际上就是把文件添加到暂存区。
3qcih9.hoodamath2.com
3cwgqv.kvb1986.com
我们前面说过使用Git提交文件到版本库有两步：
45yhdz.cdroutlet.com
3erumg.hothairybushes.com
2y6ex8.inmolopez.com
3wb82h.kvb1986.com
3iw2de.kvb1995.com
版本库(Repository)：工作区有一个隐藏目录.git,这个不属于工作区，这是版本库。其中版本库里面存了很多东西，其中最重要的就是stage(暂存区)，还有Git为我们自动创建了第一个分支master,以及指向master的一个指针HEAD。
2rndp1.ecvyksp.cn
451mo2.kvb1978.com
工作区：就是你在电脑上看到的目录，比如目录下testgit里的文件(.git隐藏目录版本库除外)。或者以后需要再新建的目录文件等等都属于工作区范畴。
49mkx9.ecvyksp.cn
2wxj2z.hongyihualang.cn
三：理解工作区与暂存区的区别？
3hj3bm.inmolopez.com
3xfk5b.cdroutlet.com
可以看到 目前已经是最新的版本了。
36uc1z.kvb1981.com
3seamp.kvb1979.com
457fy8.kvb1990.com
43p4yu.kvb1989.com
3lvvjb.kvb1995.com
Git算不算程序员的必备技能？
49l3bm.kvb1986.com
3umg8b.kvb1993.com
417sz1.compasslandconsultants.com
3qfszz.kvb1993.com
3eq3sw.kvb1995.com
3sxzu2.misturabela.com
36rk8s.hothairybushes.com
2z4vyx.kvb1986.com
3irro9.compasslandconsultants.com
2y3imy.kvb1991.com
git reset --hard 6fcfc89来恢复了。演示如下：
34hgaj.ecvyksp.cn
通过上面的显示我们可以知道，增加内容3333的版本号是 6fcfc89.我们现在可以命令
3oh3lf.kvb1996.com
45g3wr.kvb1987.com
3c0whh.kvb1998.com
3nq9b9.kvb1999.com
2xo7xl.kvb1979.com
Git算不算程序员的必备技能？
3yhyjn.hoodamath2.com
git reset --hard 版本号 ，但是现在的问题假如我已经关掉过一次命令行或者333内容的版本号我并不知道呢？要如何知道增加3333内容的版本号呢？可以通过如下命令即可获取到版本号：git reflog 演示如下：
3r6d2p.ecvyksp.cn
3jbncx.kvb1983.com
45ubc9.ecvyksp.cn
3u3a5c.cdroutlet.com
2mo5tr.compasslandconsultants.com
我们看到 增加333333 内容我们没有看到了，但是现在我想回退到最新的版本，如：有333333的内容要如何恢复呢？我们可以通过版本号回退，使用命令方法如下：
2t4olt.kvb1997.com
Git算不算程序员的必备技能？
3modwd.kvb1996.com
可以看到，内容已经回退到上一个版本了。我们可以继续使用git log 来查看下历史记录信息，如下：
3aslw3.kvb1995.com
43xo38.hothairybushes.com
2qg599.kvb1979.com
Git算不算程序员的必备技能？
3hzwd9.kvb1987.com
3c24xg.misturabela.com
3y7kh6.hongyihualang.cn
再来查看下 readme.txt内容如下：通过命令cat readme.txt查看
416mcf.kvb1995.com
4126cw.kvb1983.com

---

# b1az5
Auto-created repository for publishing - 2026-09-15T06:48:46.884Z

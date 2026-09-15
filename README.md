## Git算不算程序员的必备技能？ A195HCPW0F

更新时间：2026-09-15 07:00:53.814

Git算不算程序员的必备技能？
366tis.misturabela.com
在Repository name填入testgit，其他保持默认设置，点击“Create repository”按钮，就成功地创建了一个新的Git仓库：
3t3m50.kvb1999.com
3oz4vx.hoodamath2.com
3itlit.kvb1993.com
49odt1.hothairybushes.com
Git算不算程序员的必备技能？
2rg2fr.kvb1982.com
首先，登录github上，然后在右上角找到“create a new repo”创建一个新的仓库。如下：
3wk38z.compasslandconsultants.com
现在的情景是：我们已经在本地创建了一个Git仓库后，又想在github创建一个Git仓库，并且希望这两个仓库进行远程同步，这样github的仓库可以作为备份，又可以其他人通过该仓库来协作。
3hfeek.hongyihualang.cn
491j24.hoodamath2.com
如何添加远程库？
39g2n3.hongyihualang.cn
2uctkj.kvb1985.com
43u2f9.hoodamath2.com
Git算不算程序员的必备技能？
32fdws.kvb1999.com
点击 Add Key，你就应该可以看到已经添加的key。
363h8p.cdroutlet.com
35vjkm.misturabela.com
3zmer8.compasslandconsultants.com
Git算不算程序员的必备技能？
48jy0l.hoodamath2.com
352am2.ecvyksp.cn
49r50r.inmolopez.com
3uay80.kvb1986.com
第二步：登录github,打开” settings”中的SSH Keys页面，然后点击“Add SSH Key”,填上任意title，在Key文本框里黏贴id_rsa.pub文件的内容。
3ev8mv.kvb1993.com
id_rsa是私钥，不能泄露出去，id_rsa.pub是公钥，可以放心地告诉任何人。
2ql59o.hothairybushes.com
36ldax.kvb1998.com
442q2q.kvb1999.com
44ghuw.kvb1991.com
2w3krt.kvb1993.com
40h0pk.kvb1988.com
2qqjnp.kvb1978.com
4ig9ui.kvb1985.com
3os6vy.kvb1990.com
34daea.hongyihualang.cn
3ubb8a.kvb1995.com
Git算不算程序员的必备技能？
325x67.hoodamath2.com
2wvjt4.kvb1989.com
3anmwy.kvb1980.com
46r4xe.cdroutlet.com
3fwmor.cdroutlet.com
3mk6cu.kvb1998.com
ssh-keygen -t rsa –C “youremail@example.com”, 由于我本地此前运行过一次，所以本地有，如下所示：
2td8m6.kvb1987.com
2qqklg.kvb1991.com
2znpgm.cdroutlet.com
第一步：创建SSH Key。在用户主目录下，看看有没有.ssh目录，如果有，再看看这个目录下有没有id_rsa和id_rsa.pub这两个文件，如果有的话，直接跳过此如下命令，如果没有的话，打开命令行，输入如下命令：
4a5rni.kvb1981.com
在了解之前，先注册github账号，由于你的本地Git仓库和github仓库之间的传输是通过SSH加密的，所以需要一点设置：
47hrna.hoodamath2.com
2lx66q.hothairybushes.com
3f4fka.kvb1980.com
3dy5p6.ecvyksp.cn
2vsi1j.compasslandconsultants.com
35y7z9.kvb1989.com
48xk0x.cdroutlet.com
3mwh19.kvb1993.com
3588vn.kvb1979.com
五：远程仓库。
4fkh2u.kvb1987.com
3pmj0f.kvb1987.com
Git算不算程序员的必备技能？
45qahw.ecvyksp.cn
再来看看我们testgit目录，添加了3个文件了。如下所示：
4ep2e1.kvb1987.com
Git算不算程序员的必备技能？
2wslds.compasslandconsultants.com
49qnp7.kvb1990.com
3mc496.kvb1980.com
2t71or.kvb1999.com
可以使用如下命令 git checkout -- b.txt，如下所示：
3e6n3d.misturabela.com
只要没有commit之前，如果我想在版本库中恢复此文件如何操作呢？
3rf7k4.kvb1998.com
3ov613.inmolopez.com
Git算不算程序员的必备技能？
3e0gyf.kvb1999.com
如上：一般情况下，可以直接在文件目录中把文件删了，或者使用如上rm命令：rm b.txt ，如果我想彻底从版本库中删掉了此文件的话，可以再执行commit命令 提交掉，现在目录是这样的，
46uqxo.kvb1983.com
3e8vbi.compasslandconsultants.com
Git算不算程序员的必备技能？
2ryeg4.ecvyksp.cn
3693mn.hongyihualang.cn
假如我现在版本库testgit目录添加一个文件b.txt,然后提交。如下：
46ealw.hoodamath2.com
二：删除文件。
3r8m5n.hongyihualang.cn
注意：命令git checkout -- readme.txt 中的 -- 很重要，如果没有 -- 的话，那么命令变成创建分支了。
3ozvdy.misturabela.com
48jdd1.ecvyksp.cn
3ut2lg.kvb1995.com
42towq.kvb1992.com
3mf5ms.hothairybushes.com
Git算不算程序员的必备技能？
2yeqw3.hoodamath2.com
3tl5ax.cdroutlet.com
3a1gpm.hoodamath2.com
对于第二种情况，我想我们继续做demo来看下，假如现在我对readme.txt添加一行 内容为6666666666666，我git add 增加到暂存区后，接着添加内容7777777，我想通过撤销命令让其回到暂存区后的状态。如下所示：
38n8tq.inmolopez.com
2.另外一种是readme.txt已经放入暂存区了，接着又作了修改，撤销修改就回到添加暂存区后的状态。
2x4qrj.kvb1990.com
3q6hah.hothairybushes.com
4e9xxd.kvb1980.com
3pbsjs.hongyihualang.cn
1.readme.txt自动修改后，还没有放到暂存区，使用 撤销修改就回到和版本库一模一样的状态。
36tcbw.cdroutlet.com
2pzm19.ecvyksp.cn
命令 git checkout --readme.txt 意思就是，把readme.txt文件在工作区做的修改全部撤销，这里有2种情况，如下：
3651el.inmolopez.com
2usk2b.kvb1998.com
3sice6.misturabela.com
Git算不算程序员的必备技能？
3r2yz0.kvb1993.com
3dj0uo.cdroutlet.com
4i0r9o.kvb1991.com
2y62ss.ecvyksp.cn
48ywlh.compasslandconsultants.com
git checkout -- readme.txt,如下所示：
44y7oq.misturabela.com
49ms5s.kvb1991.com
可以发现，Git会告诉你，git checkout -- file 可以丢弃工作区的修改，如下命令：
3bskfd.hothairybushes.com
38ac86.ecvyksp.cn
418387.hongyihualang.cn
Git算不算程序员的必备技能？
37u4da.kvb1992.com
但是现在我不想使用上面的2种方法，我想直接想使用撤销命令该如何操作呢？首先在做撤销之前，我们可以先用 git status 查看下当前的状态。如下所示：
2tw3iw.kvb1983.com
3hxfe7.inmolopez.com
3o0k4b.cdroutlet.com
3zzt9d.ecvyksp.cn
第二：我可以按以前的方法直接恢复到上一个版本。使用 git reset --hard HEAD^
2ped5n.hongyihualang.cn
3ciqhe.kvb1991.com
3gca5j.misturabela.com
第一：如果我知道要删掉那些内容的话，直接手动更改去掉那些需要的文件，然后add添加到暂存区，最后commit掉。
3mlppy.hothairybushes.com
在我未提交之前，我发现添加5555555555555内容有误，所以我得马上恢复以前的版本，现在我可以有如下几种方法可以做修改：
489f59.kvb1986.com
34fvqp.hongyihualang.cn
2rbluc.hoodamath2.com
34fpb6.kvb1981.com
2wz95m.ecvyksp.cn
4hpy4q.kvb1980.com
Git算不算程序员的必备技能？
4czwef.kvb1979.com
2tdtbw.kvb1998.com
比如我现在在readme.txt文件里面增加一行 内容为555555555555，我们先通过命令查看如下：
41n2bt.kvb1990.com
4gi7sh.kvb1981.com
3x2k4o.hongyihualang.cn
385pa4.kvb1995.com
一：撤销修改：
4aff29.ecvyksp.cn
四：Git撤销修改和删除文件操作。
3olq7o.kvb1995.com
Git算不算程序员的必备技能？
3m7rtg.kvb1985.com
3oz2yf.kvb1985.com
2rnonp.hoodamath2.com
3gdlst.kvb1991.com
44qek2.kvb1996.com
46caxo.kvb1980.com
3p0hvb.kvb1993.com
324m8k.kvb1993.com
接着我们可以使用git commit一次性提交到分支上，如下：
3ltus8.cdroutlet.com
3yjhcz.compasslandconsultants.com
Git算不算程序员的必备技能？
2spff4.hongyihualang.cn
3sxt76.hothairybushes.com
现在我们先使用git add 命令把2个文件都添加到暂存区中，再使用git status来查看下状态，如下：
300ldi.kvb1982.com
3yx2az.compasslandconsultants.com
Git算不算程序员的必备技能？
2x467d.kvb1985.com
2z4kn4.inmolopez.com
469tvi.kvb1981.com
32pm32.kvb1996.com
我们在readme.txt再添加一行内容为4444444，接着在目录下新建一个文件为test.txt 内容为test，我们先用命令 git status来查看下状态，如下：
3vgy2l.kvb1990.com
2xxzpw.kvb1997.com
2r5jvd.compasslandconsultants.com
我们继续使用demo来演示下：
432kr5.kvb1982.com
第二步：使用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支上。
45xgah.kvb1978.com
第一步：是使用 git add 把文件添加进去，实际上就是把文件添加到暂存区。
315lbh.misturabela.com
43v1vq.misturabela.com
2s2sct.kvb1989.com
我们前面说过使用Git提交文件到版本库有两步：
3skh1y.ecvyksp.cn
44ztyb.kvb1978.com
2lsyi1.inmolopez.com
4943h4.kvb1992.com
2t39uo.inmolopez.com
33glym.ecvyksp.cn
3w7sgg.kvb1985.com
3w18pd.compasslandconsultants.com
4euo8h.kvb1990.com
3v7cma.kvb1993.com
3qszpc.hongyihualang.cn
3c3mkw.hothairybushes.com
3ej1i1.ecvyksp.cn
3eaoxw.kvb1981.com
3xnnaq.misturabela.com
版本库(Repository)：工作区有一个隐藏目录.git,这个不属于工作区，这是版本库。其中版本库里面存了很多东西，其中最重要的就是stage(暂存区)，还有Git为我们自动创建了第一个分支master,以及指向master的一个指针HEAD。
3i3nfl.kvb1981.com
3otjcg.hoodamath2.com
30w85z.kvb1992.com
3uzrk5.kvb1990.com
工作区：就是你在电脑上看到的目录，比如目录下testgit里的文件(.git隐藏目录版本库除外)。或者以后需要再新建的目录文件等等都属于工作区范畴。
380jau.kvb1978.com
三：理解工作区与暂存区的区别？
2veag7.kvb1988.com
42pq7h.inmolopez.com
可以看到 目前已经是最新的版本了。
3gser2.hongyihualang.cn
3vivtt.kvb1998.com
Git算不算程序员的必备技能？
2wqav2.compasslandconsultants.com
2rhvu5.hoodamath2.com
3h7kkc.misturabela.com
2sxq1j.kvb1981.com
489nur.kvb1997.com
3oj5tq.hothairybushes.com
4bgkcw.kvb1988.com
347gp9.compasslandconsultants.com
git reset --hard 6fcfc89来恢复了。演示如下：
3kqaue.ecvyksp.cn
通过上面的显示我们可以知道，增加内容3333的版本号是 6fcfc89.我们现在可以命令
45q3js.compasslandconsultants.com
Git算不算程序员的必备技能？
45bi9h.kvb1990.com
git reset --hard 版本号 ，但是现在的问题假如我已经关掉过一次命令行或者333内容的版本号我并不知道呢？要如何知道增加3333内容的版本号呢？可以通过如下命令即可获取到版本号：git reflog 演示如下：
45hq0b.hongyihualang.cn
49kqa7.inmolopez.com
3aufrr.kvb1999.com
3lf4g5.kvb1998.com
3advf6.inmolopez.com
3ltsws.kvb1992.com
2q6q8j.kvb1982.com
3pziaf.kvb1992.com
我们看到 增加333333 内容我们没有看到了，但是现在我想回退到最新的版本，如：有333333的内容要如何恢复呢？我们可以通过版本号回退，使用命令方法如下：
3otwkb.kvb1982.com
Git算不算程序员的必备技能？
4a14sw.misturabela.com
可以看到，内容已经回退到上一个版本了。我们可以继续使用git log 来查看下历史记录信息，如下：
45hrah.kvb1998.com
47c15b.inmolopez.com
4i94ka.kvb1993.com
3ch3yt.misturabela.com
3izw5d.hongyihualang.cn
3xs5ey.inmolopez.com
Git算不算程序员的必备技能？
42qf0c.cdroutlet.com
再来查看下 readme.txt内容如下：通过命令cat readme.txt查看
3hwq8t.misturabela.com
Git算不算程序员的必备技能？
33t6c5.misturabela.com
3ii2w9.inmolopez.com
如果想回退到上一个版本的命令如下操作：
487gxp.kvb1999.com
2wij42.inmolopez.com
2n391c.compasslandconsultants.com
33163c.kvb1989.com
Git算不算程序员的必备技能？
43k1h4.kvb1993.com
3aa13s.compasslandconsultants.com
2rkof1.hongyihualang.cn
3ggj90.kvb1997.com
2szir1.hothairybushes.com
2rl8um.inmolopez.com
现在我想使用版本回退操作，我想把当前的版本回退到上一个版本，要使用什么命令呢？可以使用如下2种命令，第一种是：git reset --hard HEAD^ 那么如果要回退到上上个版本只需把HEAD^ 改成 HEAD^^ 以此类推。那如果要回退到前100个版本的话，使用上面的方法肯定不方便，我们可以使用下面的简便命令操作：git reset --hard HEAD~100 即可。未回退之前的readme.txt内容如下：
3afodf.hoodamath2.com
Git算不算程序员的必备技能？
466005.compasslandconsultants.com
4bi1u8.kvb1993.com
3shjyu.kvb1988.com
2ylfum.kvb1999.com
git log命令显示从最近到最远的显示日志，我们可以看到最近三次提交，最近的一次是,增加内容为333333.上一次是添加内容222222，第一次默认是 111111.如果嫌上面显示的信息太多的话，我们可以使用命令 git log –pretty=oneline 演示如下：
47tj1m.kvb1981.com
41vsah.ecvyksp.cn
Git算不算程序员的必备技能？
3jecl3.kvb1992.com
4aizwf.kvb1985.com
3qhfnl.kvb1997.com
3guo8q.kvb1985.com
现在我已经对readme.txt文件做了三次修改了，那么我现在想查看下历史记录，如何查呢？我们现在可以使用命令 git log 演示如下所示：
38gjpz.hongyihualang.cn
2qa7wa.hothairybushes.com
Git算不算程序员的必备技能？
3q3c1u.misturabela.com
内容为33333333333333.继续执行命令如下：
35q8b5.kvb1995.com
3uuvhl.kvb1985.com
3a7trk.hongyihualang.cn
如上，我们已经学会了修改文件，现在我继续对readme.txt文件进行修改，再增加一行
2rm7fs.hongyihualang.cn
2sfrf4.kvb1978.com
42f1ri.kvb1988.com
二：版本回退：
3ud2sy.kvb1998.com
31phfs.kvb1999.com
2mssd4.hongyihualang.cn
387oi5.misturabela.com
3axp4y.inmolopez.com
Git算不算程序员的必备技能？
3k92se.hoodamath2.com
44nvcl.inmolopez.com
37oq3s.hothairybushes.com
如下：
41c288.kvb1991.com
306v73.kvb1989.com
2snbc8.kvb1999.com
知道了对readme.txt文件做了什么修改后，我们可以放心的提交到仓库了，提交修改和提交文件是一样的2步(第一步是git add 第二步是：git commit)。
40nid7.ecvyksp.cn
4g2lh9.kvb1978.com
46w4n2.kvb1980.com
3prida.kvb1993.com
2oyxi2.hongyihualang.cn
4ge4od.kvb1982.com
如上可以看到，readme.txt文件内容从一行11111111改成 二行 添加了一行22222222内容。
2th12n.kvb1997.com
43f5fw.hongyihualang.cn
3ztv3c.kvb1995.com
3pp0je.compasslandconsultants.com
3sd3yp.kvb1989.com
43f5wt.hothairybushes.com
3hmncg.kvb1998.com
4ac664.kvb1978.com
Git算不算程序员的必备技能？
3v88ck.kvb1979.com
3q9psw.kvb1999.com
git diff readme.txt 如下：
3s02kg.kvb1981.com
3swk9v.inmolopez.com
接下来我想看下readme.txt文件到底改了什么内容，如何查看呢？可以使用如下命令：
35uw7a.hoodamath2.com
2qmmnr.kvb1985.com
4dplw3.kvb1989.com
2y3x0g.hoodamath2.com
35m8vs.kvb1980.com
408do3.misturabela.com
49c01v.kvb1998.com
433v2y.kvb1978.com
上面的命令告诉我们 readme.txt文件已被修改，但是未被提交的修改。
49zlyo.kvb1985.com
3tsy52.kvb1991.com
4cywx2.kvb1995.com
2xjauq.ecvyksp.cn
2qxg4s.hothairybushes.com
3qp1cn.kvb1997.com
Git算不算程序员的必备技能？
2uayhk.cdroutlet.com
说明没有任何文件未提交，但是我现在继续来改下readme.txt内容，比如我在下面添加一行2222222222内容，继续使用git status来查看下结果，如下：
34ebly.compasslandconsultants.com
Git算不算程序员的必备技能？
3c44co.kvb1990.com
2wf79m.kvb1987.com
现在我们已经提交了一个readme.txt文件了，我们下面可以通过命令git status来查看是否还有文件未提交，如下：
43laym.hongyihualang.cn
43dizk.kvb1993.com
Git算不算程序员的必备技能？
47ryl6.misturabela.com
3t8ycu.hongyihualang.cn
31787e.compasslandconsultants.com
2zhh8e.ecvyksp.cn
第二步：用命令 git commit告诉Git，把文件提交到仓库。
3l10fc.kvb1987.com
4j2nkm.kvb1996.com
3wgt2m.misturabela.com
如果和上面一样，没有任何提示，说明已经添加成功了。
2nb5kt.cdroutlet.com
3sswyo.kvb1987.com
3j9z3c.kvb1989.com
Git算不算程序员的必备技能？
3spmus.kvb1993.com
第一步：使用命令 git add readme.txt添加到暂存区里面去。如下：
3e7wmr.kvb1992.com
36rsy9.kvb1979.com
42id5u.hothairybushes.com
2wv08n.ecvyksp.cn
3v6ueg.hoodamath2.com
4d6ulq.kvb1998.com
我在版本库testgit目录下新建一个记事本文件 readme.txt 内容如下：11111111
46qnq6.kvb1991.com
2yesfc.kvb1983.com
下面先看下demo如下演示：
41p6ny.hothairybushes.com
把文件添加到版本库中。首先要明确下，所有的版本控制系统，只能跟踪文本文件的改动，比如txt文件，网页，所有程序的代码等，Git也不列外，版本控制系统可以告诉你每次的改动，但是图片，视频这些二进制文件，虽能也能由版本控制系统管理，但没法跟踪文件的变化，只能把二进制文件每次改动串起来，也就是知道图片从1kb变成2kb，但是到底改了啥，版本控制也不知道。

---

# ddv74
Auto-created repository for publishing - 2026-09-15T07:00:48.030Z

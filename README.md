## Learn git 


> git ����
 - �汾����
   - ����
   - �ָ�
 - ��֧����(Эͬ����)

### ��ʼ��
`git clone`

`git init`


### �汾����

��������
 - ������
 - �ݴ���
 - git�ֿ�(Զ�ֿ̲�)
 
 ![Alt text](./img/areas.png)

����״̬
- δ����(Untracked)(�������ļ�)
- �Ѹ���(Tracked)(�������ļ�)
- δ�޸�(Origin)
- ���޸�(Modified)
- ���ݴ�(Staged)
- ���ύ(Committed)
- ������(Pushed)

Git ��������
![Alt text](./img/lifecycle.png)


#### �ļ�״̬
**`git add`**
> ���ļ��ύ���ݴ���

**.gitignore�ļ�**
> ֧��ͨ���..

`git status`
> ������ʾ���������ݴ����ı仯

`git diff`
> �Ƚϵ��ǹ�����**���޸�**��**��ʼ״̬**������(��δ�ݴ�ĸĶ�)

 `git diff --cached`
> �Ƚϵ��� **���زֿ�** �� **�ݴ���**������

`git log`

**`git commit`**
 - -m �ύ��Ϣ
 - -a �����ݴ� 
 - \- -amend �����ύ
 
#### ���ֳ���(�ĸ��׶�)
##### ���޸� δ�ݴ�
`git checkout .` 
> �Ƚϼ��� `git add .`

`git reset --hard`
##### ���ݴ� δ�ύ
`git reset` + `git checkout .`
>  git reset ���˻���git add .֮���״̬ git checkout .�˻���δ�޸�״̬

`git reset --hard`
> ͬ��һ��

---
##### ���ύ δ����
`git reset --hard origin/master`
##### ������
`git reset --hard HEAD^`
`git push -f`

---

#### Զ�ֿ̲�
`git remote -v`
> �鿴�ֿ�

`git remote add [name] [url]`
> ���Զ�ֿ̲�

**`git push [name] [local branch]:[remote branch]`** 
> ���ʹ���

**`git fetch [remote name] [remote branhc]`**
> ��ȡ����



### ��֧����
- ����
- Ӧ�ó���
![Alt text](./img/111.png)



---
![Alt text](./img/cedr6fvm5f.png)

---
![Alt text](./img/����.png)



![Alt text](./img/222.png)

`git branch  [branch name]`
> �½���֧


![Alt text](./img/333.png)

`git checkout [branch name]`
> �л���֧

`git checkout -b [branch name]`
> ��ͬ����

`git branch`
 - -v
 - -a
 
![Alt text](./img/444.png)

---

![Alt text](./img/555.png)

![Alt text](./img/666.png)

![Alt text](./img/99999.png)


##### ��֧�ϲ�

**`git merge`**

`git rebase`
 > ���
 ![Alt text](./img/9999999999.png)



##### �����ͻ
- �Զ����
- �ֹ����


### ѧϰ��վ

[progit](https://progit.bootcss.com/)

[��ѩ��](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

[��һ��](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)

[����](https://mp.weixin.qq.com/s/mBckvjSiKorTuSmHcjp8oQ)


### һЩ����

- [���з�����](http://blog.csdn.net/starry_night9280/article/details/53207928)
- [δmerge](https://stackoverflow.com/questions/18328800/github-updates-were-rejected-because-the-remote-contains-work-that-you-do-not-h)
- [��֤����](https://stackoverflow.com/questions/17846529/could-not-open-a-connection-to-your-authentication-agent/10077302)
- [���git�˺�](http://blg.csdn.net/mq2856992713/article/details/62090841)
- [���git�˺�2](http://www.cnblogs.com/BeginMan/p/3548139.html)
- [Git���ú����ļ�/�ļ���](https://my.oschina.net/milletes/blog/798963)
- [others](http://blog.51cto.com/halolk/1304701)
- [�������ļ�](https://rtyley.github.io/bfg-repo-cleaner/)




# Mac�£�ʹ��sshpass��iterm2֧�ֶ�ssh��¼��Ϣ����
windows���и�Xshell�ǳ��ķ����ʹ����Ϊ���ܱ��������е�ssh��¼�ʺ���Ϣ��MAC�²�û��xshell����ЩҲ�ṩ�����Ĺ��ܣ���Ч�������á�iterm2�Ǻܺõ��նˣ���ȴ���ܺܺõ�֧�ֶ�profiles����Ҫ����Ļ����϶�ʱ���ͱȽ��鷳�ˡ���������profiles���ã�ֻ�ǲ��ܱ���ssh��¼�ʺż����룬�����ṩ�˼���profilesʱִ���ⲿ����Ĺ��ܣ���ˣ�����Ϳ���ʹ��sshpass������ִ�С�
## ��װiterm2
ֱ�ӵ��������ذ�װ: [http://iterm2.com/](http://iterm2.com/)��mac��װ������Ǽ������ɵ�����
## ��װsshpass
���أ�[http://sourceforge.net/projects/sshpass/files/](http://sourceforge.net/projects/sshpass/files/)
��ѹ�󣬽���sshpassĿ¼��ִ�а�װ
```java
./configure
make
make install
```
�����ϲ����ʲô���⣬��װ�ú�ִ���������Ƿ��Ѿ�OK
```shell
sshpass -h
```
## ׼������
��sshpassʹ��ssh���룬��Ҫ�Ƚ����뱣����һ���ļ����ͨ��sshpass���ļ�����ȡ���룬iterm2�Ϳ���ͨ����������������¼�����������ļ��ܼ򵥣�ȡһ�������֣�������д��ȥ�Ϳ����ˣ�û�б���κζ������磬���û�Ŀ¼��sshpassĿ¼��һ����Ϊpass���ļ�������д���������룺123456���ļ���ַΪ��/Users/�û���/sshpass/pass
## ����iterm2
��iterm��profilesѡ��
![image](https://github.com/onlyfu/Blog/blob/master/static/images/01.png)
���һ���µ�profile������ûʲô�����õģ���Ҫ����General��command��ѡ��ʹ��command���������sshpass��ִ������磺
```java
/usr/local/bin/sshpass -f /Users/fuwy/sshpass/pass ssh -p22 root@112.124.25.173
```
/usr/local/bin/sshpass��sshpassִ���ļ���·���������Ĭ�������װ�����϶�����������λ����

-f �Ǹ���sshpass�����ļ�

/Users/fuwy/sshpass/pass����Ҫ���ص��ļ�����ǰ�潨�������ļ�

ssh -p22 root@112.124.25.173��˵��ssh���ӣ��˿�22��root�ʺź�IP��ַ

�����ѡ���profile���Ϳ���ʵ��ssh��¼��ֻ������Ǳ�����һ�ε�¼���ǲ���ɹ��ģ���Ϊssh��¼��Ҫ��yesȷ�ϣ���д�ļ���hosts����Ե�һ�λ�ֱ��ʧ�ܣ�����һ�λ��������ն�����ssh root@ip����¼һ�Σ��Ϳ����ˡ�
�������½����profile���Ϳ���ʵ�ֹ����¼�ˡ�

iterm2��xshell�����������кܶ಻��ʹ�ĵط������磬�޷�ֱ�ӿ�������IP����ʱ���븴��һ�²����㡣tab�ϵ����Ʋ����Զ��壬�࿪����֮�󣬲�̫�����ֵȵȡ��������ܱ�û�кã����ԣ����ǲ���ġ�

1����ʼ��git���û��������䣺
	git config --global user.name "Your Name"
	git config --global user.email "email@example.com"

2������SSH��Կ��
	��.sshĿ¼�£�����Git Bash:  ssh-keygen -t rsa -C "youremail@example.com"�����������ļ�
	����id_rsa.pub�е�key��GitHub��

3����ʼ�����زֿ�ʹ�ã�git init

4���������ļ�����ӵ��ݴ�����git add -A

5����Ӿ����ļ����ݴ�����git add �ļ���.��׺�� �ļ���.��׺��

6�����ݴ������ļ��ύ���ֿ⣺ git commit -m "����"

7���ѱ��زֿ���Զ�ֿ̲��������git remote add origin �ֿ��ַ,��:git@github.com:arsty/acs.git

8���ѱ��زֿ����͵�Զ�ֿ̲⣺git push

9������һ��������Ҫʹ�ã�git push -u origin master

P.s: origin��Զ�ֿ̲�����ƣ�GitĬ�ϵĽз������Ը�Ϊ���
1�����������û����������ַ���������ã�������һ�����ؿ⣬��������޹أ�
git config --global user.name "njelement"
git config --global user.email "adsl.com@163.com" 
git init
���ˣ�һ������git�ֿ⽨����ɡ�����ʹ��
git status�鿴�ֿ�״̬������ʹ��
git add . ����ļ�/�ļ��е��ݴ���������ʹ��
git commit . -m "�汾ע��" �ύ�ݴ����ļ�/�ļ��е��ֿ��С�

2��������⽨��������ǰ�����Ѿ�����Ӧ��վע�ᣬ�������ֿ⣩������ʹ��ssh-keygen������Կ��
ssh-keygen -t rsa -C "adsl.com@163.com"
Ȼ�����ɵĹ�Կ����������ˣ����岽��Ϊͼ�λ��������裬����׸����һ̨��������Ҫһ����Կ���ɣ���ͬ��Ŀ¼�����ظ����ɣ�

3�������زֿ���Զ�ֿ̲⽨����ϵ
git remote add origin git@github.com:njelement/GitCode.git
Զ�ֿ̲�������������Ϊorigin��

4�����͵�Զ�ֿ̲⣬ʹ��-u�ǽ�����ϵ���˺��ٴ����Ϳɲ�����ʹ��Զ�̵�ַ/�ֿ�����
git push -u origin master

5�����֦���ܣ�ʹ��git branceָ����Բ�ͬ�Ŀ��ز���
git branch �鿴��ǰ��֧״̬���б����з�֧��

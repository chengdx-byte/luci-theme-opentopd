luci-theme-opentopd
ԭ���� https://github.com/sirpdboy/luci-theme-opentopd



opentopd ��һ�����luci-theme-material�����ģ�ʹ��HTML5��CSS3��д��Luci���⡣

���������Ϊsirpdboy������OpenWrt��ר��Ϊ��ͥʹ�ó�����ƵĹ̼���ר����Ƶģ�Ҳ��������OpenWrt�����汾��Ŀǰ����Luci18��Luci�����汾�ƻ��ڴ˰汾�ȶ��󿪷���

��opentopd ��������� LEDE/OpenWRT Դ��ķ�����
�༭Դ���ļ��и�Ŀ¼feeds.conf.default��������������:

# luci-theme-ifit
src-git opentopd  https://github.com/sirpdboy/luci-theme-opentopd
����feeds������װ���⣺

$ scripts/feeds update opentopd
$ scripts/feeds install luci-theme-opentopd
�����ò˵���

$ make menuconfig
�ҵ� LuCI -> Themes, ѡ�� luci-theme-opentopd, ������˳�������̼���

����Ĭ�ϻ��Զ����ã����û�����������ֶ�������

�ֶ���������
ϵͳ -> ϵͳ -> ���Ժͽ���
���⴦ѡ�� 'opentopd'�����½ǡ�����&Ӧ�á�
��F5ˢ�������
��Ļ��ͼ
# CCU-WAR

**��װJDK**  
1.1 ����JDK  

> ������https://www.oracle.com/java/technologies/javase-jdk8-downloads.html  

1.2 ��JDK�ŵ�ָ��Ŀ¼ �磺/usr/local/java  
1.3 ��ѹJDK ���tar -zxvf jdk����   
1.4 д�뻷������ �磺vi /etc/profile  
1.5 д���������£�  
```
export JAVA_HOME=Ŀ¼
export CLASSPATH=.:${JAVA_HOME}/jre/lib/rt.jar:${JAVA_HOME}/lib/dt.jar:${JAVA_HOME}/lib/tools.jar
export PATH=$PATH:${JAVA_HOME}/bin
```
1.6 ���»������� ���source /etc/profile  
1.7 ���� ���java -v  

**��װAndroid SDK**  
2.1 ����Android ADT  

> ��ַ��http://tools.android-studio.org/index.php/adt-bundle-plugin    

2.2 ��ѹadt ���tar -zxvf sdk����  
2.3 д�뻷������ �磺vi /etc/profile  
2.4 д���������£�  
```
export ANDROID_HOME=Ŀ¼
export PATH=${PATH}:${ANDROID_HOME}/tools:${ANDROID_HOME}/platform-tools
```
2.5 ���»������� ���source /etc/profile  

**��װgenymotion**  

3.1 ���� genymotion-2.8.0-linux_x64.bin  
> ���ӣ�https://pan.baidu.com/s/1esUU9dq7XNLBn1FDCc9xjg  
> ��ȡ�룺k4rn  

3.2 ��װ`genymotion`  
���`sudo ./genymotion-2.4.0_x64.bin`
> һ�㰲װĿ¼Ϊ��/opt/genymobile/genymotions/  

3.3 �滻�ļ�  
ʹ�� genymotion_crack �µ��ļ��滻�� genymotion  
`sudo cp -f <�滻�ļ�(from)> <���滻�ļ�(to)>`

3.4 �����쳣
> **�쳣��** undefined symbol: xcb_wait_for_reply64  
> **�����** �� genymotion Ŀ¼�µ� libxcb.so.1 ɾ�������ƶ��������ĵط����ɽ����  
> **�쳣��** undefined symbol: drmGetDevice2  
> **�����** �� genymotion Ŀ¼�µ� libdrm.so.2 ɾ�������ƶ��������ĵط����ɽ����  
> **�쳣��** INSTALL_FAILED_CPU_ABI_INCOMPATIBLE  
> **�����** ��ģ�����а�װGenymotion-ARM-Translation  
> **��ʹ�������汾 �����汾��û�г��ִ�����**  

**��װappium**  
4.1 ���� `appium`  
> ������https://github.com/appium/appium-desktop/releases/tag/v1.15.1  
4.2 ���� `Appium-linux-1.15.1.AppImage`

#�����쿡�� Theano ��ġ �ϱ� 
 
 
##1. python ��ġ �ϱ�    
Theano�� ���ؼ��� pyCuda�� ���� ���̺귯���� ������ �ؾ� �ϱ� ������    �Ϲ����� Python�� �ƴ϶�    WinPython�̶�� ��Ű���� ��ġ.    �� ��Ű���� ������ ������ �ϱ� ���� ������ �غ� �Ǿ� �ִٴ°�.(������ �׷��� ���ϴ� �� ^^)   �ٿ�ε� ��ġ : http://winpython.sourceforge.net/
 
 
##2. CUDA ��ġ  
NVIDIA���� CUDA ��Ŷ�� �ٿ�ε� �޾Ƽ� ��ġ.   ���� �ֱ� ���� : 7.0 ����   ��ġ�� ����̺갡 ����� ���� �ȵǾ� �־ �� ��¼�� ��¼�� �޼��� ����  ������ �����ϰ� ��ġ.   PATH���� CUDA ��� �߰�. 
 
 
 
##3. Visual Studio ��ġ   
python ��Ű�� ��ġ�� ���ؼ��� visual Studio�� MinGW ���� �����Ϸ��� �ʿ��ϳ�...  Visual Studion 2012�� ��ġ.   MS Ȩ������ Visual Studio 2012 Express ������ ��ġ. 
 
 
##4. Visual Studio �Ϻ� ����.    
C:\Program Files (x86)\Microsoft Visual Studio 11.0\VC\bin ���丮 �ؿ�    x86_amd64 ���丮�� ���� amd64�� �̸� �ٲ�.   vcvarsx86_amd64.bat ���ϸ��� vcvarsx86_amd64.bat�� ����. 
 
 
##5. MinGW ��ġ   
�������� ���� ��ġ    �Ʒ� url���� �ٿ�ε�    http://sourceforge.net/projects/mingw-w64/   ÷���� MSYS-20111123.zip������ �ٿ�ε� �ް� ��ġ�� ��ο� ���� ����    msys ���丮 �ȿ�    msys.bat �ֻ�ܿ�    call ��c:\Program Files (x86)\Microsoft Visual Studio 11.0\VC\bin\x86_amd64\vcvarsx86_amd64.bat��   ���� �߰�.       @echo Off ���� �ٷ� �Ʒ��� ���� ���� �߰�.    set HOME=%USERPROFILE%
 
 
##6. Theano ��ġ    
pip install Theano�� ��ġ 
 
 
##7. Theano ȯ�� ���� ����    
c:\User\����ڸ�\.theanorc.txt ���� ����  [gcc] �ǿ�   cxxflags = -shared -I[MinGW ���丮]\include -L[���̽� ���丮]\libs -lpython34 -DMS_WIN64  �ܿ� ���� ���� 
 
 
##8. Theano ����    
ipython ����      import theano     theano.test() 
 
   python -c "import theano;theano.test()"
 
   ���� ���� �ڵ尡 ���� ���� �Ǹ� ������. 
 
 
���� ����Ʈ http://rosinality.ncity.net/doku.php?id=python:installing_theano
 
 
�� ����Ʈ�� 5�� �׸��� winPython�� ��ġ�ϸ� ���� �� �ʿ� ����. 
### ��� ������� � �������� SSH-����? ��� ����������� �����������? 
---
1. � ���� ��������� ������ ssh-keygen -t ed25519 -C "...email"
 > git clone https://github.com/...
 
2. ssh-���� ��������� � ����� id_<file_name>, ��� ���������� ���������� � ��������������� ����� �� github.

3. ����� �������� ���� � ssh agent, ����� �������� � ���������
> eval ssh-agent -s

� �������� ���� ��������� ���� � ssh-agent:
> ssh-add ~/.ssh/id_<file_name>

4. ����� ����������� �����������, ����� �������� � ���������
> git clone https://github.com/repository...
���������� �������� ����� scadasrv, scadacomm � /etc/init.d
����� ��� ����������� ������� ���������� ��������� ��������� �������: 

sudo update-rc.d scadasrv defaults 97 03    
sudo update-rc.d scadacomm defaults 98 02

����� 97, 98 �������� �� ������� ������� ��� ���������, 03 � 02 �� ������� ��������� ��� ���������� �������.

sudo service scadacomm start - ������ ������ � ������ scadacomm
sudo service scadacomm stop - ���������
sudo service scadacomm restart - ����������

sudo update-rc.d -f test_script  remove - ������ ����������� ������ � ������ test_script
# domestos-closets
Data from Domestos contest of school toilets to repair

���� ����������� �������� ��� � ������ �������� ��������� Domestos 2021 https://www.promonado.ru/domestos-schools/
�� 31 ��� 2021 ���� � �������� ������ �� ������ ��� �������� ����� API �� ����� ���������.



������ �������� ���������� APIBackuper (https://github.com/ruarxive/apibackuper) ������ 1.0.5 ��������� ���������� 
��� ��������� ������ ������������ ����� API. ��� ������ ������� ����� ��������� � � ����� � ������ .cfg.
��������� �������� ������� � apibackuper.cfg �����, ������� ����� ������ ��������� � ��������������� ���������� ������
� ���������� �� � ���� storage/storage.zip. ������� ��������� ������������ ����� (�����������) � �������������� ������


��� �������� ������

	apibackuper run full

��� �������� ���� �����������

	apibackuper getfiles

��� ��������� ������ ������ � ������� ����������� JSON ����� (JSON lines)

	apibackuper export jsonl data.jsonl

��� �������������� JSON ����� � CSV ������������� ����� ������� undatum  (https://github.com/datacoon/undatum)
    
    undatum convert data.jsonl data.csv


��� ������ �������, ������������� � ������� � �����������, ����� ��������������� ����������. ����� ������� ������ ��������� ���������� 
- ��� ��������� ������� apibackuper getfiles. ������������� ����� ������� ��� ����� ������ ������������ ������� ��� ����� ������ 
�� ����� � �������

# �������� 
MIT License
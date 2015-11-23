# HelpDesk

### ��������
GPL v3 http://www.gnu.org/licenses/gpl-3.0.ru.html

### ���������
```sh
mkdir helpdesk
cd ./helpdesk
git clone https://github.com/SibirixScrum/HelpDesk.git ./
npm i
```

### ���������
```sh
cd ./config
cp ./config.example.js ./config.js
mcedit ./config.js
```

### ������� �����
- connectString: 'mongodb://localhost/helpdesk' � ���� � mongo. ����� ������� ��� ������ �������, ���� ��� �� ����������.
- exports.projects � ��������� ��������.
- responsible: 'tester@example.com' ����� �������������� �������. ������� ��������� �������������. ������ ������������ �� �����.
- exports.socketIo: 'SECRETKEY' � ��������� ���� ��� ���������� �����.
- exports.session.secret: 'SECRETKEY' � ��������� ���� ��� ���������� ������.

### ������
```sh
node app.js
```

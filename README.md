# blockchain
blockchain - һ���򵥵�����������رҵ�ʵ�֣���������������رҵ�һЩ�������ԣ���ȥ���Ļ���P2PͨѶ�����رҽ��ף� �ڿ󣬹�ʶ�㷨�����ر�Ǯ����

### Quick start
```
git clone https://github.com/aaronrao/blockchain.git
cd blockchain
mvn clean install
java -jar blockchain.jar 8081 7001
java -jar blockchain.jar 8082 7002 ws://localhost:7001

```


### HTTP API

- ��ѯ������

  ```
  curl http://localhost:8081/chain

  ```
- ����Ǯ��

  ```
  curl http://localhost:8081/wallet/create

  ```
- �ڿ�

  ```
  curl http://localhost:8081/mine

  ```

- ת�˽���

  ```
  curl http://localhost:8081/transactions/new

  ```
- ��ѯǮ���

  ```
  curl http://localhost:8081/wallet/balance/get?address=518522f475ab591cf55d5f79bef629a0

  ```
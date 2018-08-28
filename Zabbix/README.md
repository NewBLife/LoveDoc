Zabbix 利用説明

----

◆穴あけが必要なポート◆
ZABBIXマネージャ　→　ZABBIXエージェント（監視対象側）

TCP 10050 Manager→Agent通信用
ICMP ping監視用
UDP 161 SNMP　※Snmpポーリング監視をする場合必要。
※ポート監視やURL監視をする場合は、上記以外のポートについて別途FW申請が必要です。

ZABBIXエージェント（監視対象側）→　ZABBIXマネージャ
TCP 10051 Agent→Manager通信用    
UDP 162 SNMPTRAP　
※Snmpトラップ監視またはSnmpポーリング監視をする場合必要。

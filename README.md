# Monitoring for GSM GATEWAY CZ-NXS 9750-3G

based on snmp - see OID from documentation

**Triggers**

![triggers](https://user-images.githubusercontent.com/52492965/62545415-f26bcb80-b861-11e9-980e-3077c5c2a283.PNG)


**GSM_Signal** \
\
Returns GSM/3G signal strength in percent. Value range: 0-100. If modem is disconnected from GSM/3G network GSM_Signal returns 0.

.1.3.6.1.4.1.8072.1.3.2.3.1.2.11.71.83.77.95.83.105.103.110.97.108.49

**FolderOutbox_Total** \
\
Returns number of SMS messages in Outbox folder (outgoing queue length)

.1.3.6.1.4.1.8072.1.3.2.3.1.2.18.70.111.108.100.101.114.79.117.116.98.111.120.95.84.111.116.97.108 

**FolderInbox_Total** \
\
Returns number of SMS messages in Inbox folder 

.1.3.6.1.4.1.8072.1.3.2.3.1.2.17.70.111.108.100.101.114.73.110.98.111.120.95.84.111.116.97.108

**FolderSent_Last24H** \
\
Returns number of SMS messages sent from the device within last 24 hours

.1.3.6.1.4.1.8072.1.3.2.3.1.2.18.70.111.108.100.101.114.83.101.110.116.95.76.97.115.116.50.52.72 

**FolderSent_Last1M** \
\
Returns number of SMS messages sent from the device within last month 

.1.3.6.1.4.1.8072.1.3.2.3.1.2.17.70.111.108.100.101.114.83.101.110.116.95.76.97.115.116.49.77

**FolderSent_Last24HSendErr** \
\
Returns number of SMS messages sent with error within last 24h. Error occurs when 3G modem cannot send SMS message or message is rejected by GSM /3G carrier (mostly happens when a credit on pre-paid SIM card is over)

.1.3.6.1.4.1.8072.1.3.2.3.1.2.25.70.111.108.100.101.114.83.101.110.116.95.76.97.115.116.50.52.72.83.101.110.100.69.114.114



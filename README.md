# Cryptographic Hashing & Debugger Analysis Lab Log

This collection acts as a standalone technical journal recording practical investigation into Windows assembly debugging instruments and the syntax used for offline password cracking.

Progress: Successfully initialized an offline cracking lab environment.
Actions: Verified hardware configuration utilizing an AMD GPU via OpenCL at 29,000 kH/s. Cracked a custom MD5 fingerprint against the `rockyou.txt` database.
Takeaways: Evaluated combinatoric keyspace limits. Identified the requirement rules for identifying hash formats ('-m') and tracking boundary characters prior to executing brute-force operations.

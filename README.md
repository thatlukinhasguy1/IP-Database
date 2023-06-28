# IP-Database
An Anti Proxy, TOR, and VPN SQLite database.

# How to use?
The database is stored in an SQLite database file. You can query like this: `SELECT * FROM IPv4 WHERE Start <= ? AND End >= ? ORDER BY Start DESC LIMIT 1;` where ? is the IP address as an integer.

# Address Types:
1. Residential
2. Business
3. Hosting
4. VPN
5. DDoS Mitigation
6. Tor Relay
7. Cloud Gaming
8. Mobile Carrier
9. Banking

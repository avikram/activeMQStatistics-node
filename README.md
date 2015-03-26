Usage: node stomp-activemq-statistics-collector.js <activeMQServer> <activeMQStompPort> <qName> <qUserName> <qPass> <logFile>

Prerequisites: 
1. node
2. npm 
3. npm modules bunyan, stomp-client & xml2js

The module collects the statistics periodically (every 5 seconds) and dumps it into a log file 


# downlink-locator-via-sms0
Locate if person in area based on a simplified version of police triangulation using telecom strategies.

<h3>• Download Silent SMS Detector: https://github.com/MatejKovacic/silent-sms-ping</h2>
<h3>• Install LTESniffer, used with an Software Defined Radio (SDR): https://github.com/SysSec-KAIST/LTESniffer</h2>
<h3>• Text silent sms (sms-0) to target but in a fashion that is noticeable, like 5 fast messages in a row, or every 3 seconds. These will be silent, so does not notify target of connection, or anything, but will register in cell tower downlink. Hence, upon silent pinging (sms-0), if target is nearby, you will see the irregular ping pattern you did with Silent SMS Detector on LTESniffer. You must know the tower Cell ID so you can know if target is near that tower. You can get these CID's (Cell ID's) using any modern app that identifies surrounding towers. I use CellularFinder.</h2>
<p>Basically, on a general level, this is how the cops do it, and government agencies. Pretty cool.</p>

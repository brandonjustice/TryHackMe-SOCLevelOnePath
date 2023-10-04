Pyramid of Pain
	
	Hashing(Trivial)
	Most Common Hashing algorithms:
		MD5 - not secure
		SHA-1
		SHA-2

	Tools for hash lookups
		VirusTotal
		Metadefender Cloud - OPSWAT

	Hashlookups are good to use if the hash is known but it is easy for a threat actor to change the file thus changing the hash

	IP Address (Easy)
	Knowledge of an IP address as the defense is useful because you can set the firewall to block, drop or deny traffic from that IP address. However, the attacker can just use a new IP address that is not blocked

	Attackers also use Fast Flux to get around IP blocking. Fast Flux is a network that has multiple IP Addresses associated with a domain name that constantly changes. This makes it difficult to be discovered

	Domain Names (Simple)
	Attackers use puny code to change the domain name from words that connate be written in ASCII, into a Unicode ASCII encoding

	Attackers usually hide the malicisou domains under URL Shorteners. A URL Shortener is a tool that creates a short and unique URL that will redirect to the specific website during the initial step of setting up the URL Shortener Link.
	
	You can see the actual website the shortened link is redirecting you to by appending “+” to it.

	Host Artifacts (Annoying)
	Host artifacts are the traces or observables that attackers leave on the system, such as registry values, suspicious process execution, attack patterns or IOCs (Indicators of Compromise), files dropped by malicious applications, or anything exclusive to the current threat.

	Network Artifacts
	A network artifact can be a user-agent string, C2 information, or URI patterns followed by the HTTP POST requests.An attacker might use a User-Agent string that hasn’t been observed in your environment before or seems out of the ordinary. The User-Agent is defined by RFC2616 as the request-header field that contains the information about the user agent originating the request.

	Network Artifacts can be detected in Wireshark PCAPs

	Tools (Challenging)
	MalwareBazaar and Malshare are good resources to provide you with access to the samples, malicious feeds and YARA results (helpful for threat hunting and incident response)

	SOC Prime Threat Detection Marketplace - used for detection rules - shares of detection rules for different kinds of threats

		Fuzzy hashing - helps to perform similarity analysis (matching two files with minor differences based on the fuzzy hash values.

	TTPs(Tough) - Tactics, Techniques & Procedures
		

# 3	SIP Clients and Servers

The client-server nature of SIP has been introduced in the example message flows of Chapter 2. In this chapter, the types of clients and servers in a SIP network will be introduced and defined.

##	3.1	SIP User Agents

## 3.2	Presence Agents

## 3.3	Back-to-Back User Agents

## 3.4	SIP Gateways

## 3.5	SIP Servers

###	3.5.1	Proxy Servers

### 3.5.2	Redirect Servers

### 3.5.3	Register Servers

## 3.6	Uniform Resource Indicators

## 3.7	Acknowledgment of Messages

## 3.8	Reliability

## 3.9	Multicast Support

## 3. 10	Conclusion

## 3.11	Questions

Q3.1 Fill in the missing messages in the call flow below with two UAs and one proxy (see Figure 3.8).

![image-20220313110151776](images/image-20220313110151776.png)

Q3.2 A User Agent sends an OPTIONS to another User Agent which does not respond. Assume T1 = 500 ms and T2 = 4 seconds. Show the timing of the retransmissions relative to t=0 when the first OPTIONS is sent. How many messages are sent all together?

Q3.3 Fill in the CSeq header fields (number AND method) for each of the messages in Figure 3.9.

![image-20220313110243761](images/image-20220313110243761.png)

Q3.4 Add the missing SIP messages and responses for the call flow in Figure 3.10. Assume the proxy does not Record-Route (Hint: There are six missing messages that will result in just a single media session between Alice and Bob.)

![image-20220313110312006](images/image-20220313110312006.png)

Q3.5 Fill in the time intervals for the retransmission example in Figure 3.11.

![image-20220313110321576](images/image-20220313110321576.png)

Q3.6 What are two ways that a proxy knows to fork a request?

Q3.7 When does a proxy generate an ACK to a response, and when does it just forward the response without generating an ACK?

Q3.8 What is the difference between a redirect server and a proxy server?

Q3.9 What is the purpose of a SIP registrar server?

Q3.10 A UA sends a REGISTER. After 2.3 seconds, a 100 Trying response is received. After another 0.7 second, a 200 OK response is received. In total, how many times was the REGISTER request sent?

## References

[^1]:	Rosenberg, J., et al., “SIP: Session Initiation Protocol,” RFC 3261, June 2002.
[^2]:	Rosenberg, J., “A Presence Event Package for the Session Initiation Protocol (SIP),” RFC 3856, August 2004.
[^3]:	Roach, A., “SIP—Specific Event Notification,” RFC 6665, July 2012.
[^4]:	Niemi, A., “Session Initiation Protocol (SIP) Extension for Event State Publication,” RFC 3903, October 2004.
[^5]:	Hautakorpi, J., et al., “Requirements from SIP (Session Initiation Protocol) Session Border Control Deployments,” RFC 5853, April 2010.
[^6]:	Schulzrinne, H., and C. Agboh, “Session Initiation Protocol (SIP)-H.323 Interworking Requirements,” RFC 4123, July 2005.
[^7]:	Rosenberg, J., H. Salama, and M. Squire, “Telephony Routing over IP (TRIP),” RFC 3219, January 2002.
[^8]:	Roach, A., “Registration for Multiple Phone Numbers in the Session Initiation Protocol (SIP),” RFC 6140, March 2011.
[^9]:	Donovan, S., and J. Rosenberg, “Session Timers in the Session Initiation Protocol (SIP),” RFC 4028, April 2005.
[^10]: 	Belshe, M., et al., “Hypertext Transfer Protocol Version 2 (HTTP/2),” RFC 7540, May 2015.
[^11]: 	Burger, E., J. Van Dyke, and A. Spitzer, “Basic Network Media Services with SIP,” RFC 4240, December 2005.
[^12]: 	Bormann, C., et al., “Applying Signaling Compression (SigComp) to the Session Initiation Protocol (SIP),” RFC 5049, December 2007.
[^13]: 	Jennings, C., F. Audet, and J. Elwell, “Session Initiation Protocol (SIP) URIs for Applications such as Voicemail and Interactive Voice Response (IVR),” RFC 4458, April 2006.
[^14]: 	Rosenberg, J., “Obtaining and Using Globally Routable User Agent URIs (GRUUs) in the Session Initiation Protocol (SIP),” RFC 5627, October 2009.
[^15]: 	Jennings, C., Mahy, R., and F. Audet, “Managing Client-Initiated Connections in the Session Initiation Protocol (SIP),” RFC 5626, October 2009.


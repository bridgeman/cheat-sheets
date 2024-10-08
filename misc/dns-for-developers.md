- **A record**  
    A type of DNS record that maps a domain name to an IPv4 address.
- **AAAA record**  
    A type of DNS record that maps a domain name to an IPv6 address.
- **Accredited registrar**  
    A registrar that passed ICANN's accreditation process. They have a Registrar Accreditation Agreement with ICANN.
- **Add grace period**  
    A 5-day period in which domain name registrations can be undone, and the cost reversed.
- **Anycast**  
    A networking methodology that allows multiple servers to listen to the same IP address.
- **API**  
    Application programming interface. A way for two programs to communicate.
- **ASCII**  
    American Standard Code for Information Interchange. A character encoding with western characters.
- **Auth code**  
    Synonymous to transfer code
- **Auth info**  
    Synonymous to transfer code
- **Authoritative DNS server**  
    A DNS server that has authority (ownership) over a DNS zone. Only this server can change DNS records for domain names in that zone.
- **Authority**  
    A server that manages a domain name is said to have authority over that zone.
- **Auto-renew**  
    A setting at registrars that automatically renews a domain name. This prevents accidentally dropping domain names but can cause accidental charges.
- **Auto-renew grace period**  
    A 0 to 45 day period after domain expiry in which a domain owner can still renew a domain name for the usual cost. The registrar may delete the DNS records during this period.
- **AXFR**  
    A DNS query type that requests all the DNS records for a specific DNS zone.
- **Brand TLD**  
    A TLD that a brand owns. These usually don't allow registrations outside of their organization. Examples are `.accenture` and `.google`.
- **Caching**  
    Remembering data for a specified period to use that data in the future without requesting it from the source again.
- **ccTLD**  
    Country code top-level domain. A 2-letter TLD that is operated by a country. Examples are `.nl` and `.io`.
- **Character encoding**  
    The process of assigning numbers to letters and other symbols. This allows them to be stored and sent by computers.
- **Child zone**  
    A zone directly below another zone in the DNS tree.
- **Client**  
    A software component that is capable of making DNS requests.
- **DNS**  
    The Domain Name System. This stores all domain names and associated data.
- **DNS protocol**  
    The network protocol of the DNS.
- **DNS query**  
    A request message in the DNS protocol. E.g., "May I have the IPv4 addresses of en.wikipedia.org?"
- **DNS request**  
    Synonymous to DNS query
- **DNS root**  
    The upmost domain name in the DNS tree. All domain names start here and flow down through other labels in the tree.
- **DNS server**  
    A server that responds to DNS queries.
- **DNS Tree**  
    The logical representation of the domain name space as a tree-like data structure. The root of the tree is the DNS root, nodes are labels, and the path from the root to any label is a domain name.
- **Database replication**  
    A mechanism to keep data on multiple databases in sync.
- **Debugging**  
    The manual process of investigating an issue.
- **Delegation**  
    Synonymous to "Zone delegation".
- **Design pattern**  
    A commonly used software design that can be applied to achieve a certain design goal.
- **Dig**  
    A command-line tool that can query DNS records from a server.
- **Distributed system**  
    A system whose components are located on different servers.
- **Distribution**  
    A design pattern that composes multiple servers into a single system.
- **Domain expiry**  
    The moment that the period that a domain name is registered for ends.
- **Domain hijacking**  
    Domain hijacking is when someone tries to transfer your domain name without your consent.
- **Domain lock**  
    A setting offered by registrars that disallows domain transfer.
- **Domain name**  
    A human-friendly text string that represents a node in the DNS tree. E.g. "en.wikipedia.org", "wikipedia.org" and "org".
- **Domain name space**  
    The set of all possible domain names.
- **Domain transfer**  
    The transfer of ownership from one party to another.
- **Drop-catching**  
    Attempting to register a domain name as soon as it expires.
- **Expire time**  
    If the zone cannot be transferred within this many seconds, the follower DNS server should consider the zone to be offline and drop its record for that zone.
- **Fault-tolerance**  
    The ability of a system to keep working when part of the system fails.
- **Federated database**  
    A database that consists of smaller databases that are merged to form a larger database.
- **Federation**  
    See "federated database"
- **Functional second-level domain**  
    A third-level domain where it's parent is a public suffix domain.
- **GDPR**  
    General Data Protection Regulation. An EU regulation on information privacy.
- **Generic restricted TLD**  
    A generic TLD that is only allowed to be used for a specific purpose.
- **Grace period**  
    A period in which an action can be reversed.
- **gTLD**  
    Generic top-level domain. A three or more letter TLD that is not tied to a country.
- **IANA**  
    The Internet Assigned Numbers Authority. This organization is a subsidiary of ICANN, and manages the DNS root zone.
- **ICANN**  
    The Internet Cooperation for Assigned Names and Numbers. This organization oversees the DNS.
- **IDN**  
    International domain name. A domain name that starts with `xn--` and can be translated to Unicode characters.
- **Infrastructure TLD**`   .arpa` is the only infrastructure TLD. It handles IP to domain name lookups, among other things.
- **IP address**  
    A numerical label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication.
- **IPv4 address**  
    A 32-bit IP address.
- **IPv6 address**  
    A 128-bit IP address.
- **ISO 3166**  
    A document that standardizes the use of country codes. Officially called "Codes for the representation of names of countries and their subdivisions."
- **IXFR**  
    A DNS query type that requests an incremental zone transfer.
- **Incremental zone transfer**  
    An improvement on zone transfer that allows changes to be transmitted rather than all data. See "zone transfer".
- **JSON**  
    JavaScript Object Notation. A file format standard for transmitting data in a human-readable form.
- **Key-value store**  
    A database that allows storing a data object referenced by a key.
- **Label**  
    A text string that is represented by a node in the DNS tree. E.g. "en", "wikipedia" and "org" are all labels in the domain name "en.wikipedia.org".
- **Latin characters**  
    The alphabet containing the letters A-Z.
- **Leader/follower architecture**  
    A design pattern in distributed systems that allow data to be kept in sync among servers. A single leader is the source of truth, and followers aim to replicate the data as quickly as possible in order to serve the same data.
- **Master**  
    Synonymous to "leader". See "Leader/follower architecture".
- **Multi-tenancy**  
    The ability of a system to accommodate multiple independent users, where these users cannot interfere with each other.
- **NS record**  
    A DNS record type that maps a domain name to authoritative DNS servers.
- **Name server**  
    A DNS server. See "Authoritative DNS server" and "NS record".
- **Network protocol**  
    A formally specified set of network messages that allow two systems to communicate. 
- **Notify query**  
    A DNS query that a leader can send to a follower to signal that zone data has been changed. See "incremental zone transfer".
- **Operating system**  
    A system software that manages computer hardware and software resources. E.g. Windows, MacOS, Android and Linux.
- **Parent zone**  
    The zone one zone delegation closer to the root than the current zone.
- **Pending delete**  
    The state a domain name can be in, in which it is about to be deleted.
- **Performance**  
    The speed (throughput and latency) of a system.
- **Primary DNS server**  
    The leader in a leader/follower deployment of a set of authoritative DNS servers.
- **Public suffix domain**  
    A domain name under which people can register their own domain name. Examples are `.org` and `.co.uk`.
- **Punycode**  
    A representation of Unicode characters with the limited set of ASCII characters.
- **Quad A record**  
    Synonymous to "AAAA records".
- **Rate limiting**  
    The process of rejecting requests when a requestor exceeds a certain rate of requests.
- **RDAP**  
    Registration Data Access Protocol. A network protocol to access domain name registration data. Replaces WHOIS.
- **RDDS**  
    Registration Data Directory Services. An online service that allows looking up domain name registration data. WHOIS and RDAP are such services, but it can also be on a website.
- **Recursion**  
    Recursion occurs when the definition of a concept or process depends on a simpler version of itself.
- **Redemption grace period**  
    A grace period after domain expiration in which the domain can still be redeemed. The redemption fee is usually significantly higher than the regular renewal fee.
- **Refresh time**  
    A field in a SOA record that specifies how often secondary servers should initiate zone transfer.
- **Registrant**  
    Someone who registers a domain name.
- **Registrar**  
    An organization that sells domain name registrations.
- **Registrar Accreditation Agreements**  
    A contract between ICANN and a registrar.
- **Registry**  
    An organization that operates a TLD.
- **Replication**  
    A design pattern where data is stored on multiple parts of a system in order to achieve fault tolerance and scalability.
- **Resolver**  
    A DNS client that sometimes also caches responses.
- **RESTful**  
    A web interface that conforms to the Representational State Transfer (REST) standard.
- **Retry time**  
    A field in a SOA record that specifies how long secondary servers should wait before retrying zone transfer when it fails.
- **RFC**  
    Request for comments. A document that standardizes (internet) technology.
- **Root server**  
    A DNS server that is authoritative for the root zone.
- **Root WHOIS server**  
    The WHOIS server that hosts information about TLDs. It is run by IANA at `whois.iana.org`.
- **Root zone**  
    The DNS zone that contains the DNS root.
- **SOA record**  
    All DNS zones begin with a Start Of Authority (SOA) record. The SOA record states that authority for a zone starts at a particular point in the global tree of DNS names. This record also contains configuration data for zone transfer.
- **Scalability**  
    The ability for a system to accommodate growing usage.
- **Secondary DNS server**  
    A follower in a leader/follower deployment of a set of authoritative DNS servers.
- **Second-level domain**  
    A domain name directly below a TLD. Examples are `co.uk` and `wikipedia.org`
- **Serial number**  
    A field in a SOA record that acts as a version number of zone data. This allows secondary DNS servers to know if they have the most up-to-date data.
- **Sponsored TLD**  
    A domain name that servers a specific community or industry.
- **Staleness**  
    Cached DNS records that have been updated are called stale records.
- **Start of authority record**  
    Synonymous to "SOA record"
- **Subdomain**  
    A domain name immediately below another domain name in the DNS tree.
- **TCP**  
    A network protocol that allows reliable transfer of data.
- **Test TLD**  
    A TLD with the specific purpose of testing DNS software and infrastructure. There are currently 11 test TLDs — all for testing IDNs.
- **Thick registry**  
    A registry that maintains WHOIS data.
- **Thin registry**  
    A registry that doesn't maintain WHOIS data. WHOIS data for domains under this registry are maintained by registrars.
- **Third-level domain**  
    A domain name directly below a second-level domain. Examples are `en.wikipedia.org` and `bbc.co.uk`.
- **TLD**  
    See Top-level domain
- **Top-level domain**  
    A domain name directly below the DNS root. Examples are `com`, `org` and `nl`.
- **Trace**  
    The process of looking up DNS records, starting at the DNS root, and working its way down until it lands on the requested domain name.
- **Transfer code**  
    A code that you can enter at a different registrar to move it there.
- **Transfer contact email**  
    The email address a registrar or registry has as an authorized person to transfer a domain name. This is entered upon registration and can be changed at any time. It is sometimes shown in WHOIS responses.
- **Tree structure**  
    A data-structure that stores the domain name space. It starts at a single root node and flows downwards through labels.
- **UDP**  
    A network protocol that prioritizes performance over reliability.
- **UDRP**  
    Uniform Domain-Name Dispute-Resolution. A way for trademark holders to take ownership of a domain name if it was registered in bad faith.
- **Unicode**  
    A character encoding for most of the world's writing systems.
- **Verisign**  
    A commercial organization that runs two of the DNS root servers.
- **Well-known**  
    Something is said to be well-known when it is common knowledge that does not need to be shared or looked up.
- **WHOIS**  
    A network protocol to look up domain name registration data.
- **Wireshark**  
    Software to capture and inspect local network traffic.
- **Zone**  
    A DNS zone is a domain name and all domain names below it, excluding any domain names that have been delegated.
- **Zone delegation**  
    The process of handing over the authority of a subdomain to a child zone.
- **Zone file**  
    A text file in a formally specified syntax that can be interpreted by DNS software. It contains DNS records.
- **Zone transfer**  
    A process to synchronize DNS data from a primary to a secondary authoritative DNS server.

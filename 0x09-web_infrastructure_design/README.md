<h1>0x09. Web infrastructure design.</h1>
  
  <h2>Notes</h2>
  
  <h4>Servers</h4>
    Servers are actual computers that run on Operating Systems are located in datacenters. Servers are computer w/o a keyboard, mouse or screen and it's ony accessible through a network. Servers can be virtual or physical.
   
  <h4>Web Server</h4>
    Web server and a server are the same things. 
    A web server is a software that delivers web pages (static content). A server is an actual computer (physical machine). A web server is a computer that runs websites.
    
  <h4>Application Server</h4>
    An application server delivers dynamic content. Databases are used to store the applications's data.
    
  <h4>Load Balancer</h4>
    Big companies have thousands of servers to handle all of the traffic. Load balancer distributes the web traffic/load to the servers.
    
  <h4>DNS</h4>
    The technology that translates human adapted text-based domain names to machine adapted, numerical based IP.
    Computers and other devices communicate and identify each other on the internet using IP address.
    Ppl can't remember IP addresses so they use words. DNS just matches these words and names.
    
   There are 4 DNS record types: A, CANME, MX, TXT.
    
   There are 3 level domains: 
   
    - Top-level domain TLD: .com, .org .net etc
    - Second-level domain (root domain): google.com
    - Third-level domain (sub domain): images.google.com
    
    
   <h4>Monitoring</h4>
   Monitoring how our software systems are doing is important!
   Web static monitoring can be broken down into categories:
   
    1) Application Monitoring: getting data about your running software and making sure it's behaving as expected.
    
    2) Server Monitoring: getting data about your virtual or physical server and making sure they are not overloaded like CPU, memory, disk or nextwork load)
    
  <h4>Single Point Of Failure (SPOF)</h4>
  There will be SPOF if there's nothing repeated, because the whole program is relying on one component.
  
  
    

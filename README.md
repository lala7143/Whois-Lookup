# Whois-Lookup
A WHOIS Lookup tool is a networking utility used to retrieve registration information for a domain name or IP address. It queries databases maintained by registrars and registries to identify the owner, administrative contacts, and technical details of a specific web entity.

What is it?
When a domain is registered, the owner must provide contact information. A WHOIS tool acts as a "public directory" for the internet. It reveals:
Registrar Information: Who sold the domain (e.g., GoDaddy).
Registration Dates: When the domain was created and when it expires.
Name Servers: Where the domain's DNS is hosted.
Ownership Details: Names, emails, or "Privacy Protection" statuses.

The Basic Workflow
Connection: The script opens a TCP socket to a WHOIS server (like whois.iana.org).
Query: It sends the domain name followed by a newline character.
Response: The server sends back the registration data as a text stream.
Formatting: Your tool cleans the raw text and presents it in an easy-to-read table or list.
Note: Modern privacy laws (like GDPR) often redact personal info from WHOIS results, making this project a great way to learn about the balance between internet transparency and data privacy.

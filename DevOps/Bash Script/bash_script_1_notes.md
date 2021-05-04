#  Bash Script 1

### Internet communication
- Each device connected to internet has a unique ID called an IP address which is used to identify destinations and origins of data. 
- Servers are connected directly to internet, other devices communicate  through routers to ISPs(Internet Service Providers) to the servers.
  

### Pull protocol

\* Http Requests

 \* Header

 \* HTTP Verb

 \* URI

 \* HTTP Version Number

 \* Optional request headers

 \* Name:Value, Name:Value

 \* Blank Line

 \* Body

 \* Additional Information

\* Example

  

\`\`\`

Get puppies.html HTTP/1.1

Host: www.puppyshelter.com

Accept: image/gif, image/jpeg, \*/\*

Accept-Language: en-us

Accept-Encoding: gzip, deflate

User-Agent: Mozilla/4.0

Content-Lenght: 35

  

puppyId=12345&name=Fido+Simpson

\`\`\`

  

### API - Application Programming Interface

The API is an interface that lets you connect other apps or programs comunicate with websites and access services.

  

### Notes on curl

  

The basic syntax of using cURL is simply:

  

curl <url> -displays webpage html

\* \-o FileName <url> - downloads file with custom name

\* \-O <url> - downloads file with default name

\* \-O -C - <url> -Resumes download

\* \-L <url> - Follows redirects

\* \-L --max-redirs <number> <url> - Follows <number> redirects, if <number> = -1 will follow endlessly

\* \-i <url> - Shows response headers

\* \-v <url> - "verbose mode" Shows connection details

curl <url> is the answer.rl
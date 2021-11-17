                                                 Activity File: Exploring Kibana
Answer the following questions:

In the last 7 days, how many unique visitors were located in India? 

- _There were 245 unique visitors located in India._

![Unique Visitors](https://user-images.githubusercontent.com/88859779/142128674-2385e89b-445b-4819-bcf6-4b704760fea0.png)
 
In the last 24 hours, of the visitors from China, how many were using Mac OSX?

- _There were 68 visitors from China in the last 24 hours._

![Unique Visitors from China](https://user-images.githubusercontent.com/88859779/142128721-8c82da3b-0849-4af8-90d8-c0ac6fa7865f.png)

In the last 2 days, what percentage of visitors received 404 errors? How about 503 errors? 

- _404: 10.294%_
- _503: 4.412%_

![Response Codes](https://user-images.githubusercontent.com/88859779/142128749-52541dbc-4aea-451b-bb01-2d1631e6d7bc.png)

In the last 7 days, what country produced the majority of the traffic on the website?

- _China produced the majority of the traffic on the website in the last 7 days: _259_

![Unique Visitors by Country](https://user-images.githubusercontent.com/88859779/142128789-63953972-6983-4f7b-86a3-63486d379118.png)

Of the traffic that's coming from that country, what time of day had the highest amount of activity?

- _Between the hours of 12 P.M. and 1 P.M., the country had the highest amount of activity._

![Heatmap](https://user-images.githubusercontent.com/88859779/142128830-1885d823-84de-494e-8b37-a4961b3a5c59.png)

List all the types of downloaded files that have been identified for the last 7 days, along with a short description of each file type (use Google if you aren't sure about a particular file type).

- _.gz – a compressed zip file using the standard GNU zip compression algorithm._

- _.css (Cascading Style Sheets) – file used to format HTML elements on a webpage._

- _.zip – used to group multiple files in one compressed file to simplify file sharing, especially when sharing large file contents via email._

- _.deb – is a Debian Unix archive that contains software package files for download on a terminal._

- _.rpm (Red Hat Package Manager) – used to store installation packages on Linux OS._

![Host, visits, and Bytes Tables](https://user-images.githubusercontent.com/88859779/142129015-50ac535f-d2b6-424d-913e-ac2eceae54a7.png)

Locate the time frame in the last 7 days with the most amount of bytes (activity).

![Unique Visitors vs  Average Bytes](https://user-images.githubusercontent.com/88859779/142129058-3d57ad3f-8b0c-4c1d-9e0d-16ca1a306868.png)

In your own words, is there anything that seems potentially strange about this activity?

- _There is 1 visitor is using a high volume of bytes compared to usage of other visitors count and avg. bytes_

![Unique Visitors vs  Average Bytes2](https://user-images.githubusercontent.com/88859779/142129090-54dd9a51-5715-4d19-b6c9-a93b50d96f48.png)

Filter the data by this event.

![Filtered data for question 4](https://user-images.githubusercontent.com/88859779/142129139-c63673ad-3eb9-4f19-81bd-f4b56e151442.png)

What is the timestamp for this event? 

- _Nov 08, 2021 @ 14:03 to Nov 12, 2021 @ 23:00. The time stamp is 15:00._

![Time stamp](https://user-images.githubusercontent.com/88859779/142129187-256f826a-b1ac-4958-8696-36ec61b99ea1.png)

What kind of file was downloaded? 

- _A .gz file was downloaded._

![Type of download](https://user-images.githubusercontent.com/88859779/142129385-7084ea92-a85e-46ad-a79a-874f62dc2eed.png)
   
From what country did this activity originate? 

- _China_
 
What HTTP response codes were encountered by this visitor? 

- _200 ok_

![Response code Cuba](https://user-images.githubusercontent.com/88859779/142129433-252a4f5b-818e-48d0-83a8-d46654464342.png) 

What is the source IP address of this activity? 

- *1.145.31.121*

![IP address](https://user-images.githubusercontent.com/88859779/142129525-2416f78c-02f1-46c1-8de2-0734a0ccf9ad.png)
 
What are the geo coordinates of this activity? 

- *{‘lat”: 28.28980556, “lon”: -81.43708333}*

![Geo Coordinates](https://user-images.githubusercontent.com/88859779/142129560-66013df4-8eb4-4dbe-859f-ebb8eafc8502.png)

What OS was the source machine running? 

- *Windows 8*

![OS source](https://user-images.githubusercontent.com/88859779/142129615-4f0bcce0-30ee-4946-8954-2791aebabc26.png)

What is the full URL that was accessed?

- '_https://artifacts.elastic.co/downloads/kibana/kibana-6.3.2-linux-x86_64.tar.gz_'

![URL accessed](https://user-images.githubusercontent.com/88859779/142129707-f5b4325a-8932-477c-9c80-37efdd2e5acf.png)

From what website did the visitor's traffic originate? 

- _Elastic-elastic-elastic.com_

![Elastic website](https://user-images.githubusercontent.com/88859779/142129968-a110494f-1cf0-4efd-8aa6-1c1060c6d79b.png)

What do you think the user was doing? 

- _It appears the individual is trying to download a linux file from the website._ 

Was the file they downloaded malicious? If not, what is the file used for?

- _The user is downloading a “Free and open-source software browser engine” named Gecko; which is created by Mozilla and used on the Firefox. The downloaded file is not malicious, but alterations to the library list can make it malicious._

Is there anything that seems suspicious about this activity?

- _The Gecko linux package was designed to support open internet standards, however, by tampering with the library lists, which is loaded automatically, the individual (with malicious intent) can create potential malicious downloads such as: spyware, keyloggers, etc. This malicious download can be bypassed without suspicion._

Is any of the traffic you inspected potentially outside of compliance guidelines? 

- _It doesn’t appear to be outside of compliance guidelines, however, further monitoring of the specified user can help in ascertaining information of any, if at all, suspicious activities._

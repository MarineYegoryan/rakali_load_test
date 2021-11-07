# Commerce_Tool_Load_Test

Load test is defined to measure commerce tool responsibility and stability for product and category filtering.

Details Find: https://confluence.greensky.net/display/rakali/CT+Load+Test
 
## Get started

Installation: https://confluence.greensky.net/pages/viewpage.action?pageId=82317593

CLI execution
1. jmeter -n -t CT_Load_Test.jmx -Jthread=5 -Jrampup=150 -l {report name}.jtl
	
	- thread: this is a max thread(users) number
	- rampup: this is a raump-up period for each thread. For specified example it means increas thread number each 3rd second https://jmeter.apache.org/usermanual/test_plan.html#:~:text=The%20ramp%2Dup%20period%20tells,the%20previous%20thread%20was%20begun.

GUI execution
1. Navigate to JMeter/bin folder
2. Choose jmeter.bat(Windows) jmeter.sh(Linux) file
3. Double click on it
4. From GUI click on Run button

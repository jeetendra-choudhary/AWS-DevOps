## Auto Scaling Groups (ASG)

### What 
 - Service which allows scale EC2 Instance capacity automatically, based on the conditions defined.
 - Increases instances during demand spikes and maintains performance. Decreases capacity during lulls to save money.
 - Suitable for stable demand applications or hourly/daily/weekly demand fluctuations.

 <table>
 <tr>
 	<-------------- Scale Out As Needed -----------------> <br> (These values can be modified based on cloud watch alarm values)
 </tr>
 <tr>
 	<td>Minimum Size</td>
 	<td>Desired Capacity</td>
 	<td>Maximum Size</td>
 </tr>
 </table>
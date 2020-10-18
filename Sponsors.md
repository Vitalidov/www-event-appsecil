---
---

## Sponsors

AppSec Israel Conference and Training are completely free to attend, thanks to the generous support of our sponsors!   


### Interested in becoming a sponsor for {{ site.title }}? 

Whether you have a product to showcase, you're offering a service, or you are recruiting - sponsoring the OWASP AppSec Israel Conference gets you the right exposure.   
This year we are expecting over 700 attendees, including security professionals, developers, managers, and more.

Sponsorship also helps support the OWASP community, and ensures that we can keep on making our conferences better and better. Sponsorship fees are intended to cover the costs of the conference only. If anything is left over, this is used to support the ongoing Chapter activity and improve the Conference even more. Since the Conference is open to all and free of charge to attend, we need your support to enable us to put on a great conference.

We are now offering several tiers of premium sponsorship, and various a la carte opportunities.   
There is also a cost-effective “Community Supporter” option for non-profits, government offices, small startups, and anyone else that wishes to support the community (Community Supporter level does not get a booth at the conference).  
For more details on the available sponsorship options please see [Conference Sponsorships]({{ site.url }}/www-event-stdoff/assets/files/Digital_AppSec_Israel_2020_Sponsorships.pdf).  

For more details and to confirm your sponsorship, please contact [Ori Troyna](mailto:ori.troyna@owasp.org).  


<table>
<thead>
<tr>
<th>Benefit</th>
<th style="text-align:center">Silver</th>
<th style="text-align:center">Gold</th>
<th style="text-align:center">Platinum Limited</th>
</tr>
</thead>
<tbody>
<tr>
<td>Logo on Website</td>
<td style="text-align:center">280x100</td>
<td style="text-align:center">375x150</td>
<td style="text-align:center">500x200</td>
</tr>
<tr>
<td>Logo on background</td>
<td style="text-align:center">No</td>
<td style="text-align:center">Yes</td>
<td style="text-align:center">Large</td>
</tr>
<tr>
<td>Logo on Chapter page</td>
<td style="text-align:center">No</td>
<td style="text-align:center">Yes</td>
<td style="text-align:center">Yes</td>
</tr>
<tr>
<td>Logo in Website header</td>
<td style="text-align:center">No</td>
<td style="text-align:center">No</td>
<td style="text-align:center">Yes</td>
</tr>
<tr>
<td>Vendor blurb on Sponsors page</td>
<td style="text-align:center">No</td>
<td style="text-align:center">50 words</td>
<td style="text-align:center">100 words</td>
</tr>
<tr>
<td>Link to sponsor chat</td>
<td style="text-align:center">Yes</td>
<td style="text-align:center">Yes</td>
<td style="text-align:center">Yes</td>
</tr>
<tr>
<td>Link to sponsor video/zoom</td>
<td style="text-align:center">No</td>
<td style="text-align:center">Yes</td>
<td style="text-align:center">Yes</td>
</tr>
<tr>
<td>Vendor passport raffle</td>
<td style="text-align:center">No</td>
<td style="text-align:center">Yes</td>
<td style="text-align:center">Yes</td>
</tr>
<tr>
<td>Price:</td>
<td style="text-align:center">$2,000</td>
<td style="text-align:center">$3,000</td>
<td style="text-align:center">$4,500</td>
</tr>
</tbody>
</table>

#### Gold Sponsors 
<div class="sponsor-tier">
  {% for sponsor in site.data.sponsors.gold %}
	  <span class="sponsor gold-sponsor">
		<a href="{{ sponsor.url }}" title="{{ sponsor.name }}" target="_blank">
		  {% if sponsor.image == %}
			<span>{{ sponsor.name }}</span>
		  {% else %} 
			<img src="assets/img/Sponsors/{{ sponsor.image }}">
		  {% endif %}
		</a>
	  </span>
  {% endfor %}
</div>
{% endif %}



---
title: It's a wrap for PHPSC17
---

Just a quick follow-up to everyone who attended, spoke, sponsored, or helped organise the PHP South Coast 2017 conference. The organisation team are slowly recovering and we hope you all had an incredible time.

## Thank you to all our sponsors :)
Don't forget that events like this rely heavily on sponsorship. It helps keep the ticket prices down, and means that we can do the best we can in delivering an amazing conference for everyone!

First and foremost, a massive thanks to our Platinum sponsor for this year, who are [Spectrum IT Recruitment](https://www.spectrumit.co.uk). Spectrum IT are based here in the south and are a non-pushy, technical-minded recruitment agency.

&nbsp;

[![Spectrum IT (Platinum sponsor)]({{ site.url }}/img/sponsors/spectrumit.png){: .img-responsive .center-block }](https://www.spectrumit.co.uk)

&nbsp;

And of course, our gold, silver and community-level sponsors:

<div class="container" id="sponsors-bar">
    <div class="row">
        {% for sponsor in site.data.sponsors %}
					{% if sponsor.level == 'Platinum' %}
						{% continue %}
					{% endif %}
					<a href="{{ sponsor.url }}" target="_blank" rel="noopener noreferrer">
							<img src="/img/sponsors/{{ sponsor.logo }}" alt="Sponsored by {{ sponsor.name }} ({{ sponsor.level }})"
									 title="{{ sponsor.name }} ({{ sponsor.level }})">
					</a>
        {% endfor %}
    </div>
</div>

## That's a wrap...
As many of you will know, this is the last PHP South Coast conference, at least in it's current incarnation. We did hear rumours of other similar events, or even social events that may be organised in the future. 

Whatever happens, I hope we have made a positive impact on your lives, and that we have encouraged you to become involved in the tech community, wherever you may be.

Our goals for PHP South Coast were:

* Build & promote the PHP community in the south coast
* Encourage submissions for new speakers into the conference speaking circuit
* Bring world-class speakers to the south of the UK at affordable prices for all

I believe we have achieved our goals here with the help of our amazing teams over the years. I am really proud of what we have achieved, and we have loved seeing some success stories of people improving themselves as a result of the hard work we put into the conference.

We are of course sad to say goodbye to this conference, never say never - something may be back in the future. Until then, farewell everyone, and THANK YOU! :)

Thanks & regards,

&nbsp;&mdash; James and the PHP South Coast conference team (for all the years!)
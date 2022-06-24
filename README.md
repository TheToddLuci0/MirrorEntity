# Mirror Entity
![](/images/card.png)

Imagine, if you will, a social engineer who wants to take a peek in the server room of the local bank. But alas! His buisnuess cards simply say "Big Dong Consulting", and a link to his domain of choice, but the last time he used it it was for an electrician pretext, and he's currently wearing a plumbers outfit! Worry not! By simply taping one button on his phone, his website is suddenly that of a plumber, thanks to Mirror Entity!

_For those wondering what happened to our brave hero, he was forced to display his LoA when the gaurd asked why a plumber needed to see the server room! Unfortunatly, there's nothing we can do to help if you choose a terrible pretext!_


## How it works
Mirror Entity has two main components: a cloudfront distro that serves your website(s), and a control plane that changes what the distro points at. Site content is housed in an S3 bucket. 